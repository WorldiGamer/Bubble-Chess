# Privaatsuspoliitika

**Jõustumiskuupäev:** 07.08.2026  
**Vastutav töötleja:** Tomasz Rutkowski, Poolas asuv füüsiline isik, kes haldab rakendust „Chess M8” sõltumatu arendajana.  
**Rakenduse nimi:** ChessM8  

---

## 1. Sissejuhatus
Austame teie privaatsust. Käesolev Privaatsuspoliitika selgitab, kuidas ChessM8 („Rakendus”) teavet kogub, kasutab ja kaitseb. Rakendust kasutades nõustute käesolevas dokumendis sätestatud tingimustega.

---

## 2. Andmete kogumine ja töötlemine (Local-First arhitektuur)
Rakendus on loodud põhimõttel „Local-First” (kohaliku töötlemise prioriteet). See tähendab, et seame teie privaatsuse esikohale, salvestades teie andmed otse teie seadmesse.

### A. Isikuandmed
Rakendus laadib kolmandate osapoolte teenustest alla avalikke malepartiide andmeid (PGN-faile), mis võivad sisaldada:
* Kasutajanimesid (nt portaalidest Lichess.org või Chess.com).
* Partii käike, ajatempleid ja reitinguid.

Me ei salvesta isikuandmeid oma serverites; teie soovil edastatakse andmed otse teie seadmest kolmandate osapoolte API-desse.

### B. Tehnilised andmed
* **IP-aadress:** Kui Rakendus loob ühenduse väliste API-dega, on teie IP-aadress neile pakkujatele (Chess.com/Lichess) nähtav, kuid seda ei edastata kunagi meile ega salvestata meie poolt.

### C. Seadme load
Nõuetekohaseks toimimiseks vajab Rakendus:
* **Interneti-ühendust:** Ainult Chess.com-i ja Lichess.org-i API-dega ühenduse loomiseks.
* **Salvestusruumi (Lugemine/Kirjutamine):** PGN-failide salvestamiseks ja laadimiseks teie seadmes (vajaduse korral).

---

## 3. Töötlemise eesmärgid ja õiguslikud alused

### A. Euroopa Majanduspiirkonna (EMP / GDPR) kasutajad
Kui asute EMP-s, töötleme isikuandmeid järgmistel eesmärkidel:
1. **Teenuse osutamine ja partiide analüüs:** Et võimaldada teil malepartiisid alla laadida, neid analüüsida ja Rakenduses statistikat vaadata.  
   *Õiguslik alus:* GDPR artikli 6 lõike 1 punkt b (lepingu täitmine soovitud funktsioonide pakkumiseks).
2. **Tehnilise toimivuse tagamine:** Interneti-ühenduse kasutamine turvaliseks ja usaldusväärseks suhtluseks Chess.com-i ja Lichess.org-i serveritega.  
   *Õiguslik alus:* GDPR artikli 6 lõike 1 punkt f (õigustatud huvi nõuetekohase toimimise ja turvalisuse tagamiseks).
3. **Kohalik salvestusruum võrguühenduseta kasutamiseks:** PGN-failide salvestamine seadmesse, et võimaldada juurdepääsu andmetele ilma aktiivse internetiühenduseta.  
   *Õiguslik alus:* GDPR artikli 6 lõike 1 punkt b.

---

## 4. Kolmandate osapoolte teenused
Rakendus toimib kliendiliidesena. Kui kasutate funktsiooni „Impordi”, loob teie seade otseühenduse:
* **Chess.com** (vastavalt nende Privaatsuspoliitikale)
* **Lichess.org** (vastavalt nende Privaatsuspoliitikale)

Me ei tegutse vahendajana. Teie päringute päised (sealhulgas Rakenduse User-Agent) on ühenduse ajal nendele teenustele nähtavad.

---

## 5. Piirkondlikud privaatsussätted ja kasutaja õigused

Kuna me ei salvesta teie andmeid välistesse serveritesse, säilitate otsese kontrolli oma teabe üle sõltumata teie elukohast.

### 5.1. Euroopa Majanduspiirkond (EMP) ja Ühendkuningriik (UK)
Vastavalt GDPR-ile ja UK GDPR-ile on teil järgmised õigused:
* **Juurdepääs andmetele ja andmete ülekantavus:** Kõik andmed salvestatakse otse teie isiklikku seadmesse.
* **Andmete kustutamine:** Saate kõik andmed igal ajal kustutada, tühjendades seadme seadetes Rakenduse vahemälu/andmed või eemaldades Rakenduse.
* **Õigus esitada vastuväiteid / Piiramine:** Võite töötlemise igal ajal peatada, loobudes Rakenduse kasutamisest või lülitades impordifunktsioonid välja.

### 5.2. California / Ameerika Ühendriigid (CCPA / CPRA)
* **Isikuandmete müügi või jagamise puudumine:** Me ei müü ega jaga isikuandmeid ega ole seda teinud viimase 12 kuu jooksul.
* **Tundlikud isikuandmed:** Me ei kogu ega töötle tundlikke isikuandmeid, mis nõuaksid loobumismehhanisme (opt-out).
* **Õiguste teostamine:** California elanikud saavad oma õigusi teostada, hallates seadme kohalikku salvestusruumi või võttes meiega ühendust. Vastuseks kinnitame, et me ei hoia isikuandmeid väljaspool teie seadet.

