# Privatlivspolitik

**Ikrafttrædelsesdato:** 07.08.2026  
**Dataansvarlig:** Tomasz Rutkowski, en fysisk person med hjemsted i Polen, der driver applikationen "Chess M8" som uafhængig udvikler.  
**Appens navn:** ChessM8  

---

## 1. Indledning
Vi respekterer dit privatliv. Denne Privatlivspolitik forklarer, hvordan ChessM8 ("Appen") indsamler, bruger og beskytter oplysninger. Ved at bruge Appen accepterer du vilkårene i dette dokument.

---

## 2. Dataindsamling og -behandling (Local-First-arkitektur)
Appen er designet efter "Local-First"-princippet (prioritering af lokal behandling). Det betyder, at vi sætter dit privatliv i første række ved at gemme dine data direkte på din egen enhed.

### A. Personoplysninger
Appen henter offentlige skakpartidata (PGN-filer) fra tredjepartstjenester, som kan omfatte:
* Brugernavne (f.eks. fra Lichess.org eller Chess.com).
* Partitræk, tidsstempler og ratings.

Vi opbevarer ikke personoplysninger på vores egne servere; efter din anmodning overføres data direkte fra din enhed til tredjeparts-API'er.

### B. Tekniske data
* **IP-adresse:** Når Appen opretter forbindelse til eksterne API'er, er din IP-adresse synlig for disse udbydere (Chess.com/Lichess), men den sendes aldrig til os og opbevares ikke af os.

### C. Enhedstilladelser
For at fungere korrekt kræver Appen:
* **Internetadgang:** Udelukkende til at oprette forbindelse til API'erne for Chess.com og Lichess.org.
* **Lagerplads (Læse/Skrive):** Til at gemme og hente PGN-filer på din enhed (hvor relevant).

---

## 3. Formål og retsgrundlag for behandlingen

### A. Brugere i Det Europæiske Økonomiske Samarbejdsområde (EØS / GDPR)
Hvis du befinder dig i EØS, behandler vi personoplysninger til følgende formål:
1. **Levering af tjenesten og partianalyse:** For at give dig mulighed for at downloade skakpartier, analysere dem og få vist statistik i Appen.  
   *Retsgrundlag:* GDPR artikel 6, stk. 1, litra b (opfyldelse af en kontrakt for at levere ønskede funktioner).
2. **Sikring af teknisk funktionalitet:** Brug af internetadgang til sikker og pålidelig kommunikation med serverne for Chess.com og Lichess.org.  
   *Retsgrundlag:* GDPR artikel 6, stk. 1, litra f (legitim interesse i at sikre korrekt drift og sikkerhed).
3. **Lokal lagring til offlinebrug:** Lagring af PGN-filer på enheden for at give adgang til data uden en aktiv internetforbindelse.  
   *Retsgrundlag:* GDPR artikel 6, stk. 1, litra b.

---

## 4. Tredjepartstjenester
Appen fungerer som en klientgrænseflade. Når du bruger funktionen "Importer", opretter din enhed direkte forbindelse til:
* **Chess.com** (underlagt deres Privatlivspolitik)
* **Lichess.org** (underlagt deres Privatlivspolitik)

Vi fungerer ikke som mellemmand. Dine anmodningsheadere (herunder Appens User-Agent) er synlige for disse tjenester under forbindelsen.

---

## 5. Regionale privatlivsbestemmelser og brugerrettigheder

Da vi ikke gemmer dine data på eksterne servere, bevarer du direkte kontrol over dine oplysninger, uanset hvor du bor.

### 5.1. Det Europæiske Økonomiske Samarbejdsområde (EØS) og Storbritannien (UK)
I henhold til GDPR og UK GDPR har du følgende rettigheder:
* **Indsigt og dataportabilitet:** Alle data gemmes direkte på din personlige enhed.
* **Sletning af data:** Du kan til enhver tid slette alle data ved at rydde Appens cache/data i enhedsindstillingerne eller ved at afinstallere Appen.
* **Ret til indsigelse / Begrænsning:** Du kan til enhver tid stoppe behandlingen ved at ophøre med at bruge Appen eller ved at deaktivere importfunktionerne.

### 5.2. Californien / USA (CCPA / CPRA)
* **Intet salg eller deling af personoplysninger:** Vi sælger eller deler ikke personoplysninger og har ikke gjort det inden for de seneste 12 måneder.
* **Følsomme personoplysninger:** Vi indsamler eller behandler ikke følsomme personoplysninger, der kræver fravalgsmekanismer (opt-out).
* **Udøvelse af rettigheder:** Beboere i Californien kan udøve deres rettigheder ved at administrere enhedens lokale lager eller kontakte os. Som svar vil vi bekræfte, at vi ikke opbevarer nogen personoplysninger uden for din enhed.

