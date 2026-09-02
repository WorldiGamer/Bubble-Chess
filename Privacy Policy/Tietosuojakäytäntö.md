# Tietosuojakäytäntö

**Voimaantulopäivä:** 07.08.2026  
**Rekisterinpitäjä:** Tomasz Rutkowski, Puolassa toimiva luonnollinen henkilö, joka ylläpitää "Chess M8" -sovellusta itsenäisenä kehittäjänä.  
**Sovelluksen nimi:** ChessM8  

---

## 1. Johdanto
Kunnioitamme yksityisyyttäsi. Tämä Tietosuojakäytäntö selittää, miten ChessM8 ("Sovellus") kerää, käyttää ja suojaa tietoja. Käyttämällä Sovellusta hyväksyt tässä asiakirjassa esitetyt ehdot.

---

## 2. Tietojen kerääminen ja käsittely (Local-First-arkkitehtuuri)
Sovellus on suunniteltu "Local-First" -periaatteella (paikallisen käsittelyn ensisijaisuus). Tämä tarkoittaa, että asetamme yksityisyytesi etusijalle tallentamalla tietosi suoraan omalle laitteellesi.

### A. Henkilötiedot
Sovellus noutaa julkisia shakkipelitietoja (PGN-tiedostoja) kolmansien osapuolten palveluista, joihin voi sisältyä:
* Käyttäjänimiä (esim. Lichess.org- tai Chess.com-palveluista).
* Pelisiirtoja, aikaleimoja ja vahvuuslukuja (ratingeja).

Emme tallenna henkilötietoja omille palvelimillemme; pyynnöstäsi tiedot siirretään suoraan laitteeltasi kolmansien osapuolten API-rajapintoihin.

### B. Tekniset tiedot
* **IP-osoite:** Kun Sovellus muodostaa yhteyden ulkoisiin API-rajapintoihin, IP-osoitteesi näkyy näille palveluntarjoajille (Chess.com/Lichess), mutta sitä ei koskaan lähetetä meille eikä tallenneta toimestamme.

### C. Laiteluvat
Toimiakseen oikein Sovellus vaatii:
* **Internet-yhteyden:** Yksinomaan yhteyden muodostamiseen Chess.comin ja Lichess.orgin API-rajapintoihin.
* **Tallennustilan (Luku/Kirjoitus):** PGN-tiedostojen tallentamiseen ja lataamiseen laitteellasi (soveltuvin osin).

---

## 3. Käsittelyn tarkoitukset ja oikeusperusteet

### A. Euroopan talousalueen (ETA / GDPR) käyttäjät
Jos olet ETA-alueella, käsittelemme henkilötietoja seuraaviin tarkoituksiin:
1. **Palvelun tarjoaminen ja pelianalyysi:** Jotta voit ladata shakkipelejä, analysoida niitä ja katsella tilastoja Sovelluksessa.  
   *Oikeusperuste:* GDPR 6 artiklan 1 kohdan b alakohta (sopimuksen täytäntöönpano pyydettyjen ominaisuuksien tarjoamiseksi).
2. **Teknisen toimivuuden varmistaminen:** Internet-yhteyden käyttö turvalliseen ja luotettavaan viestintään Chess.comin ja Lichess.orgin palvelimien kanssa.  
   *Oikeusperuste:* GDPR 6 artiklan 1 kohdan f alakohta (oikeutettu etu asianmukaisen toiminnan ja turvallisuuden takaamiseksi).
3. **Paikallinen tallennus offline-käyttöä varten:** PGN-tiedostojen tallentaminen laitteelle, jotta tietoja voidaan käyttää ilman aktiivista internetyhteyttä.  
   *Oikeusperuste:* GDPR 6 artiklan 1 kohdan b alakohta.

---

## 4. Kolmansien osapuolten palvelut
Sovellus toimii asiakasliittymänä. Kun käytät "Tuo" (Import) -toimintoa, laitteesi muodostaa suoran yhteyden:
* **Chess.com** (heitä koskevan Tietosuojakäytännön mukaisesti)
* **Lichess.org** (heitä koskevan Tietosuojakäytännön mukaisesti)

