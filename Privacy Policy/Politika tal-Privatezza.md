# Politika tal-Privatezza

**Data tad-Dħul fis-Seħħ:** 07.08.2026  
**Kontrollur tad-Dejta:** Tomasz Rutkowski, individwu bbażat fil-Polonja, li jopera l-applikazzjoni "Chess M8" bħala żviluppatur indipendenti.  
**Isem tal-Applikazzjoni:** ChessM8  

---

## 1. Introduzzjoni
Aħna nirrispettaw il-privatezza tiegħek. Din il-Politika tal-Privatezza tispjega kif ChessM8 ("l-Applikazzjoni") tiġbor, tuża u tipproteġi l-informazzjoni. Billi tuża l-Applikazzjoni, inti taqbel mat-termini stipulati f'dan id-dokument.

---

## 2. Ġbir u Pproċessar ta' Dejta (Arkitettura Local-First)
L-Applikazzjoni hija mfassla fuq il-prinċipju "Local-First" (prijorità għall-ipproċessar lokali). Dan ifisser li npoġġu l-privatezza tiegħek l-ewwel billi naħżnu d-dejta tiegħek direttament fuq it-tagħmir tiegħek stess.

### A. Dejta Personali
L-Applikazzjoni tirkupra dejta pubblika ta' logħbiet taċ-ċess (fajls PGN) minn servizzi ta' partijiet terzi, li jistgħu jinkludu:
* Usernames (eż. minn Lichess.org jew Chess.com).
* Mossi tal-logħba, timestamps u ratings.

Aħna ma naħżnux dejta personali fuq is-servers tagħna stess; fuq talba tiegħek, id-dejta tiġi trażmessa direttament mit-tagħmir tiegħek lill-APIs ta' partijiet terzi.

### B. Dejta Teknika
* **Indirizz IP:** Meta l-Applikazzjoni tikkonnettja ma' APIs esterni, l-indirizz IP tiegħek ikun viżibbli għal dawk il-fornituri (Chess.com/Lichess), iżda qatt ma jintbagħat lilna u lanqas ma jinħażen minna.

### C. Permessi tat-Tagħmir
Biex taħdem sewwa, l-Applikazzjoni teħtieġ:
* **Aċċess għall-Internet:** Esklussivament biex tikkonnettja mal-APIs ta' Chess.com u Lichess.org.
* **Ħażna (Qari/Kitba):** Biex tissejvja u tirkupra fajls PGN fuq it-tagħmir tiegħek (fejn applikabbli).

---

## 3. Skopijiet u Bażijiet Legali għall-Ipproċessar

