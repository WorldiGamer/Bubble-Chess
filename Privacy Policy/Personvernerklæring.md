# Personvernerklæring

**Ikrafttredelsesdato:** 07.08.2026  
**Behandlingsansvarlig:** Tomasz Rutkowski, en fysisk person basert i Polen, som driver applikasjonen «Chess M8» som uavhengig utvikler.  
**Appens navn:** ChessM8  

---

## 1. Innledning
Vi respekterer ditt personvern. Denne Personvernerklæringen forklarer hvordan ChessM8 («Appen») samler inn, bruker og beskytter informasjon. Ved å bruke Appen godtar du vilkårene i dette dokumentet.

---

## 2. Datainnsamling og -behandling (Local-First-arkitektur)
Appen er designet etter «Local-First»-prinsippet (prioritering av lokal behandling). Dette betyr at vi setter ditt personvern først ved å lagre dataene dine direkte på din egen enhet.

### A. Personopplysninger
Appen henter offentlige sjakkpartidata (PGN-filer) fra tredjepartstjenester, som kan omfatte:
* Brukernavn (f.eks. fra Lichess.org eller Chess.com).
* Partitrekk, tidsstempler og rangeringer (ratings).

Vi lagrer ikke personopplysninger på våre egne servere; på din forespørsel overføres data direkte fra din enhet til tredjeparts-API-er.

### B. Tekniske data
* **IP-adresse:** Når Appen kobler seg til eksterne API-er, er din IP-adresse synlig for disse leverandørene (Chess.com/Lichess), men den sendes aldri til oss og lagres ikke av oss.

### C. Enhetstillatelser
For å fungere korrekt krever Appen:
* **Internettilgang:** Utelukkende for å koble til API-ene til Chess.com og Lichess.org.
* **Lagringsplass (Lese/Skrive):** For å lagre og hente PGN-filer på enheten din (der det er relevant).

---

## 3. Formål og rettslig grunnlag for behandlingen

### A. Brukere i Det europeiske økonomiske samarbeidsområdet (EØS / GDPR)
Hvis du befinner deg i EØS, behandler vi personopplysninger for følgende formål:
1. **Levering av tjenesten og partianalyse:** For å gjøre det mulig for deg å laste ned sjakkpartier, analysere dem og vise statistikk i Appen.  
   *Rettslig grunnlag:* GDPR artikkel 6(1)(b) (oppfyllelse av avtale for å levere ønskede funksjoner).
2. **Sikring av teknisk funksjonalitet:** Bruk av internettilgang for sikker og pålitelig kommunikasjon med serverne til Chess.com og Lichess.org.  
   *Rettslig grunnlag:* GDPR artikkel 6(1)(f) (berettiget interesse i å sikre riktig drift og sikkerhet).
3. **Lokal lagring for frakoblet bruk:** Lagring av PGN-filer på enheten for å gi tilgang til data uten aktiv internettforbindelse.  
   *Rettslig grunnlag:* GDPR artikkel 6(1)(b).

---

## 4. Tredjepartstjenester
Appen fungerer som et klientgrensesnitt. Når du bruker funksjonen «Importer», kobler enheten din seg direkte til:
* **Chess.com** (underlagt deres Personvernerklæring)
* **Lichess.org** (underlagt deres Personvernerklæring)

Vi opptrer ikke som mellomledd. Dine forespørselshoder (inkludert Appens User-Agent) er synlige for disse tjenestene under tilkoblingen.

---

## 5. Regionale personvernbestemmelser og brukerrettigheter

Fordi vi ikke lagrer dataene dine på eksterne servere, beholder du direkte kontroll over opplysningene dine uansett hvor du bor.

### 5.1. Det europeiske økonomiske samarbeidsområdet (EØS) og Storbritannia (UK)
I henhold til GDPR og UK GDPR har du følgende rettigheter:
* **Innsyn og dataportabilitet:** Alle data lagres direkte på din personlige enhet.
* **Sletting av data:** Du kan når som helst slette alle data ved å tømme Appens hurtigbuffer/data i enhetsinnstillingene eller ved å avinstallere Appen.
* **Rett til innsigelse / Begrensning:** Du kan stoppe behandlingen når som helst ved å slutte å bruke Appen eller deaktivere importfunksjonene.

### 5.2. California / USA (CCPA / CPRA)
* **Intet salg eller deling av personopplysninger:** Vi selger eller deler ikke personopplysninger, og har ikke gjort det i løpet av de siste 12 månedene.
* **Følsomme personopplysninger:** Vi samler ikke inn eller behandler følsomme personopplysninger som krever reservasjonsmekanismer (opt-out).
* **Utøvelse av rettigheter:** Innbyggere i California kan utøve sine rettigheter ved å administrere enhetens lokale lagring eller kontakte oss. Som svar vil vi bekrefte at vi ikke oppbevarer noen personopplysninger utenfor enheten din.

