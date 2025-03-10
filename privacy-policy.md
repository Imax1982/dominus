# Privacy Policy per Dominus

**Ultimo aggiornamento: 10 marzo 2025**

## Introduzione

Questo documento descrive le pratiche relative alla privacy dell'applicazione Dominus, un'applicazione client per la gestione dei sistemi di monitoraggio Zabbix. Dominus è progettata per consentire agli utenti di connettersi ai propri server Zabbix e visualizzare informazioni di monitoraggio.

## Dati raccolti e gestiti

Dominus è progettata con un approccio orientato alla privacy e alla sicurezza. L'app:

- **Non raccoglie** dati personali degli utenti per scopi di analisi o marketing
- **Non trasmette** dati personali a server esterni tranne quelli specificati dall'utente (server Zabbix)
- **Non utilizza** tracker di terze parti o servizi di analisi
- **Non condivide** informazioni con terze parti

### Dati memorizzati sul dispositivo

Dominus salva localmente sul dispositivo dell'utente i seguenti dati per garantire la funzionalità dell'app:

1. **Credenziali di accesso ai server Zabbix**: 
   - URL dei server
   - Token API
   - Nomi dei server (impostati dall'utente)

2. **Preferenze dell'utente**:
   - Server predefinito
   - Preferenze di visualizzazione

Questi dati vengono memorizzati utilizzando le tecnologie di archiviazione sicura `AsyncStorage` e `expo-secure-store` e rimangono esclusivamente sul dispositivo dell'utente.

### Connessioni di rete

Dominus si connette esclusivamente ai server Zabbix specificati dall'utente. L'applicazione:

1. Invia richieste API autenticate al server Zabbix configurato dall'utente
2. Riceve e visualizza dati provenienti dal server Zabbix dell'utente
3. Non invia dati ad altri server esterni

## Sicurezza dei dati

Ci impegniamo a proteggere i dati degli utenti con le seguenti misure:

1. I token di autenticazione vengono memorizzati in modo sicuro utilizzando `expo-secure-store`
2. Le comunicazioni con i server Zabbix avvengono tramite connessioni sicure (HTTPS)
3. I dati sensibili non vengono mai memorizzati in log o file temporanei

## Diritti degli utenti

In qualsiasi momento, l'utente può:

1. Eliminare le credenziali dei server memorizzati nell'app
2. Cancellare tutti i dati locali disinstallando l'applicazione
3. Richiedere informazioni aggiuntive contattandoci all'indirizzo email sotto indicato

## Modifiche alla Privacy Policy

Ci riserviamo il diritto di aggiornare questa privacy policy in futuro. Le modifiche verranno comunicate attraverso l'aggiornamento di questo documento e, per modifiche significative, tramite avvisi nell'app.

## Contatti

Per qualsiasi domanda relativa alla privacy o all'utilizzo dei dati, è possibile contattarci al seguente indirizzo email:

[imax1982@gmail.com]
