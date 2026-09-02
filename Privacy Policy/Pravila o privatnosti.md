# Pravila o privatnosti

**Datum stupanja na snagu:** 07.08.2026  
**Voditelj obrade podataka:** Tomasz Rutkowski, fizička osoba sa sjedištem u Poljskoj, koja upravlja aplikacijom „Chess M8” kao neovisni programer.  
**Naziv aplikacije:** ChessM8  

---

## 1. Uvod
Poštujemo vašu privatnost. Ova Pravila o privatnosti objašnjavaju kako ChessM8 („Aplikacija”) prikuplja, koristi i štiti podatke. Korištenjem Aplikacije pristajete na uvjete navedene u ovom dokumentu.

---

## 2. Prikupljanje i obrada podataka (Arhitektura Local-First)
Aplikacija je dizajnirana na načelu „Local-First” (prioritet lokalne obrade). To znači da vašu privatnost stavljamo na prvo mjesto pohranjivanjem podataka izravno na vašem uređaju.

### A. Osobni podaci
Aplikacija dohvaća javne podatke o šahovskim partijama (PGN datoteke) s usluga trećih strana, što može uključivati:
* Korisnička imena (npr. sa servisa Lichess.org ili Chess.com).
* Poteze u partijama, vremenske oznake i rejtinge.

Ne pohranjujemo osobne podatke na vlastitim poslužiteljima; na vaš zahtjev podaci se prenose izravno s vašeg uređaja na API-je trećih strana.

### B. Tehnički podaci
* **IP adresa:** Kada se Aplikacija spaja na vanjske API-je, vaša IP adresa vidljiva je tim pružateljima (Chess.com/Lichess), ali se nikada ne šalje nama niti je pohranjujemo.

### C. Dozvole uređaja
Za ispravan rad Aplikacija zahtijeva:
* **Pristup internetu:** Isključivo radi povezivanja s API-jima servisa Chess.com i Lichess.org.
* **Pohrana (Čitanje/Pisanje):** Za spremanje i učitavanje PGN datoteka na vašem uređaju (gdje je primjenjivo).

---

## 3. Svrhe i pravne osnove obrade

### A. Korisnici iz Europskog gospodarskog prostora (EGP / GDPR)
Ako se nalazite u EGP-u, osobne podatke obrađujemo u sljedeće svrhe:
1. **Pružanje usluge i analiza partija:** Kako bi vam se omogućilo preuzimanje šahovskih partija, njihova analiza i prikaz statistike u Aplikaciji.  
   *Pravna osnova:* Čl. 6. st. 1. t. (b) GDPR-a (izvršavanje ugovora radi pružanja traženih funkcionalnosti).
2. **Osiguravanje tehničke funkcionalnosti:** Korištenje internetskog pristupa za sigurnu i pouzdanu komunikaciju s poslužiteljima Chess.com i Lichess.org.  
   *Pravna osnova:* Čl. 6. st. 1. t. (f) GDPR-a (legitimni interes za osiguravanje pravilnog rada i sigurnosti).
3. **Lokalna pohrana za izvanmrežno korištenje:** Spremanje PGN datoteka na uređaju kako bi se omogućio pristup podacima bez aktivne internetske veze.  
   *Pravna osnova:* Čl. 6. st. 1. t. (b) GDPR-a.

---

## 4. Usluge trećih strana
Aplikacija funkcionira kao klijentsko sučelje. Kada koristite funkciju „Uvezi”, vaš se uređaj izravno spaja na:
* **Chess.com** (u skladu s njihovim Pravilima o privatnosti)
* **Lichess.org** (u skladu s njihovim Pravilima o privatnosti)

Ne djelujemo kao posrednik. Zaglavlja vaših zahtjeva (uključujući User-Agent Aplikacije) vidljiva su tim uslugama tijekom trajanja veze.

---

## 5. Regionalne odredbe o privatnosti i prava korisnika

Budući da vaše podatke ne pohranjujemo na vanjskim poslužiteljima, zadržavate izravnu kontrolu nad svojim informacijama bez obzira na to gdje živite.

### 5.1. Europski gospodarski prostor (EGP) i Ujedinjeno Kraljevstvo (UK)
Prema GDPR-u i UK GDPR-u imate sljedeća prava:
* **Pristup podacima i prenosivost:** Svi se podaci pohranjuju izravno na vašem osobnom uređaju.
* **Brisanje podataka:** Sve podatke možete izbrisati u bilo kojem trenutku brisanjem predmemorije/podataka Aplikacije u postavkama uređaja ili deinstaliranjem Aplikacije.
* **Pravo na prigovor / Ograničenje obrade:** Obradu možete prekinuti u bilo kojem trenutku prestankom korištenja Aplikacije ili onemogućavanjem funkcija uvoza.

### 5.2. Kalifornija / SAD (CCPA / CPRA)
* **Nema prodaje ili dijeljenja osobnih podataka:** Ne prodajemo niti dijelimo osobne podatke i nismo to činili u proteklih 12 mjeseci.
* **Osjetljivi osobni podaci:** Ne prikupljamo niti obrađujemo osjetljive osobne podatke koji zahtijevaju mehanizme odjave (opt-out).
* **Ostvarivanje prava:** Stanovnici Kalifornije mogu ostvariti svoja prava upravljanjem lokalnom pohranom uređaja ili kontaktiranjem s nama. U odgovoru ćemo potvrditi da izvan vašeg uređaja ne čuvamo nikakve osobne podatke.

