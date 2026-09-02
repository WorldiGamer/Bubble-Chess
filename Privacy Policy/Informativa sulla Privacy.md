# Informativa sulla Privacy

**Data di entrata in vigore:** 07.08.2026  
**Titolare del Trattamento:** Tomasz Rutkowski, persona fisica residente in Polonia, che gestisce l'applicazione "Chess M8" come sviluppatore indipendente.  
**Nome dell'Applicazione:** ChessM8  

---

## 1. Introduzione
Rispettiamo la privacy degli utenti. La presente Informativa sulla Privacy illustra come ChessM8 ("l'Applicazione") raccoglie, utilizza e protegge le informazioni. Utilizzando l'Applicazione, l'utente accetta i termini definiti nel presente documento.

---

## 2. Raccolta e Trattamento dei Dati (Architettura Local-First)
L'Applicazione è progettata secondo il principio "Local-First" (priorità all'elaborazione locale). Ciò significa che mettiamo la privacy al primo posto memorizzando i dati direttamente sul dispositivo dell'utente.

### A. Dati Personali
L'Applicazione recupera dati pubblici di partite di scacchi (file PGN) da servizi di terze parti, che possono includere:
* Nomi utente (ad es. da Lichess.org o Chess.com).
* Mosse di gioco, marcatori temporali e punteggi/rating.

Non conserviamo dati personali sui nostri server; su richiesta dell'utente, i dati vengono trasmessi direttamente dal dispositivo alle API di terze parti.

### B. Dati Tecnici
* **Indirizzo IP:** Quando l'Applicazione si collega alle API esterne, l'indirizzo IP è visibile a tali provider (Chess.com/Lichess), ma non viene mai trasmesso né archiviato da noi.

### C. Autorizzazioni del Dispositivo
Per funzionare correttamente, l'Applicazione richiede:
* **Accesso a Internet:** Esclusivamente per la connessione alle API di Chess.com e Lichess.org.
* **Memoria (Lettura/Scrittura):** Per salvare e recuperare i file PGN sul dispositivo (ove applicabile).

---

## 3. Finalità e Basi Giuridiche del Trattamento

### A. Utenti dello Spazio Economico Europeo (SEE / GDPR)
Per gli utenti situati nel SEE, i dati personali vengono trattati per le seguenti finalità:
1. **Fornitura del servizio e analisi delle partite:** Per consentire il download delle partite di scacchi, l'analisi e la visualizzazione delle statistiche nell'Applicazione.  
   *Base giuridica:* Art. 6, par. 1, lett. b) GDPR (esecuzione di un contratto per fornire le funzionalità richieste).
2. **Funzionalità tecnica e sicurezza:** Utilizzo della connessione Internet per comunicare in modo sicuro e affidabile con i server di Chess.com e Lichess.org.  
   *Base giuridica:* Art. 6, par. 1, lett. f) GDPR (legittimo interesse a garantire il corretto funzionamento e la sicurezza).
3. **Archiviazione locale per l'uso offline:** Salvataggio dei file PGN sul dispositivo per consentire l'accesso ai dati senza connessione Internet attiva.  
   *Base giuridica:* Art. 6, par. 1, lett. b) GDPR.

---

## 4. Servizi di Terze Parti
L'Applicazione funge da interfaccia client. Quando si utilizza la funzione "Importa", il dispositivo si connette direttamente a:
* **Chess.com** (soggetto alla rispettiva Informativa sulla Privacy)
* **Lichess.org** (soggetto alla rispettiva Informativa sulla Privacy)

