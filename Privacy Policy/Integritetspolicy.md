# Integritetspolicy

**Ikraftträdandedatum:** 07.08.2026  
**Personuppgiftsansvarig:** Tomasz Rutkowski, en fysisk person med hemvist i Polen, som driver applikationen "Chess M8" som oberoende utvecklare.  
**Appens namn:** ChessM8  

---

## 1. Introduktion
Vi respekterar din integritet. Denna Integritetspolicy förklarar hur ChessM8 ("Appen") samlar in, använder och skyddar information. Genom att använda Appen godkänner du villkoren i detta dokument.

---

## 2. Datainsamling och databehandling (Local-First-arkitektur)
Appen är utformad enligt principen "Local-First" (prioriterad lokal behandling). Det innebär att vi sätter din integritet främst genom att lagra dina data direkt på din egen enhet.

### A. Personuppgifter
Appen hämtar offentliga schackpartidata (PGN-filer) från tredjepartstjänster, vilka kan inkludera:
* Användarnamn (t.ex. från Lichess.org eller Chess.com).
* Partidrag, tidsstämplar och ratingtal.

Vi lagrar inte personuppgifter på våra egna servrar; på din begäran överförs data direkt från din enhet till tredjeparts-API:er.

### B. Tekniska data
* **IP-adress:** När Appen ansluter till externa API:er är din IP-adress synlig för dessa leverantörer (Chess.com/Lichess), men den skickas aldrig till oss och lagras inte av oss.

### C. Enhetsbehörigheter
För att fungera korrekt kräver Appen:
* **Internetåtkomst:** Uteslutande för att ansluta till API:erna för Chess.com och Lichess.org.
* **Lagring (Läsa/Skriva):** För att spara och läsa in PGN-filer på din enhet (där tillämpligt).

---

## 3. Ändamål och rättslig grund för behandlingen

### A. Användare inom Europeiska ekonomiska samarbetsområdet (EES / GDPR)
Om du befinner dig inom EES behandlar vi personuppgifter för följande ändamål:
1. **Tillhandahållande av tjänsten och partianalys:** För att göra det möjligt att ladda ner schackpartier, analysera dem och visa statistik i Appen.  
   *Rättslig grund:* Art. 6.1 b GDPR (fullgörande av avtal för att tillhandahålla begärda funktioner).
2. **Säkerställande av teknisk funktionalitet:** Användning av internetanslutning för säker och pålitlig kommunikation med servrarna för Chess.com och Lichess.org.  
   *Rättslig grund:* Art. 6.1 f GDPR (berättigat intresse av att säkerställa korrekt funktion och säkerhet).
3. **Lokal lagring för offlineanvändning:** Lagring av PGN-filer på din enhet för att möjliggöra åtkomst till data utan aktiv internetanslutning.  
   *Rättslig grund:* Art. 6.1 b GDPR.

---

## 4. Tredjepartstjänster
Appen fungerar som ett klientgränssnitt. När du använder funktionen "Importera" ansluter din enhet direkt till:
* **Chess.com** (i enlighet med deras Integritetspolicy)
* **Lichess.org** (i enlighet med deras Integritetspolicy)

Vi agerar inte som mellanhand. Dina förfrågningsrubriker (inklusive Appens User-Agent) är synliga för dessa tjänster under anslutningen.

---

## 5. Regionala integritetsbestämmelser och användarrättigheter

Eftersom vi inte lagrar dina data på externa servrar behåller du direkt kontroll över din information oavsett var du bor.

### 5.1. Europeiska ekonomiska samarbetsområdet (EES) och Storbritannien (UK)
Enligt GDPR och UK GDPR har du följande rättigheter:
* **Tillgång och dataportabilitet:** Alla data lagras direkt på din personliga enhet.
* **Radering av data:** Du kan när som helst radera alla data genom att rensa Appens cacheminne/data i enhetsinställningarna eller genom att avinstallera Appen.
* **Rätt att göra invändningar / Begränsning:** Du kan när som helst avbryta behandlingen genom att sluta använda Appen eller inaktivera importfunktionerna.

### 5.2. Kalifornien / USA (CCPA / CPRA)
* **Ingen försäljning eller delning av personuppgifter:** Vi säljer inte och delar inte personuppgifter och har inte gjort det under de senaste 12 månaderna.
* **Känsliga personuppgifter:** Vi samlar inte in eller behandlar känsliga personuppgifter som kräver opt-out-mekanismer.
* **Utövande av rättigheter:** Invånare i Kalifornien kan utöva sina rättigheter genom att hantera enhetens lokala lagring eller kontakta oss. Som svar bekräftar vi att vi inte lagrar några personuppgifter utanför din enhet.