### A. Utenti fiż-Żona Ekonomika Ewropea (ŻEE / GDPR)
Jekk tinsab fiż-ŻEE, aħna nipproċessaw dejta personali għall-iskopijiet li ġejjin:
1. **Forniment tas-servizz u analiżi tal-logħob:** Biex jippermettilek tniżżel logħbiet taċ-ċess, tanalizzahom u tara statistika fl-Applikazzjoni.  
   *Bażi Legali:* Artikolu 6(1)(b) tal-GDPR (eżekuzzjoni ta' kuntratt biex jiġu pprovduti l-karatteristiċi mitluba).
2. **Żgurar tal-funzjonalità teknika:** L-użu tal-aċċess għall-internet għal komunikazzjoni sigura u affidabbli mas-servers ta' Chess.com u Lichess.org.  
   *Bażi Legali:* Artikolu 6(1)(f) tal-GDPR (interess leġittimu biex jiġi żgurat tħaddim xieraq u sigurtà).
3. **Ħażna lokali għal użu offline:** L-issejvjar ta' fajls PGN fuq it-tagħmir biex jippermetti aċċess għad-dejta mingħajr konnessjoni attiva tal-internet.  
   *Bażi Legali:* Artikolu 6(1)(b) tal-GDPR.

---

## 4. Servizzi ta' Partijiet Terzi
L-Applikazzjoni taġixxi bħala interface tal-klijent. Meta tuża l-funzjoni "Importa", it-tagħmir tiegħek jikkonnettja direttament ma':
* **Chess.com** (suġġett għall-Politika tal-Privatezza tagħhom)
* **Lichess.org** (suġġett għall-Politika tal-Privatezza tagħhom)

Aħna ma naġixxux bħala intermedjarju. Il-headers tat-talba tiegħek (inkluż il-User-Agent tal-Applikazzjoni) huma viżibbli għal dawn is-servizzi waqt il-konnessjoni.

---

## 5. Klawsoli Reġjonali tal-Privatezza u Drittijiet tal-Utenti

Minħabba li ma naħżnux id-dejta tiegħek fuq servers esterni, inti żżomm kontroll dirett fuq l-informazzjoni tiegħek irrispettivament minn fejn tgħix.

### 5.1. Żona Ekonomika Ewropea (ŻEE) u Renju Unit (UK)
Taħt il-GDPR u l-UK GDPR, għandek id-drittijiet li ġejjin:
* **Aċċess u Portabbiltà tad-Dejta:** Id-dejta kollha hija maħżuna direttament fuq it-tagħmir personali tiegħek.
* **Tħassir tad-Dejta:** Tista' tħassar id-dejta kollha fi kwalunkwe ħin billi tħassar il-cache/dejta tal-Applikazzjoni fis-settings tat-tagħmir jew billi tneħħi l-Applikazzjoni.
* **Dritt ta' Oġġezzjoni / Restrizzjoni:** Tista' twaqqaf l-ipproċessar fi kwalunkwe ħin billi tieqaf tuża l-Applikazzjoni jew tiddiżattiva l-funzjonijiet ta' importazzjoni.

### 5.2. Kalifornja / Stati Uniti (CCPA / CPRA)
* **L-Ebda Bejgħ jew Qsim ta' Dejta Personali:** Aħna ma nbigħux u ma naqsmux dejta personali u ma għamilniex dan fl-aħħar 12-il xahar.
* **Dejta Personali Sensittiva:** Aħna ma niġbrux u ma nipproċessawx dejta personali sensittiva li teħtieġ mekkaniżmi ta' opt-out.
* **Eżerċizzju tad-Drittijiet:** Ir-residenti ta' Kalifornja jistgħu jeżerċitaw id-drittijiet tagħhom billi jimmaniġġjaw il-ħażna lokali tat-tagħmir jew billi jikkuntattjawna. Bi tweġiba, aħna nikkonfermaw li ma nżommu l-ebda dejta personali barra mit-tagħmir tiegħek.

### 5.3. Brażil (LGPD)
Skont il-Lei Geral de Proteção de Dados (LGPD):
* **Bażijiet Legali:** L-ipproċessar għall-analiżi tal-logħob u l-ħażna lokali jsir abbażi tal-Artikolu 7(V) tal-LGPD (eżekuzzjoni tal-kuntratt). Konnessjonijiet tekniċi ma' APIs esterni jsiru abbażi tal-Artikolu 7(IX) tal-LGPD (interess leġittimu).
* **Drittijiet:** Tista' teżerċita d-drittijiet tiegħek għal konferma, aċċess jew tħassir direttament permezz tal-immaniġġjar tal-ħażna lokali fuq it-tagħmir tiegħek.

### 5.4. Indja (Att DPDP tal-2023)
Skont id-Digital Personal Data Protection Act 2023:
* **Drittijiet tas-Suġġett tad-Dejta:** Għandek id-dritt li titlob it-tħassir tad-dejta u tirtira l-kunsens tiegħek għall-ipproċessar.
* **Implimentazzjoni:** Peress li d-dejta kollha tinsab lokalment fuq it-tagħmir tiegħek, tista' teżerċita dawn id-drittijiet direttament billi tħassar id-dejta tal-Applikazzjoni jew tneħħiha.

### 5.5. Ġurisdizzjonijiet Oħra
Jekk tgħix f'ġurisdizzjoni oħra (eż. il-Kanada, l-Awstralja, l-Isvizzera, il-Ġappun jew Singapor), inti żżomm id-dritt sħiħ li taċċessa u tħassar id-dejta lokali tiegħek direttament fuq it-tagħmir tiegħek.

---

## 6. Trasferiment Internazzjonali ta' Dejta
Meta tuża l-funzjoni ta' importazzjoni, it-tagħmir tiegħek jikkonnettja direttament ma' servers ta' partijiet terzi:
* **Chess.com:** Is-servers jistgħu jkunu jinsabu fl-Istati Uniti. Il-konnessjoni ma' Chess.com tibgħat talbiet tan-netwerk standard (inkluż l-indirizz IP u l-username mitlub) direttament lil servers fl-Istati Uniti.
* **Lichess.org:** L-infrastruttura tinsab fit-territorju tal-Unjoni Ewropea (Franza/Ġermanja).

Jekk tuża l-Applikazzjoni minn barra l-Istati Uniti jew l-UE, il-bidu ta' importazzjoni jikkawża trażmissjoni transkonfinali diretta ta' dejta tal-konnessjoni lil dawn is-servers esterni. Aħna ma nikkontrollawx dawn it-trasferimenti – huma rregolati mill-Politika tal-Privatezza tas-servizz korrispondenti.

---

## 7. Analitika, Profiling u SDKs ta' Partijiet Terzi
* **L-Ebda SDKs ta' Traċċar:** L-Applikazzjoni ma tuża l-ebda SDK għall-analitika, reklamar jew rappurtar ta' ħsarat (bħal Google Analytics, Firebase jew AdMob).
* **L-Ebda Profiling jew Teħid ta' Deċiżjonijiet Awtomatizzat:** Aħna ma nipprofilawkx u ma nieħdux deċiżjonijiet awtomatizzati bbażati fuq dejta personali jew storja tal-logħob.
* **L-Ebda Telemetrija:** L-ebda dejta dwar l-interazzjonijiet tiegħek mal-Applikazzjoni ma tintbagħat lilna.

---

## 8. Sigurtà tad-Dejta
Minħabba n-natura lokali tal-ħażna tad-dejta, is-sigurtà tiddependi mill-protezzjoni tat-tagħmir tiegħek. Nirrakkomandaw:
* L-użu ta' passcode tat-tagħmir jew lock bijometriku.
* Iż-żamma tas-sistema operattiva aġġornata.
* L-evitar tal-użu tal-Applikazzjoni fuq tagħmir b'modifiki mhux awtorizzati ("rooted" jew "jailbroken").

---

## 9. Privatezza tat-Tfal
L-Applikazzjoni mhix immirata għal tfal taħt is-16-il sena (jew l-età minima meħtieġa mil-liġi lokali jekk tkun aktar baxxa – fl-ebda każ taħt it-13-il sena).

Aħna ma nħallux b'għarfien lil tfal taħt din l-età jużaw il-funzjonijiet ta' importazzjoni. L-użu ta' servizzi ta' partijiet terzi (Chess.com u Lichess.org) permezz tal-Applikazzjoni huwa suġġett għar-restrizzjonijiet tal-età tagħhom stess. Il-ġenituri jew il-kustodji li jemmnu li wild kiseb aċċess għal servizzi esterni għandhom jikkuntattjaw direttament lil Chess.com jew Lichess.org.

---

## 10. Liġi Applikabbli u Riżoluzzjoni ta' Tilwim
Din il-Politika tal-Privatezza u kwalunkwe tilwim li jirriżulta minnha huma rregolati u interpretati skont il-liġi Pollakka, bl-esklużjoni tar-regoli tal-kunflitt tal-liġijiet. Il-pretensjonijiet legali kollha jkunu esklussivament taħt il-ġurisdizzjoni tal-qrati kompetenti fil-Polonja.

---

## 11. Dritt li Tressaq Ilment (Utenti taż-ŻEE)
Jekk tinsab fiż-ŻEE u temmen li nkisru d-drittijiet tal-privatezza tiegħek, għandek id-dritt li tressaq ilment mal-awtorità lokali tal-protezzjoni tad-dejta tiegħek jew mal-awtorità superviżorja ewlenija tagħna:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varsavja, Il-Polonja  
Websajt: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Bidliet f'Din il-Politika
Nistgħu naġġornaw din il-Politika tal-Privatezza perjodikament biex nirriflettu bidliet fil-prattiki tagħna jew fir-rekwiżiti legali. Aħna ninnotifikawk bil-bidliet billi nippubblikaw il-verżjoni l-ġdida fl-Applikazzjoni jew fuq il-websajt uffiċjali tagħna u naġġornaw id-"Data tad-Dħul fis-Seħħ" fil-bidu.

F'każ ta' bidliet materjali fil-mod kif tiġi pproċessata d-dejta (eż. tluq mill-arkitettura local-first), aħna nipprovdu avviż aktar prominenti, eż. fil-forma ta' messaġġ fl-Applikazzjoni, qabel ma jidħlu fis-seħħ il-bidliet.

---

## 13. Kuntatt
Għal mistoqsijiet dwar il-privatezza jew biex teżerċita d-drittijiet tiegħek, jekk jogħġbok ikkuntattja lill-Kontrollur tad-Dejta:

**Email:** WorldiPL@protonmail.com  
*L-indirizz postali sħiħ u dejta ta' identifikazzjoni addizzjonali huma disponibbli fuq talba bil-miktub skont l-Artikolu 13 tal-GDPR.*