Non operiamo come intermediari. Le intestazioni di richiesta (incluso lo User-Agent dell'Applicazione) sono visibili a questi servizi durante la connessione.

---

## 5. Clausole Regionali sulla Privacy e Diritti degli Utenti

Poiché non memorizziamo i dati su server esterni, l'utente mantiene il controllo diretto sulle proprie informazioni indipendentemente dal luogo di residenza.

### 5.1. Spazio Economico Europeo (SEE) e Regno Unito (UK)
Ai sensi del GDPR e dell'UK GDPR, l'utente gode dei seguenti diritti:
* **Accesso e Portabilità dei Dati:** Tutti i dati sono memorizzati direttamente sul dispositivo personale.
* **Cancellazione dei Dati:** È possibile eliminare tutti i dati in qualsiasi momento cancellando la cache/dati dell'Applicazione nelle impostazioni del dispositivo o disinstallando l'Applicazione.
* **Diritto di Opposizione / Limitazione:** È possibile interrompere il trattamento in qualsiasi momento cessando l'uso dell'Applicazione o disabilitando le funzionalità di importazione.

### 5.2. California / Stati Uniti (CCPA / CPRA)
* **Nessuna Vendita o Condivisione di Dati Personali:** Non vendiamo né condividiamo dati personali e non lo abbiamo fatto negli ultimi 12 mesi.
* **Dati Personali Sensibili:** Non raccogliamo né trattiamo dati personali sensibili che richiedano meccanismi di opt-out.
* **Esercizio dei Diritti:** I residenti in California possono esercitare i propri diritti gestendo la memoria locale del dispositivo o contattandoci. In risposta, confermeremo di non conservare alcun dato personale al di fuori del dispositivo.

### 5.3. Brasile (LGPD)
Ai sensi della Lei Geral de Proteção de Dados (LGPD):
* **Basi Giuridiche:** Il trattamento per l'analisi delle partite e l'archiviazione locale avviene sulla base dell'Art. 7(V) LGPD (esecuzione del contratto). I collegamenti tecnici alle API esterne si basano sull'Art. 7(IX) LGPD (legittimo interesse).
* **Diritti:** È possibile esercitare i diritti di conferma, accesso o cancellazione direttamente tramite la gestione della memoria locale del dispositivo.

### 5.4. India (Legge DPDP del 2023)
Ai sensi del Digital Personal Data Protection Act 2023:
* **Diritti dell'Interessato:** L'utente ha il diritto di richiedere la cancellazione dei dati e revocare il consenso al loro trattamento.
* **Attuazione:** Poiché tutti i dati risiedono localmente sul dispositivo, tali diritti possono essere esercitati direttamente cancellando i dati dell'Applicazione o disinstallandola.

### 5.5. Altre Giurisdizioni
Per gli utenti residenti in altre giurisdizioni (ad es. Canada, Australia, Svizzera, Giappone o Singapore), permane il pieno diritto di accesso e cancellazione dei propri dati locali direttamente sul dispositivo.

---

## 6. Trasferimento Internazionale di Dati
Durante l'uso della funzione di importazione, il dispositivo si collega direttamente a server di terze parti:
* **Chess.com:** I server possono essere situati negli Stati Uniti. La connessione trasmette richieste di rete standard (inclusi indirizzo IP e nome utente richiesto) direttamente ai server negli USA.
* **Lichess.org:** L'infrastruttura si trova all'interno dell'Unione Europea (Francia/Germania).

In caso di utilizzo dell'Applicazione al di fuori degli Stati Uniti o dell'Unione Europea, l'importazione comporterà una trasmissione transfrontaliera diretta dei dati di connessione a tali server esterni. Tali trasferimenti sono regolati dall'Informativa sulla Privacy del rispettivo servizio.

---

## 7. Analisi, Profilazione e SDK di Terze Parti
* **Nessun SDK di Tracciamento:** L'Applicazione non include SDK per analisi, pubblicità o segnalazione di arresti anomali (come Google Analytics, Firebase o AdMob).
* **Nessuna Profilazione o Decisione Automatizzata:** Non eseguiamo profilazione né adottiamo decisioni automatizzate basate su dati personali o cronologia di gioco.
* **Nessuna Telemetria:** Nessun dato relativo alle interazioni con l'Applicazione viene inviato allo Sviluppatore.

---

## 8. Sicurezza dei Dati
Poiché i dati sono conservati localmente, la loro sicurezza dipende dalla protezione del dispositivo dell'utente. Si raccomanda di:
* Utilizzare un codice di accesso o blocco biometrico sul dispositivo.
* Mantenere aggiornato il sistema operativo.
* Evitare l'uso dell'Applicazione su dispositivi con modifiche non autorizzate ("root" o "jailbreak").

---

## 9. Privacy dei Minori
L'Applicazione non è rivolta a minori di 16 anni (o dell'età minima prevista dalla legislazione locale se inferiore, e in ogni caso non inferiore a 13 anni).

Non consentiamo consapevolmente l'uso delle funzioni di importazione a soggetti al di sotto di tale soglia. L'accesso a servizi terzi (Chess.com e Lichess.org) è soggetto alle rispettive limitazioni di età. I genitori o tutori che ritengano che un minore abbia effettuato l'accesso a servizi esterni devono contattare direttamente Chess.com o Lichess.org.

---

## 10. Legge Applicabile e Risoluzione delle Controversie
La presente Informativa sulla Privacy e qualsiasi controversia da essa derivante sono disciplinate e interpretate in conformità al diritto polacco, con esclusione delle norme sui conflitti di legge. Qualsiasi azione legale sarà devoluta esclusivamente ai tribunali competenti in Polonia.

---

## 11. Diritto di Proporre Reclamo (Utenti SEE)
Se l'utente si trova nel SEE e ritiene che siano stati violati i propri diritti alla privacy, ha il diritto di proporre reclamo all'autorità locale per la protezione dei dati o all'autorità di controllo capofila:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varsavia, Polonia  
Sito web: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Modifiche alla Presente Informativa
La presente Informativa sulla Privacy può essere periodicamente aggiornata. Le modifiche saranno rese note pubblicando la nuova versione nell'Applicazione o sul nostro sito ufficiale e aggiornando la "Data di entrata in vigore".

In caso di modifiche sostanziali al trattamento dei dati (ad es. abbandono dell'architettura local-first), forniremo un avviso più evidente nell'Applicazione prima dell'entrata in vigore delle modifiche.

---

## 13. Contatti
Per domande sulla privacy o per l'esercizio dei propri diritti, contattare il Titolare del Trattamento:

**E-mail:** WorldiPL@protonmail.com  
*L'indirizzo postale completo e ulteriori dati identificativi sono disponibili su richiesta scritta ai sensi dell'Art. 13 GDPR.*