### 5.3. Brasilien (LGPD)
Enligt Lei Geral de Proteção de Dados (LGPD):
* **Rättslig grund:** Behandling för spelanalys och lokal lagring sker med stöd av Art. 7(V) LGPD (fullgörande av avtal). Tekniska anslutningar till externa API:er sker med stöd av Art. 7(IX) LGPD (berättigat intresse).
* **Rättigheter:** Du kan utöva dina rättigheter avseende bekräftelse, tillgång eller radering direkt genom att hantera det lokala minnet på din enhet.

### 5.4. Indien (DPDP-lagen 2023)
Enligt Digital Personal Data Protection Act 2023:
* **Registrerades rättigheter:** Du har rätt att begära radering av data och återkalla samtycke till behandling.
* **Genomförande:** Eftersom alla data finns lokalt på din enhet kan du utöva dessa rättigheter direkt genom att rensa Appens data eller avinstallera den.

### 5.5. Övriga jurisdiktioner
Om du bor i en annan jurisdiktion (t.ex. Kanada, Australien, Schweiz, Japan eller Singapore) behåller du full rätt till tillgång och radering av dina lokala data direkt på din enhet.

---

## 6. Internationell dataöverföring
När du använder importfunktionen ansluter din enhet direkt till tredjepartsservrar:
* **Chess.com:** Servrar kan finnas i USA. Anslutning till Chess.com skickar vanliga nätverksförfrågningar (inklusive IP-adress och begärt användarnamn) direkt till servrar i USA.
* **Lichess.org:** Infrastrukturen finns inom Europeiska unionen (Frankrike/Tyskland).

Om du använder Appen utanför USA eller EU innebär initiering av en import en direkt gränsöverskridande överföring av anslutningsdata till dessa externa servrar. Vi har ingen kontroll över dessa överföringar – de styrs av respektive tjänsts Integritetspolicy.

---

## 7. Analysverktyg, profilering och tredjeparts-SDK:er
* **Inga spårnings-SDK:er:** Appen använder inga SDK:er för analys, reklam eller kraschrapportering (såsom Google Analytics, Firebase eller AdMob).
* **Ingen profilering eller automatiserat beslutsfattande:** Vi profilerar dig inte och fattar inga automatiserade beslut baserade på personuppgifter eller spelhistorik.
* **Ingen telemetri:** Inga data om dina interaktioner med Appen skickas till oss.

---

## 8. Datasäkerhet
På grund av datalagringens lokala karaktär beror säkerheten på skyddet av din enhet. Vi rekommenderar:
* Att använda enhetens lösenkod eller biometriska lås.
* Att hålla operativsystemet uppdaterat.
* Att undvika att använda Appen på enheter med otillåtna modifieringar ("rootade" eller "jailbreakade").

---

## 9. Skydd av barns personuppgifter
Appen riktar sig inte till barn under 16 år (eller den minimiålder som krävs enligt lokal lag om den är lägre – dock under inga omständigheter under 13 år).

Vi tillåter inte medvetet barn under denna ålder att använda importfunktionerna. Användning av tredjepartstjänster (Chess.com och Lichess.org) via Appen omfattas av deras egna åldersgränser. Föräldrar eller vårdnadshavare som misstänker att ett barn har fått tillgång till externa tjänster bör kontakta Chess.com eller Lichess.org direkt.

---

## 10. Tillämplig lag och tvistlösning
Denna Integritetspolicy och alla tvister som härrör från den styrs av och tolkas i enlighet med polsk lag, med uteslutande av lagvalsregler. Eventuella rättsliga anspråk ska uteslutande avgöras av behöriga domstolar i Polen.

---

## 11. Rätt att lämna klagomål (EES-användare)
Om du befinner dig inom EES och anser att dina integritetsrättigheter har kränkts har du rätt att lämna in ett klagomål till din nationella dataskyddsmyndighet eller till vår ledande tillsynsmyndighet:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Warszawa, Polen  
Webbplats: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Ändringar i denna policy
Vi kan uppdatera denna Integritetspolicy periodvis för att återspegla förändringar i våra rutiner eller i lagstiftningen. Vi meddelar ändringar genom att publicera den nya versionen i Appen eller på vår officiella webbplats samt uppdatera "Ikraftträdandedatum" högst upp i dokumentet.

Vid väsentliga ändringar av hur data behandlas (t.ex. om vi frångår local-first-arkitekturen) kommer vi att ge ett mer framträdande meddelande, t.ex. via ett meddelande i Appen, innan ändringarna träder i kraft.

---

## 13. Kontakt
För frågor om integritet eller för att utöva dina rättigheter, vänligen kontakta Personuppgiftsansvarig:

**E-post:** WorldiPL@protonmail.com  
*Fullständig postadress och ytterligare identifieringsuppgifter tillhandahålls på skriftlig begäran i enlighet med Art. 13 GDPR.*
