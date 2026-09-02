# Zásady ochrany osobných údajov

**Dátum účinnosti:** 07.08.2026  
**Prevádzkovateľ údajov:** Tomasz Rutkowski, fyzická osoba so sídlom v Poľsku, prevádzkujúca aplikáciu „Chess M8“ ako nezávislý vývojár.  
**Názov aplikácie:** ChessM8  

---

## 1. Úvod
Rešpektujeme vaše súkromie. Tieto Zásady ochrany osobných údajov vysvetľujú, ako aplikácia ChessM8 (ďalej len „Aplikácia“) zhromažďuje, používa a chráni informácie. Používaním Aplikácie vyjadrujete súhlas s podmienkami uvedenými v tomto dokumente.

---

## 2. Zhromažďovanie a spracovanie údajov (Architektúra Local-First)
Aplikácia je navrhnutá na základe princípu „Local-First“ (prednosť lokálneho spracovania). To znamená, že kladieme vaše súkromie na prvé miesto a uchovávame vaše údaje priamo vo vašom zariadení.

### A. Osobné údaje
Aplikácia sťahuje verejné údaje šachových partií (súbory PGN) zo služieb tretích strán, ktoré môžu zahŕňať:
* Používateľské mená (napr. zo služieb Lichess.org alebo Chess.com).
* Ťahy v partiách, časové značky a hodnotenia (ratingy).

Neukladáme osobné údaje na vlastných serveroch; na vašu žiadosť sa údaje prenášajú priamo z vášho zariadenia do rozhraní API tretích strán.

### B. Technické údaje
* **IP adresa:** Pri pripájaní Aplikácie k externým rozhraniam API je vaša IP adresa viditeľná pre týchto poskytovateľov (Chess.com/Lichess), nikdy sa však neodosiela k nám ani ju neukladáme.

### C. Oprávnenia zariadenia
Pre správne fungovanie Aplikácia vyžaduje:
* **Prístup k internetu:** Výhradne za účelom pripojenia k rozhraniam API služieb Chess.com a Lichess.org.
* **Úložisko (Čítanie/Zápis):** Na ukladanie a načítanie súborov PGN vo vašom zariadení (v príslušných prípadoch).

---

## 3. Účely a právne základy spracovania

### A. Používatelia z Európskeho hospodárskeho priestoru (EHP / GDPR)
Ak sa nachádzate v EHP, spracúvame osobné údaje na nasledujúce účely:
1. **Poskytovanie služby a analýza partií:** Umožnenie sťahovania šachových partií, ich analýzy a zobrazovania štatistík v Aplikácii.  
   *Právny základ:* Čl. 6 ods. 1 písm. b) GDPR (plnenie zmluvy s cieľom poskytovania požadovaných funkcií).
2. **Zabezpečenie technickej funkčnosti:** Využitie prístupu k internetu na bezpečnú a spoľahlivú komunikáciu so servermi Chess.com a Lichess.org.  
   *Právny základ:* Čl. 6 ods. 1 písm. f) GDPR (oprávnený záujem spočívajúci v zabezpečení riadneho fungovania a bezpečnosti).
3. **Miestne úložisko pre použitie v režime offline:** Ukladanie súborov PGN do zariadenia na prístup k údajom bez aktívneho internetového pripojenia.  
   *Právny základ:* Čl. 6 ods. 1 písm. b) GDPR.

---

## 4. Služby tretích strán
Aplikácia funguje ako klientske rozhranie. Pri použití funkcie „Importovať“ sa vaše zariadenie pripája priamo k:
* **Chess.com** (v súlade s ich Zásadami ochrany osobných údajov)
* **Lichess.org** (v súlade s ich Zásadami ochrany osobných údajov)

Túto výmenu nesprostredkúvame. Hlavičky vašich požiadaviek (vrátane User-Agent Aplikácie) sú počas trvania spojenia viditeľné pre tieto služby.

---

## 5. Regionálne ustanovenia o ochrane súkromia a práva používateľov

Pretože vaše údaje neukladáme na externých serveroch, máte priamu kontrolu nad svojimi informáciami bez ohľadu na to, kde žijete.

### 5.1. Európsky hospodársky priestor (EHP) a Spojené kráľovstvo (UK)
Podľa GDPR a UK GDPR máte nasledujúce práva:
* **Prístup k údajom a prenosnosť:** Všetky údaje sú uložené priamo vo vašom osobnom zariadení.
* **Výmaz údajov:** Všetky údaje môžete kedykoľvek vymazať vymazaním vyrovnávacej pamäte/údajov Aplikácie v nastaveniach zariadenia alebo odinštalovaním Aplikácie.
* **Právo namietať / Obmedzenie spracúvania:** Spracúvanie môžete kedykoľvek ukončiť ukončením používania Aplikácie alebo vypnutím funkcií importu.

### 5.2. Kalifornia / Spojené štáty americké (CCPA / CPRA)
* **Žiadny predaj ani zdieľanie osobných údajov:** Osobné údaje nepredávame ani nezdieľame a nerobili sme tak ani v uplynulých 12 mesiacoch.
* **Citlivé osobné údaje:** Nezhromažďujeme ani nespracúvame citlivé osobné údaje vyžadujúce mechanizmy odhlásenia (opt-out).
* **Uplatnenie práv:** Obyvatelia Kalifornie môžu svoje práva uplatniť správou miestneho úložiska zariadenia alebo kontaktovaním našej podpory. V odpovedi potvrdíme, že mimo vášho zariadenia neuchovávame žiadne osobné údaje.

