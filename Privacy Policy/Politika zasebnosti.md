# Politika zasebnosti

**Datum začetka veljavnosti:** 07.08.2026  
**Upravljavec podatkov:** Tomasz Rutkowski, fizična oseba s sedežem na Poljskem, ki upravlja aplikacijo »Chess M8« kot neodvisni razvijalec.  
**Ime aplikacije:** ChessM8  

---

## 1. Uvod
Spoštujemo vašo zasebnost. Ta Politika zasebnosti pojasnjuje, kako ChessM8 (»Aplikacija«) zbira, uporablja in varuje informacije. Z uporabo Aplikacije se strinjate s pogoji, navedenimi v tem dokumentu.

---

## 2. Zbiranje in obdelava podatkov (Arhitektura Local-First)
Aplikacija je zasnovana na načelu »Local-First« (prednost lokalne obdelave). To pomeni, da postavljamo vašo zasebnost na prvo mesto tako, da vaše podatke hranimo neposredno v vaši napravi.

### A. Osebni podatki
Aplikacija iz storitev tretjih oseb pridobiva javne podatke o šahovskih partijah (datoteke PGN), ki lahko vključujejo:
* Uporabniška imena (npr. iz storitev Lichess.org ali Chess.com).
* Poteze v partijah, časovne žige in ocene/ratinge.

Osebnih podatkov ne shranjujemo na lastnih strežnikih; na vašo zahtevo se podatki prenašajo neposredno iz vaše naprave v API-je tretjih oseb.

### B. Tehnični podatki
* **IP naslov:** Ko se Aplikacija poveže z zunanjimi API-ji, je vaš IP naslov viden tem ponudnikom (Chess.com/Lichess), vendar se nikoli ne pošilja k nam in ga ne shranjujemo.

### C. Dovoljenja naprave
Za pravilno delovanje Aplikacija zahteva:
* **Dostop do interneta:** Izključno za povezovanje z API-ji storitev Chess.com in Lichess.org.
* **Shramba (Branje/Pisanje):** Za shranjevanje in branje datotek PGN v vaši napravi (kjer je primerno).

---

## 3. Nameni in pravne podlage za obdelavo

### A. Uporabniki iz Evropskega gospodarskega prostora (EGP / GDPR)
Če ste v EGP, osebne podatke obdelujemo za naslednje namene:
1. **Zagotavljanje storitve in analiza partij:** Omogočanje prenosa šahovskih partij, njihove analize in prikaza statistike v Aplikaciji.  
   *Pravna podlaga:* Člen 6(1)(b) GDPR (izvajanje pogodbe za zagotavljanje zahtevanih funkcij).
2. **Zagotavljanje tehnične funkcionalnosti:** Uporaba internetnega dostopa za varno in zanesljivo komunikacijo s strežniki Chess.com in Lichess.org.  
   *Pravna podlaga:* Člen 6(1)(f) GDPR (zakoniti interes za zagotavljanje pravilnega delovanja in varnosti).
3. **Lokalna shramba za uporabo brez povezave:** Shranjevanje datotek PGN v napravi za dostop do podatkov brez aktivne internetne povezave.  
   *Pravna podlaga:* Člen 6(1)(b) GDPR.

---

## 4. Storitve tretjih oseb
Aplikacija deluje kot odjemalski vmesnik. Ko uporabite funkcijo »Uvozi«, se vaša naprava neposredno poveže z:
* **Chess.com** (v skladu z njihovo Politiko zasebnosti)
* **Lichess.org** (v skladu z njihovo Politiko zasebnosti)

Pri tej izmenjavi ne delujemo kot posrednik. Glave vaših zahtevkov (vključno z User-Agentom Aplikacije) so tem storitvam vidne med trajanjem povezave.

---

## 5. Regionalne določbe o zasebnosti in pravice uporabnikov

Ker vaših podatkov ne shranjujemo na zunanjih strežnikih, ohranjate neposreden nadzor nad svojimi podatki ne glede na to, kje prebivate.

### 5.1. Evropski gospodarski prostor (EGP) in Združeno kraljestvo (UK)
V skladu z GDPR in UK GDPR imate naslednje pravice:
* **Dostop do podatkov in prenosljivost:** Vsi podatki so shranjeni neposredno na vaši osebni napravi.
* **Izbris podatkov:** Vse podatke lahko kadar koli izbrišete tako, da počistite predpomnilnik/podatke Aplikacije v nastavitvah naprave ali odstranite Aplikacijo.
* **Pravica do ugovora / Omejitev:** Obdelavo lahko kadar koli ustavite tako, da prenehate uporabljati Aplikacijo ali onemogočite funkcije uvoza.

### 5.2. Kalifornija / Združene države Amerike (CCPA / CPRA)
* **Brez prodaje ali deljenja osebnih podatkov:** Osebnih podatkov ne prodajamo in ne delimo ter tega nismo storili v zadnjih 12 mesecih.
* **Občutljivi osebni podatki:** Ne zbiramo in ne obdelujemo občutljivih osebnih podatkov, ki bi zahtevali mehanizme zavrnitve (opt-out).
* **Uveljavljanje pravic:** Prebivalci Kalifornije lahko svoje pravice uveljavljajo z upravljanjem lokalne shrambe naprave ali tako, da nas kontaktirajo. V odgovoru bomo potrdili, da zunaj vaše naprave ne hranimo nobenih osebnih podatkov.