### 5.3. Brasiilia (LGPD)
Vastavalt Lei Geral de Proteção de Dados (LGPD):
* **Õiguslikud alused:** Mängude analüüsimiseks ja kohalikuks salvestamiseks toimub töötlemine LGPD artikli 7(V) alusel (lepingu täitmine). Tehnilised ühendused väliste API-dega toimuvad LGPD artikli 7(IX) alusel (õigustatud huvi).
* **Õigused:** Saate kasutada oma õigusi kinnitamisele, juurdepääsule või kustutamisele otse oma seadme kohaliku salvestusruumi haldamise kaudu.

### 5.4. India (2023. aasta DPDP seadus)
Vastavalt Digital Personal Data Protection Act 2023:
* **Andmesubjekti õigused:** Teil on õigus taotleda andmete kustutamist ja võtta tagasi nõusolek töötlemiseks.
* **Rakendamine:** Kuna kõik andmed asuvad kohapeal teie seadmes, saate neid õigusi teostada otse Rakenduse andmete kustutamise või selle desinstallimise teel.

### 5.5. Muud jurisdiktsioonid
Kui elate teises jurisdiktsioonis (nt Kanada, Austraalia, Šveits, Jaapan või Singapur), säilib teil täielik õigus oma kohalikele andmetele juurde pääseda ja neid otse oma seadmes kustutada.

---

## 6. Rahvusvaheline andmeedastus
Impordifunktsiooni kasutamisel loob teie seade otseühenduse kolmandate osapoolte serveritega:
* **Chess.com:** Serverid võivad asuda Ameerika Ühendriikides. Chess.com-iga ühenduse loomine saadab tavalised võrgupäringud (sealhulgas IP-aadressi ja soovitud kasutajanime) otse USA serveritesse.
* **Lichess.org:** Infrastruktuur asub Euroopa Liidu territooriumil (Prantsusmaa/Saksamaa).

Kui kasutate Rakendust väljaspool USA-d või EL-i, toob impordi algatamine kaasa ühendusandmete otsese piiriülese edastamise nendesse välistesse serveritesse. Me ei kontrolli neid edastusi – neile kehtib vastava teenuse Privaatsuspoliitika.

---

## 7. Analüütika, profileerimine ja kolmandate osapoolte SDK-d
* **Jälgimis-SDK-sid pole:** Rakendus ei kasuta SDK-sid analüütikaks, reklaamiks ega vigadest teatamiseks (nt Google Analytics, Firebase või AdMob).
* **Profileerimist ega automatiseeritud otsuste tegemist pole:** Me ei profiili teid ega tee automatiseeritud otsuseid isikuandmete või mänguajaloo põhjal.
* **Telemeetriat pole:** Meile ei saadeta mingeid andmeid teie suhtluse kohta Rakendusega.

---

## 8. Andmeturve
Andmete kohaliku olemuse tõttu sõltub nende turvalisus teie seadme kaitsest. Soovitame:
* Kasutada seadme pääsukoodi või biomeetrilist lukku.
* Hoida operatsioonisüsteem uuendatuna.
* Vältida Rakenduse kasutamist volitamata muudatustega („rootitud” või „jailbreakitud”) seadmetes.

---

## 9. Laste privaatsus
Rakendus ei ole suunatud alla 16-aastastele lastele (või kohaliku seadusega nõutavast vanusest noorematele, kui see on madalam – mitte mingil juhul alla 13-aastastele).

Me ei luba teadlikult sellest vanusest noorematel lastel impordifunktsioone kasutada. Kolmandate osapoolte teenuste (Chess.com ja Lichess.org) kasutamisele Rakenduse kaudu kehtivad nende endi vanusepiirangud. Vanemad või eestkostjad, kes usuvad, et laps on saanud juurdepääsu välistele teenustele, peaksid võtma ühendust otse Chess.com-i või Lichess.org-iga.

---

## 10. Kohaldatav õigus ja vaidluste lahendamine
Käesolevat Privaatsuspoliitikat ja kõiki sellest tulenevaid vaidlusi reguleerib ja tõlgendatakse vastavalt Poola õigusele, välja arvatud kollisiooninormid. Kõik õiguslikud nõuded lahendatakse eranditult Poola pädevates kohtutes.

---

## 11. Õigus esitada kaebus (EMP kasutajad)
Kui asute EMP-s ja leiate, et teie privaatsusõigusi on rikutud, on teil õigus esitada kaebus oma kohalikule andmekaitseasutusele või meie juhtivale järelevalveasutusele:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varssavi, Poola  
Veebisait: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Muudatused käesolevas poliitikas
Võime seda Privaatsuspoliitikat perioodiliselt uuendada, et kajastada muudatusi meie tavades või õigusaktides. Muudatustest teavitame, avaldades uue versiooni Rakenduses või meie ametlikul veebisaidil ning uuendades dokumendi alguses olevat „Jõustumiskuupäeva”.

Oluliste muudatuste korral andmete töötlemises (nt kohalikust arhitektuurist loobumisel) esitame enne muudatuste jõustumist silmatorkavama teavituse, nt Rakenduse-sisese teate vormis.

---

## 13. Kontakt
Privaatsusega seotud küsimuste või oma õiguste teostamiseks võtke ühendust Vastutava töötlejaga:

**E-post:** WorldiPL@protonmail.com  
*Täielik postiaadress ja täiendavad identifitseerimisandmed on kättesaadavad kirjalikul taotlusel vastavalt GDPR artiklile 13.*