Emme toimi välikätenä. Pyyntösi otsikkotiedot (mukaan lukien Sovelluksen User-Agent) näkyvät näille palveluille yhteyden aikana.

---

## 5. Alueelliset tietosuojalausekkeet ja käyttäjien oikeudet

Koska emme tallenna tietojasi ulkoisille palvelimille, säilytät suoran hallinnan tietoihisi riippumatta siitä, missä asut.

### 5.1. Euroopan talousalue (ETA) ja Yhdistynyt kuningaskunta (UK)
GDPR:n ja UK GDPR:n mukaisesti sinulla on seuraavat oikeudet:
* **Pääsy tietoihin ja tietojen siirrettävyys:** Kaikki tiedot tallennetaan suoraan henkilökohtaiseen laitteeseesi.
* **Tietojen poistaminen:** Voit poistaa kaikki tiedot milloin tahansa tyhjentämällä Sovelluksen välimuistin/tiedot laitteen asetuksista tai poistamalla Sovelluksen asennuksen.
* **Vastustamisoikeus / Käsittelyn rajoittaminen:** Voit lopettaa käsittelyn milloin tahansa lopettamalla Sovelluksen käytön tai poistamalla tuontitoiminnot käytöstä.

### 5.2. Kalifornia / Yhdysvallat (CCPA / CPRA)
* **Ei henkilötietojen myyntiä tai jakamista:** Emme myy tai jaa henkilötietoja emmekä ole tehneet niin viimeisten 12 kuukauden aikana.
* **Arkaluonteiset henkilötiedot:** Emme kerää tai käsittele arkaluonteisia henkilötietoja, jotka edellyttäisivät kieltäytymismekanismeja (opt-out).
* **Oikeuksien käyttäminen:** Kalifornian asukkaat voivat käyttää oikeuksiaan hallitsemalla laitteen paikallista tallennustilaa tai ottamalla meihin yhteyttä. Vastauksena vahvistamme, ettemme säilytä mitään henkilötietoja laitteesi ulkopuolella.

### 5.3. Brasilia (LGPD)
Lei Geral de Proteção de Dados (LGPD) -lain mukaisesti:
* **Oikeusperusteet:** Pelianalyysin ja paikallisen tallennuksen käsittely perustuu LGPD:n 7(V) artiklaan (sopimuksen täytäntöönpano). Tekniset yhteydet ulkoisiin API-rajapintoihin perustuvat LGPD:n 7(IX) artiklaan (oikeutettu etu).
* **Oikeudet:** Voit käyttää vahvistus-, pääsy- tai poisto-oikeuksiasi suoraan hallitsemalla laitteesi paikallista tallennustilaa.

### 5.4. Intia (Vuoden 2023 DPDP-laki)
Digital Personal Data Protection Act 2023 -lain mukaisesti:
* **Rekisteröidyn oikeudet:** Sinulla on oikeus pyytää tietojen poistamista ja peruuttaa suostumuksesi käsittelyyn.
* **Toteutus:** Koska kaikki tiedot sijaitsevat paikallisesti laitteellasi, voit käyttää näitä oikeuksia suoraan tyhjentämällä Sovelluksen tiedot tai poistamalla sen asennuksen.

### 5.5. Muut lainkäyttöalueet
Jos asut muulla lainkäyttöalueella (esim. Kanada, Australia, Sveitsi, Japani tai Singapore), säilytät täyden oikeuden tarkastella ja poistaa paikallisia tietojasi suoraan laitteellasi.

---

## 6. Kansainvälinen tiedonsiirto
Tuontitoimintoa käytettäessä laitteesi muodostaa suoran yhteyden kolmansien osapuolten palvelimiin:
* **Chess.com:** Palvelimet voivat sijaita Yhdysvalloissa. Yhteyden muodostaminen Chess.comiin lähettää tavanomaiset verkkopyynnöt (mukaan lukien IP-osoitteen ja pyydetyn käyttäjänimen) suoraan Yhdysvalloissa sijaitseville palvelimille.
* **Lichess.org:** Infrastruktuuri sijaitsee Euroopan unionin alueella (Ranska/Saksa).