### 5.3. Brasil (LGPD)
I henhold til Lei Geral de Proteção de Dados (LGPD):
* **Rettslig grunnlag:** Behandling for spillanalyse og lokal lagring skjer med hjemmel i art. 7(V) LGPD (oppfyllelse av avtale). Tekniske tilkoblinger til eksterne API-er utføres i henhold til art. 7(IX) LGPD (berettiget interesse).
* **Rettigheter:** Du kan utøve dine rettigheter til bekreftelse, innsyn eller sletting direkte ved å administrere det lokale minnet på enheten din.

### 5.4. India (DPDP-loven av 2023)
I henhold til Digital Personal Data Protection Act 2023:
* **Den registrertes rettigheter:** Du har rett til å be om sletting av data og trekke tilbake samtykket til behandling.
* **Gjennomføring:** Siden alle data befinner seg lokalt på enheten din, kan du utøve disse rettighetene direkte ved å slette Appens data eller avinstallere den.

### 5.5. Andre jurisdiksjoner
Hvis du bor i en annen jurisdiksjon (f.eks. Canada, Australia, Sveits, Japan eller Singapore), beholder du full rett til innsyn i og sletting av dine lokale data direkte på enheten din.

---

## 6. Internasjonal dataoverføring
Når du bruker importfunksjonen, kobler enheten din seg direkte til tredjepartsservere:
* **Chess.com:** Servere kan være plassert i USA. Tilkobling til Chess.com sender standard nettverksforespørsler (inkludert IP-adresse og etterspurt brukernavn) direkte til servere i USA.
* **Lichess.org:** Infrastrukturen er plassert innenfor Den europeiske union (Frankrike/Tyskland).

Hvis du bruker Appen utenfor USA eller EU, vil igangsetting av en import medføre direkte grenseoverskridende overføring av tilkoblingsdata til disse eksterne serverne. Vi kontrollerer ikke disse overføringene – de er underlagt den aktuelle tjenestens Personvernerklæring.

---

## 7. Analyse, profilering og tredjeparts-SDK-er
* **Ingen sporings-SDK-er:** Appen bruker ingen SDK-er for analyse, reklame eller krasjrapportering (som Google Analytics, Firebase eller AdMob).
* **Ingen profilering eller automatisert beslutningstaking:** Vi profilerer deg ikke og tar ingen automatiserte beslutninger basert på personopplysninger eller spillhistorikk.
* **Ingen telemetri:** Ingen data om dine interaksjoner med Appen sendes til oss.

---

## 8. Datasikkerhet
På grunn av datalagringens lokale natur avhenger sikkerheten av beskyttelsen av din enhet. Vi anbefaler:
* Å bruke adgangskode eller biometrisk lås på enheten.
* Å holde operativsystemet oppdatert.
* Å unngå å bruke Appen på enheter med uautoriserte modifikasjoner («rootet» eller «jailbreaket»).

---

## 9. Barns personvern
Appen henvender seg ikke til barn under 16 år (eller minstealderen som kreves i henhold til lokal lovgivning hvis denne er lavere – under ingen omstendigheter under 13 år).

Vi tillater ikke bevisst barn under denne alderen å bruke importfunksjonene. Bruken av tredjepartstjenester (Chess.com og Lichess.org) via Appen er underlagt deres egne aldersbegrensninger. Foreldre eller foresatte som mistenker at et barn har fått tilgang til eksterne tjenester, bør kontakte Chess.com eller Lichess.org direkte.

---

## 10. Gjeldende lov og tvisteløsning
Denne Personvernerklæringen og enhver tvist som måtte oppstå herav, er underlagt og skal tolkes i samsvar med polsk rett, med unntak av lovvalgsregler. Alle juridiske krav skal utelukkende avgjøres av de kompetente domstolene i Polen.

---

## 11. Rett til å klage (EØS-brukere)
Hvis du befinner deg i EØS og mener at dine personvernrettigheter er blitt krenket, har du rett til å klage til ditt nasjonale datatilsyn eller til vår ledende tilsynsmyndighet:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Warszawa, Polen  
Nettsted: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Endringer i denne erklæringen
Vi kan oppdatere denne Personvernerklæringen periodisk for å gjenspeile endringer i vår praksis eller i lovgivningen. Vi vil informere om endringer ved å publisere den nye versjonen i Appen eller på vår offisielle nettside samt oppdatere «Ikrafttredelsesdatoen» øverst.

Ved vesentlige endringer i måten data behandles på (f.eks. hvis vi fraviker local-first-arkitekturen), vil vi gi et mer fremtredende varsel, f.eks. i form av en melding i Appen, før endringene trer i kraft.

---

## 13. Kontakt
Ved spørsmål om personvern eller utøvelse av dine rettigheter, vennligst kontakt Behandlingsansvarlig:

**E-post:** WorldiPL@protonmail.com  
*Fullstendig postadresse og ytterligere identifikasjonsopplysninger er tilgjengelig på skriftlig forespørsel i henhold til GDPR artikkel 13.*