### 5.3. Brasilien (LGPD)
I henhold til Lei Geral de Proteção de Dados (LGPD):
* **Retsgrundlag:** Behandling til spilanalyse og lokal lagring sker med hjemmel i art. 7(V) LGPD (opfyldelse af kontrakt). Tekniske forbindelser til eksterne API'er udføres i henhold til art. 7(IX) LGPD (legitim interesse).
* **Rettigheder:** Du kan udøve dine rettigheder til bekræftelse, indsigt eller sletning direkte ved at administrere det lokale lager på din enhed.

### 5.4. Indien (DPDP-loven fra 2023)
I henhold til Digital Personal Data Protection Act 2023:
* **Registreredes rettigheder:** Du har ret til at anmode om sletning af data og tilbagetrække dit samtykke til behandling.
* **Gennemførelse:** Da alle data befinder sig lokalt på din enhed, kan du udøve disse rettigheder direkte ved at rydde Appens data eller afinstallere den.

### 5.5. Andre jurisdiktioner
Hvis du bor i en anden jurisdiktion (f.eks. Canada, Australien, Schweiz, Japan eller Singapore), bevarer du fuld ret til indsigt i og sletning af dine lokale data direkte på din enhed.

---

## 6. International dataoverførsel
Når du bruger importfunktionen, opretter din enhed direkte forbindelse til tredjepartsservere:
* **Chess.com:** Servere kan være placeret i USA. Oprettelse af forbindelse til Chess.com sender standard netværksanmodninger (herunder IP-adresse og det anmodede brugernavn) direkte til servere i USA.
* **Lichess.org:** Infrastrukturen er placeret inden for Den Europæiske Union (Frankrig/Tyskland).

Hvis du bruger Appen uden for USA eller EU, vil igangsættelse af en import medføre en direkte grænseoverskridende overførsel af forbindelsesdata til disse eksterne servere. Vi kontrollerer ikke disse overførsler – de er underlagt den pågældende tjenestes Privatlivspolitik.

---

## 7. Analyse, profilering og tredjeparts-SDK'er
* **Ingen sporings-SDK'er:** Appen anvender ikke SDK'er til analyse, reklame eller fejlrapportering (såsom Google Analytics, Firebase eller AdMob).
* **Ingen profilering eller automatiseret beslutningstagning:** Vi profilerer dig ikke og træffer ingen automatiserede beslutninger baseret på personoplysninger eller spilhistorik.
* **Ingen telemetri:** Der sendes ingen data om dine interaktioner med Appen til os.

---

## 8. Datasikkerhed
På grund af datalagringens lokale karakter afhænger sikkerheden af beskyttelsen af din enhed. Vi anbefaler:
* At bruge adgangskode eller biometrisk lås på enheden.
* At holde styresystemet opdateret.
* At undgå at bruge Appen på enheder med uautoriserede modifikationer ("rootede" eller "jailbreakede").

---

## 9. Børns privatliv
Appen henvender sig ikke til børn under 16 år (eller den minimumsalder, der kræves i henhold til lokal lovgivning, hvis denne er lavere – under ingen omstændigheder under 13 år).

Vi tillader ikke bevidst børn under denne alder at bruge importfunktionerne. Brugen af tredjepartstjenester (Chess.com og Lichess.org) via Appen er underlagt deres egne aldersbegrænsninger. Forældre eller værger, der mener, at et barn har fået adgang til eksterne tjenester, bør kontakte Chess.com eller Lichess.org direkte.

---

## 10. Gældende lov og tvistbilæggelse
Denne Privatlivspolitik og enhver tvist, der måtte opstå heraf, er underlagt og skal fortolkes i overensstemmelse med polsk ret, med undtagelse af lovvalgsregler. Alle juridiske krav skal udelukkende afgøres af de kompetente domstole i Polen.

---

## 11. Ret til at indgive klage (EØS-brugere)
Hvis du befinder dig i EØS og mener, at dine rettigheder til databeskyttelse er blevet krænket, har du ret til at indgive en klage til din lokale databeskyttelsesmyndighed eller til vores ledende tilsynsmyndighed:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Warszawa, Polen  
Hjemmeside: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Ændringer af denne politik
Vi kan opdatere denne Privatlivspolitik med jævne mellemrum for at afspejle ændringer i vores praksis eller i lovgivningen. Vi vil informere om ændringer ved at offentliggøre den nye version i Appen eller på vores officielle hjemmeside samt opdatere "Ikrafttrædelsesdatoen" øverst.

I tilfælde af væsentlige ændringer i måden, hvorpå data behandles (f.eks. hvis local-first-arkitekturen forlades), vil vi give en mere fremtrædende meddelelse, f.eks. i form af en besked i Appen, før ændringerne træder i kraft.

---

## 13. Kontakt
Ved spørgsmål om privatliv eller udøvelse af dine rettigheder bedes du kontakte den Dataansvarlige:

**E-mail:** WorldiPL@protonmail.com  
*Fuld postadresse og yderligere identifikationsoplysninger er tilgængelige efter skriftlig anmodning i henhold til GDPR artikel 13.*