### 5.3. Brazilija (LGPD)
V skladu z Lei Geral de Proteção de Dados (LGPD):
* **Pravne podlage:** Obdelava za analizo iger in lokalno shranjevanje poteka na podlagi člena 7(V) LGPD (izvajanje pogodbe). Tehnične povezave z zunanjimi API-ji se izvajajo na podlagi člena 7(IX) LGPD (zakoniti interes).
* **Pravice:** Svoje pravice do potrditve, dostopa ali izbrisa lahko uveljavljate neposredno z upravljanjem lokalne shrambe na vaši napravi.

### 5.4. Indija (Zakon DPDP iz leta 2023)
V skladu z Digital Personal Data Protection Act 2023:
* **Pravice posameznika:** Imate pravico zahtevati izbris podatkov in preklicati privolitev za obdelavo.
* **Uveljavitev:** Ker se vsi podatki nahajajo lokalno na vaši napravi, lahko te pravice uveljavljate neposredno z brisanjem podatkov Aplikacije ali njeno odstranitvijo.

### 5.5. Druge jurisdikcije
Če prebivate v drugi jurisdikciji (npr. Kanada, Avstralija, Švica, Japonska ali Singapur), ohranite polno pravico do dostopa in izbrisa svojih lokalnih podatkov neposredno na svoji napravi.

---

## 6. Mednarodni prenos podatkov
Pri uporabi funkcije uvoza se vaša naprava neposredno poveže s strežniki tretjih oseb:
* **Chess.com:** Strežniki se lahko nahajajo v Združenih državah Amerike. Povezava s Chess.com pošilja standardne omrežne zahteve (vključno z IP naslovom in zahtevanim uporabniškim imenom) neposredno na strežnike v ZDA.
* **Lichess.org:** Infrastruktura se nahaja na ozemlju Evropske unije (Francija/Nemčija).

V primeru uporabe Aplikacije zunaj ZDA ali EU bo začetek uvoza povzročil neposreden čezmejni prenos podatkov o povezavi na te zunanje strežnike. Teh prenosov ne nadzorujemo – zanje velja Politika zasebnosti ustrezne storitve.

---

## 7. Analitika, profiliranje in SDK-ji tretjih oseb
* **Brez sledilnih SDK-jev:** Aplikacija ne uporablja nobenih SDK-jev za analitiko, oglaševanje ali poročanje o napakah (kot so Google Analytics, Firebase ali AdMob).
* **Brez profiliranja ali avtomatiziranega odločanja:** Ne profiliramo vas in ne sprejemamo avtomatiziranih odločitev na podlagi osebnih podatkov ali zgodovine iger.
* **Brez telemetrije:** Nobeni podatki o vaši interakciji z Aplikacijo se ne pošiljajo k nam.

---

## 8. Varnost podatkov
Zaradi lokalne narave shranjevanja podatkov je varnost odvisna od zaščite vaše naprave. Priporočamo:
* Uporabo gesla naprave ali biometričnega zaklepanja.
* Redno posodabljanje operacijskega sistema.
* Izogibanje uporabi Aplikacije na napravah z nepooblaščenimi spremembami (»root« ali »jailbreak«).

---

## 9. Zasebnost otrok
Aplikacija ni namenjena otrokom, mlajšim od 16 let (ali minimalne starosti, ki jo zahteva lokalna zakonodaja, če je ta nižja – v nobenem primeru mlajšim od 13 let).

Otrokom, mlajšim od te starosti, zavestno ne dovoljujemo uporabe funkcij uvoza. Za uporabo storitev tretjih oseb (Chess.com in Lichess.org) prek Aplikacije veljajo njihove lastne starostne omejitve. Starši ali skrbniki, ki menijo, da je otrok pridobil dostop do zunanjih storitev, se morajo obrniti neposredno na Chess.com ali Lichess.org.

---

## 10. Veljavno pravo in reševanje sporov
To Politiko zasebnosti in vse spore, ki iz nje izhajajo, ureja in razlaga poljsko pravo, ob izključitvi kolizijskih pravil. Vsi pravni zahtevki bodo v izključni pristojnosti pristojnih sodišč na Poljskem.

---

## 11. Pravica do vložitve pritožbe (Uporabniki iz EGP)
Če ste v EGP in menite, da so bile vaše pravice do zasebnosti kršene, imate pravico vložiti pritožbo pri lokalnem organu za varstvo podatkov ali pri našem vodilnem nadzornem organu:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varšava, Poljska  
Spletno mesto: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Spremembe te politike
To Politiko zasebnosti lahko občasno posodobimo, da odraža spremembe v naših praksah ali zakonodaji. O spremembah vas bomo obvestili z objavo nove različice v Aplikaciji ali na naši uradni spletni strani ter posodobitvijo »Datuma začetka veljavnosti« na vrhu.

V primeru bistvenih sprememb načina obdelave podatkov (npr. opustitev arhitekture local-first) bomo pred uveljavitvijo sprememb zagotovili vidnejše obvestilo, npr. v obliki sporočila v Aplikaciji.

---

## 13. Stik
Za vprašanja o zasebnosti ali uveljavljanje vaših pravic se obrnite na Upravljavca podatkov:

**E-pošta:** WorldiPL@protonmail.com  
*Celoten poštni naslov in dodatni identifikacijski podatki so na voljo na pisno zahtevo v skladu s členom 13 GDPR.*