### 5.3. Brazília (LGPD)
Podľa Lei Geral de Proteção de Dados (LGPD):
* **Právne základy:** Spracúvanie na účely analýzy hier a lokálneho ukladania prebieha na základe čl. 7(V) LGPD (plnenie zmluvy). Technické spojenia s externými API sa realizujú na základe čl. 7(IX) LGPD (oprávnený záujem).
* **Práva:** Svoje práva na potvrdenie spracúvania, prístup alebo výmaz môžete uplatniť priamo správou miestneho úložiska vo svojom zariadení.

### 5.4. India (Zákon DPDP z roku 2023)
Podľa Digital Personal Data Protection Act 2023:
* **Práva dotknutej osoby:** Máte právo požadovať výmaz údajov a odvolať súhlas s ich spracúvaním.
* **Realizácia:** Vzhľadom na to, že sa všetky údaje nachádzajú lokálne vo vašom zariadení, môžete tieto práva uplatniť priamo vymazaním údajov Aplikácie alebo jej odinštalovaním.

### 5.5. Ostatné jurisdikcie
Ak žijete v inej jurisdikcii (napr. Kanada, Austrália, Švajčiarsko, Japonsko alebo Singapur), zachovávate si plné právo na prístup k svojim lokálnym údajom a ich výmaz priamo vo svojom zariadení.

---

## 6. Medzinárodný prenos údajov
Pri použití funkcie importu sa vaše zariadenie pripája priamo k serverom tretích strán:
* **Chess.com:** Servery sa môžu nachádzať v USA. Pripojenie k Chess.com odosiela štandardné sieťové požiadavky (vrátane IP adresy a požadovaného používateľského mena) priamo na servery v USA.
* **Lichess.org:** Infraštruktúra sa nachádza na území Európskej únie (Francúzsko/Nemecko).

V prípade používania Aplikácie mimo USA alebo EÚ spôsobí spustenie importu priamy cezhraničný prenos údajov pripojenia k týmto externým serverom. Tieto prenosy nekontrolujeme – riadia sa Zásadami ochrany osobných údajov príslušnej služby.

---

## 7. Analytika, profilovanie a externé súpravy SDK
* **Žiadne sledovacie SDK:** Aplikácia nepoužíva žiadne SDK na analýzu, reklamu ani hlásenie chýb (napr. Google Analytics, Firebase alebo AdMob).
* **Žiadne profilovanie ani automatizované rozhodovanie:** Neprofilujeme vás ani nevykonávame automatizované rozhodnutia na základe osobných údajov alebo hernej histórie.
* **Žiadna telemetria:** Žiadne údaje o interakcii s Aplikáciou sa nám nezasielajú.

---

## 8. Zabezpečenie údajov
Vzhľadom na lokálnu povahu ukladania údajov závisí ich bezpečnosť od zabezpečenia vášho zariadenia. Odporúčame:
* Používať prístupový kód zariadenia alebo biometrický zámok.
* Udržiavať operačný systém zariadenia aktualizovaný.
* Vyvarovať sa používaniu Aplikácie na zariadeniach s neoprávnene upraveným systémom („rootnutých“ alebo po „jailbreaku“).

---

## 9. Ochrana súkromia detí
Aplikácia nie je určená pre deti mladšie ako 16 rokov (alebo minimálneho veku vyžadovaného miestnym právom, ak je nižší – v žiadnom prípade mladšie ako 13 rokov).

Deťom mladším ako tento vek vedome neumožňujeme používať funkcie importu. Používanie služieb tretích strán (Chess.com a Lichess.org) prostredníctvom Aplikácie podlieha ich vlastným vekovým obmedzeniam. Rodičia alebo zákonní zástupcovia, ktorí sa domnievajú, že dieťa získalo prístup k externým službám, by mali kontaktovať priamo Chess.com alebo Lichess.org.

---

## 10. Rozhodné právo a riešenie sporov
Tieto Zásady ochrany osobných údajov a všetky spory z nich vyplývajúce sa riadia a vykladajú v súlade s poľským právom, s vylúčením kolíznych noriem. Všetky právne nároky budú riešené výhradne príslušnými súdmi v Poľsku.

---

## 11. Právo podať sťažnosť (Používatelia z EHP)
Ak sa nachádzate v EHP a domnievate sa, že vaše práva na ochranu osobných údajov boli porušené, máte právo podať sťažnosť na miestnom úrade na ochranu osobných údajov alebo na našom hlavnom dozornom úrade:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varšava, Poľsko  
Webové sídlo: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Zmeny týchto zásad
Tieto Zásady ochrany osobných údajov môžeme pravidelne aktualizovať, aby odrážali zmeny v našich postupoch alebo právnych predpisoch. O všetkých zmenách budeme informovať zverejnením novej verzie v Aplikácii alebo na našich oficiálnych stránkach a aktualizáciou „Dátumu účinnosti“ na začiatku dokumentu.

V prípade podstatných zmien v spôsobe spracovania údajov (napr. odklon od architektúry local-first) poskytneme viditeľnejšie oznámenie, napr. formou správy v Aplikácii, predtým ako zmeny vstúpia do platnosti.

---

## 13. Kontakt
V prípade otázok týkajúcich sa súkromia alebo uplatnenia vašich práv kontaktujte Prevádzkovateľa údajov:

**E-mail:** WorldiPL@protonmail.com  
*Úplná poštová adresa a ďalšie identifikačné údaje sú k dispozícii na písomnú žiadosť v súlade s čl. 13 GDPR.*