### 5.3. Brazil (LGPD)
Prema Lei Geral de Proteção de Dados (LGPD):
* **Pravne osnove:** Obrada radi analize partija i lokalnog pohranjivanja temelji se na čl. 7(V) LGPD-a (izvršavanje ugovora). Tehničke veze s vanjskim API-jima temelje se na čl. 7(IX) LGPD-a (legitimni interes).
* **Prava:** Svoja prava na potvrdu, pristup ili brisanje možete ostvariti izravno upravljanjem lokalnom pohranom na vašem uređaju.

### 5.4. Indija (Zakon DPDP iz 2023.)
Prema Digital Personal Data Protection Act 2023:
* **Prava ispitanika:** Imate pravo zatražiti brisanje podataka i povući privolu za obradu.
* **Realizacija:** Budući da se svi podaci nalaze lokalno na vašem uređaju, ta prava možete ostvariti izravno brisanjem podataka Aplikacije ili njezinim deinstaliranjem.

### 5.5. Ostale jurisdikcije
Ako živite u drugoj jurisdikciji (npr. Kanada, Australija, Švicarska, Japan ili Singapur), zadržavate puno pravo pristupa i brisanja svojih lokalnih podataka izravno na svom uređaju.

---

## 6. Međunarodni prijenos podataka
Prilikom korištenja funkcije uvoza vaš se uređaj izravno spaja na poslužitelje trećih strana:
* **Chess.com:** Poslužitelji se mogu nalaziti u SAD-u. Spajanje na Chess.com šalje standardne mrežne zahtjeve (uključujući IP adresu i traženo korisničko ime) izravno poslužiteljima u SAD-u.
* **Lichess.org:** Infrastruktura se nalazi unutar Europske unije (Francuska/Njemačka).

U slučaju korištenja Aplikacije izvan SAD-a ili EU-a, pokretanje uvoza uzrokovat će izravan prekogranični prijenos podataka o vezi na te vanjske poslužitelje. Mi ne kontroliramo te prijenose – oni su regulirani Pravilima o privatnosti odgovarajuće usluge.

---

## 7. Analitika, profiliranje i vanjski SDK-ovi
* **Bez SDK-ova za praćenje:** Aplikacija ne koristi SDK-ove za analitiku, oglašavanje ili izvještavanje o rušenjima (kao što su Google Analytics, Firebase ili AdMob).
* **Bez profiliranja ili automatiziranog donošenja odluka:** Ne profiliramo vas niti donosimo automatizirane odluke na temelju osobnih podataka ili povijesti igara.
* **Bez telemetrije:** Nikakvi podaci o vašoj interakciji s Aplikacijom ne šalju se nama.

---

## 8. Sigurnost podataka
Zbog lokalne prirode pohrane podataka, njihova sigurnost ovisi o zaštiti vašeg uređaja. Preporučujemo:
* Korištenje pristupnog koda ili biometrijskog zaključavanja uređaja.
* Redovito ažuriranje operativnog sustava.
* Izbjegavanje korištenja Aplikacije na uređajima s neovlaštenim izmjenama („rootanim” ili „jailbreakanim”).

---

## 9. Privatnost djece
Aplikacija nije namijenjena djeci mlađoj od 16 godina (ili minimalne dobi propisane lokalnim zakonom ako je niža – ni u kojem slučaju mlađoj od 13 godina).

Djeci mlađoj od te dobi svjesno ne dopuštamo korištenje funkcija uvoza. Korištenje usluga trećih strana (Chess.com i Lichess.org) putem Aplikacije podliježe njihovim vlastitim dobnim ograničenjima. Roditelji ili skrbnici koji smatraju da je dijete pristupilo vanjskim uslugama trebaju se izravno obratiti servisima Chess.com ili Lichess.org.

---

## 10. Mjerodavno pravo i rješavanje sporova
Ova Pravila o privatnosti i svi sporovi koji iz njih proizlaze uređuju se i tumače u skladu s poljskim pravom, isključujući kolizijska pravila. Svi pravni zahtjevi bit će u isključivoj nadležnosti sudova u Poljskoj.

---

## 11. Pravo na podnošenje pritužbe (Korisnici iz EGP-a)
Ako se nalazite u EGP-u i smatrate da su vaša prava na zaštitu privatnosti povrijeđena, imate pravo podnijeti pritužbu lokalnom tijelu za zaštitu podataka ili našem vodećem nadzornom tijelu:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varšava, Poljska  
Internetska stranica: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Izmjene ovih Pravila
Ova Pravila o privatnosti možemo povremeno ažurirati kako bismo odrazili promjene u našim postupcima ili zakonskim propisima. O svim promjenama obavijestit ćemo vas objavljivanjem nove verzije u Aplikaciji ili na našoj službenoj web stranici te ažuriranjem „Datuma stupanja na snagu”.

U slučaju bitnih promjena načina obrade podataka (npr. napuštanje arhitekture local-first), pružit ćemo uočljiviju obavijest, npr. putem poruke u Aplikaciji, prije nego što promjene stupe na snagu.

---

## 13. Kontakt
Za pitanja o privatnosti ili ostvarivanje svojih prava obratite se Voditelju obrade podataka:

**E-pošta:** WorldiPL@protonmail.com  
*Puna poštanska adresa i dodatni identifikacijski podaci dostupni su na pisani zahtjev u skladu s čl. 13. GDPR-a.*