Jos käytät Sovellusta Yhdysvaltojen tai EU:n ulkopuolelta, tuonnin käynnistäminen johtaa yhteystietojen suoraan rajatylittävään siirtoon näille ulkoisille palvelimille. Emme valvo näitä siirtoja – niihin sovelletaan kyseisen palvelun Tietosuojakäytäntöä.

---

## 7. Analytiikka, profilointi ja kolmansien osapuolten SDK:t
* **Ei seuranta-SDK:ita:** Sovellus ei käytä SDK-kirjastoja analytiikkaan, mainontaan tai virheraportointiin (kuten Google Analytics, Firebase tai AdMob).
* **Ei profilointia tai automaattista päätöksentekoa:** Emme profiloi sinua emmekä tee automatisoituja päätöksiä henkilötietojen tai pelihistorian perusteella.
* **Ei telemetriaa:** Mitään tietoja Sovelluksen käytöstäsi ei lähetetä meille.

---

## 8. Tietoturva
Tietojen tallennuksen paikallisen luonteen vuoksi turvallisuus riippuu laitteesi suojauksesta. Suosittelemme:
* Laitteen pääsykoodin tai biometrisen lukituksen käyttöä.
* Käyttöjärjestelmän pitämistä ajan tasalla.
* Sovelluksen käytön välttämistä laitteilla, joissa on luvattomia järjestelmämuutoksia ("rootattu" tai "jailbreakattu").

---

## 9. Lasten yksityisyys
Sovellusta ei ole suunnattu alle 16-vuotiaille lapsille (tai paikallisen lain edellyttämää vähimmäisikää nuoremmille, jos se on alhaisempi – ei missään tapauksessa alle 13-vuotiaille).

Emme tietoisesti salli tämän ikärajan alittavien lasten käyttää tuontitoimintoja. Kolmansien osapuolten palveluiden (Chess.com ja Lichess.org) käyttöön Sovelluksen kautta sovelletaan niiden omia ikärajoituksia. Vanhempien tai huoltajien, jotka uskovat lapsen päässeen ulkoisiin palveluihin, tulee ottaa yhteyttä suoraan Chess.comiin tai Lichess.orgiin.

---

## 10. Sovellettava laki ja riitojenratkaisu
Tähän Tietosuojakäytäntöön ja kaikista siitä johtuviin riitoihin sovelletaan Puolan lakia ja niitä tulkitaan sen mukaisesti, lukuun ottamatta lainvalintasääntöjä. Kaikki oikeudelliset vaatimukset ratkaistaan yksinomaan Puolan toimivaltaisissa tuomioistuimissa.

---

## 11. Oikeus tehdä valitus (ETA-käyttäjät)
Jos olet ETA-alueella ja katsot, että tietosuojaoikeuksiasi on loukattu, sinulla on oikeus tehdä valitus paikalliselle tietosuojaviranomaisellesi tai johtavalle valvontaviranomaisellemme:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varsova, Puola  
Verkkosivusto: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Muutokset tähän käytäntöön
Saatamme päivittää tätä Tietosuojakäytäntöä säännöllisesti vastaamaan käytäntöjemme tai lakisääteisten vaatimusten muutoksia. Ilmoitamme muutoksista julkaisemalla uuden version Sovelluksessa tai virallisella verkkosivustollamme ja päivittämällä asiakirjan yläosassa olevan "Voimaantulopäivän".

Mikäli tietojenkäsittelytapoihin tehdään olennaisia muutoksia (esim. luovutaan local-first-arkkitehtuurista), annamme näkyvämmän ilmoituksen, esim. Sovelluksen sisäisellä ilmoituksella, ennen muutosten voimaantuloa.

---

## 13. Yhteystiedot
Yksityisyyteen liittyvissä kysymyksissä tai oikeuksiesi käyttämiseksi ota yhteyttä Rekisterinpitäjään:

**Sähköposti:** WorldiPL@protonmail.com  
*Täydellinen postiosoite ja muut tunnistetiedot ovat saatavilla kirjallisesta pyynnöstä GDPR:n 13 artiklan mukaisesti.*
