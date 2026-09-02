# Directivas davart la protecziun da datas

**Data d'entrada en vigur:** 07.08.2026  
**Responsabel per las datas:** Tomasz Rutkowski, ina persuna fizica cun domicil en Pologna, che gestiunescha l'applicaziun «Chess M8» sco sviluppader independent.  
**Num da l'Applicaziun:** ChessM8  

---

## 1. Introducziun
Nus respectain Tia sfera privata. Questas Directivas davart la protecziun da datas decleran co che ChessM8 («l'Applicaziun») rimna, utilisescha e protegia las infurmaziuns. Cun duvrar l'Applicaziun acceptas Ti las cundiziuns formuladas en quest document.

---

## 2. Rimnada ed elavuraziun da datas (Architectura Local-First)
L'Applicaziun è concepida tenor il princip «Local-First» (prioritad a l'elavuraziun locala). Quai vul dir che nus mettain Tia sfera privata en l'emprim plan cun memorisar Tias datas directamain sin Tes agen apparat.

### A. Datas persunalas
L'Applicaziun telechargia datas publicas da partidas da schah (datotecas PGN) da servetschs da terzs, las qualas pon cuntegnair:
* Nums d'utilisaders (p.ex. da Lichess.org u Chess.com).
* Midadas da partida, timestamps e classificaziuns (ratings).

Nus na memorisain naginas datas persunalas sin noss agens servers; sin Tia dumonda vegnan las datas transmessas directamain da Tes apparat a las APIs da terzs.

### B. Datas tecnicas
* **Adressa IP:** Cura che l'Applicaziun sa collia cun APIs externas, è Tia adressa IP visibla per quests purschiders (Chess.com/Lichess), ma ella na vegn mai transmessa a nus e mai memorisada da nus.

### C. Permissiuns d'apparat
Per funcziunar a moda correcta dovra l'Applicaziun:
* **Access a l'internet:** Exclusivamain per sa colliar cun las APIs da Chess.com e Lichess.org.
* **Memoria (Leger/Scriver):** Per memorisar e chargiar datotecas PGN sin Tes apparat (sche applicabel).

---

## 3. Intents e basas legalas da l'elavuraziun

### A. Utilisaders en il Spazi Economic Europeic (SEE / DSGVO)
Sche Ti Te chattas en il SEE, elavurain nus datas persunalas per ils suandants intents:
1. **Porscher il servetsch ed analisar partidas:** Per pussibilitar da telechargiar partidas da schah, las analisar e vesair statisticas en l'Applicaziun.  
   *Basa legala:* Artitgel 6(1)(b) DSGVO (adempliment d'in contract per porscher las funcziunalitads dumandadas).
2. **Garantir la funcziunalitad tecnica:** Utilisaziun da l'access a l'internet per ina communicaziun segira e fidada cun ils servers da Chess.com e Lichess.org.  
   *Basa legala:* Artitgel 6(1)(f) DSGVO (interess legitim da garantir in funcziunament correct e la segirtad).
3. **Memorisaziun locala per utilisaziun offline:** Memorisaziun da datotecas PGN sin l'apparat per pussibilitar l'access a datas senza connex d'internet activ.  
   *Basa legala:* Artitgel 6(1)(b) DSGVO.

---

## 4. Servetschs da terzs
L'Applicaziun funcziunescha sco interfatscha da client. Cura che Ti utiliseschas la funcziun «Importar», sa collia Tes apparat directamain cun:
* **Chess.com** (sut lur Directivas davart la protecziun da datas)
* **Lichess.org** (sut lur Directivas davart la protecziun da datas)

Nus n'agischain betg sco intermediar. Ils headers da Tias dumondas (inclusiv il User-Agent da l'Applicaziun) èn visibels per quests servetschs durant la connexiun.

---

## 5. Disposiziuns da protecziun da datas regiunalas e dretgs dals utilisaders

Pervi da la nun-memorisaziun da Tias datas sin servers externs mantegnas Ti il control direct davart Tias infurmaziuns independentamain da Tes lieu da domicil.

### 5.1. Spazi Economic Europeic (SEE) e Reginavel Unì (UK)
Tenor la DSGVO e l'UK GDPR has Ti ils suandants dretgs:
* **Access a datas e portabilitad:** Tut las datas vegnan memorisadas directamain sin Tes apparat persunal.
* **Stizzar datas:** Ti pos stizzar tut las datas en mintga mument cun rumir la memoria redundanta (cache)/datas da l'Applicaziun en ils parameters da l'apparat u cun deinstallar l'Applicaziun.
* **Dretg d'opposiziun / Limitaziun:** Ti pos terminar l'elavuraziun da tut temp cun chalar da duvrar l'Applicaziun u deactivar las funcziuns d'import.

### 5.2. California / Stadis Unids da l'America (CCPA / CPRA)
* **Nagina vendita u transmissiun da datas persunalas:** Nus na vendain e na cundividain naginas datas persunalas e n'avain betg fatg quai en ils ultims 12 mais.
* **Datas persunalas sensiblas:** Nus na rimnain e n'elavurain naginas datas persunalas sensiblas che pretendan mecanissems d'opt-out.
* **Exersizi dals dretgs:** Abitants da la California pon far valair lur dretgs cun administrar la memoria locala da l'apparat u cun ans contactar. Sco resposta confermain nus che nus na tegnain naginas datas persunalas ordaifer Tes apparat.

### 5.3. Brasilia (LGPD)
Tenor la Lei Geral de Proteção de Dados (LGPD):
* **Basas legalas:** L'elavuraziun per l'analisa da gieus e la memorisaziun locala sa basa sin l'Artitgel 7(V) LGPD (adempliment dal contract). Connexiuns tecnicas ad APIs externas succedan tenor l'Artitgel 7(IX) LGPD (interess legitim).
* **Dretgs:** Ti pos exequir Tes dretgs da confermaziun, access u stizzament directamain tras l'administraziun da la memoria locala sin Tes apparat.

### 5.4. India (Lescha DPDP dal 2023)
Tenor il Digital Personal Data Protection Act 2023:
* **Dretgs da la persuna pertutgada:** Ti has il dretg da pretender il stizzament da datas e revocar Tes consentiment tar l'elavuraziun.
* **Realisaziun:** Cunquai che tut las datas sa chattan localmain sin Tes apparat, pos Ti exequir quests dretgs directamain cun stizzar las datas da l'Applicaziun u cun deinstallar ella.

### 5.5. Autras giurisdicziuns
Sche Ti stas en in'autra giurisdicziun (p.ex. Canada, Australia, Svizra, Giapun u Singapur), mantegnas Ti il dretg cumplet d'access e da stizzament da Tias datas localas directamain sin Tes apparat.

---

## 6. Transmissiun da datas internaziunala
Cura che la funcziun d'import vegn utilisada, sa collia Tes apparat directamain cun servers da terzs:
* **Chess.com:** Ils servers pon sa chattar en ils Stadis Unids. Ina connexiun cun Chess.com trametta dumondas da rait usitadas (inclusiv l'adressa IP ed il num d'utilisader dumandà) directamain als servers en ils USA.
* **Lichess.org:** L'infrastructura sa chatta en l'Uniun Europeica (Frantscha/Germania).

Sche Ti utiliseschas l'Applicaziun ordaifer ils USA u l'UE, provochescha l'iniziaziun d'in import ina transmissiun transfrontaliera directa da datas da connexiun a quests servers externs. Nus na controllain betg questas transmissiuns – ellas suttastattan a las directivas da protecziun da datas dal servetsch correspundent.

---

## 7. Analitica, profiling e SDKs da terzs
* **Nagins SDKs da tracking:** L'Applicaziun na dovra nagins SDKs per analitica, reclama u rapports d'interrupziun (sco Google Analytics, Firebase u AdMob).
* **Nagin profiling u decisiuns automatisadas:** Nus na profilain betg Tias datas e na prendain naginas decisiuns automatisadas a basa da datas persunalas u da l'istorgia da gieu.
* **Nagina telemetria:** Naginas datas davart Tias interacziuns cun l'Applicaziun vegnan tramessas a nus.

---

## 8. Segirtad da las datas
Pervia da la natira locala da la memorisaziun dependa la segirtad da la protecziun da Tes apparat. Nus recumandain:
* Da duvrar in code d'access u ina serradira biometrica sin l'apparat.
* Da tegnair il sistem operativ actualisà.
* D'evitar l'utilisaziun da l'Applicaziun sin apparats cun modificaziuns nunautorisadas («rooted» u «jailbroken»).

---

## 9. Protecziun da datas d'uffants
L'Applicaziun na s'adressa betg ad uffants sut 16 onns (u a la vegliadetgna minimala tenor il dretg local sch'ella è pli bassa – en nagin cas sut 13 onns).

Nus na permettain conscientamain betg ad uffants sut questa vegliadetgna da duvrar las funcziuns d'import. L'utilisaziun da servetschs da terzs (Chess.com e Lichess.org) tras l'Applicaziun suttasta a lur atgnas restricziuns da vegliadetgna. Geniturs u represchentants legals che crajan ch'in uffant haja survegnì access a servetschs externs duessan contactar directamain Chess.com u Lichess.org.

---

## 10. Dretg applicabel e resoluziun da dispitas
Questas Directivas davart la protecziun da datas e tut las dispitas che resultan da quellas stattan sut e vegnan interpretadas tenor il dretg polac, cun exclusiun da las normas da collisiun da leschas. Tut las pretensiuns legalas suttastattan exclusivamain a la giurisdicziun dals tribunals cumpetents en Pologna.

---

## 11. Dretg da recurs (Utilisaders SEE)
Sche Ti Te chattas en il SEE e crajas che Tes dretgs da protecziun da datas sajan vegnids violads, has Ti il dretg da far recurs tar l'autoritad da protecziun da datas locala u tar nossa autoritad da surveglianza principala:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Warschau, Pologna  
Website: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Midadas da questas directivas
Nus pudain actualisar questas Directivas davart la protecziun da datas periodicamain per resguardar midadas en nossas practicas u prescripziuns legalas. Nus T'infurmain davart midadas cun publicar la nova versiun en l'Applicaziun u sin nossa website uffiziala e cun actualisar la «Data d'entrada en vigur» a l'entschatta.

En cas da midadas materialas dal biais d'elavuraziun da datas (p.ex. bandun da l'architectura local-first), dain nus in avis pli visibel, p.ex. en furma d'in messadi en l'Applicaziun, avant che las midadas entrian en vigur.

---

## 13. Contact
Per dumondas davart la protecziun da datas u per exequir Tes dretgs, stausch contactar il Responsabel per las datas:

**E-mail:** WorldiPL@protonmail.com  
*L'adressa postala cumpletta ed ulteriuras datas d'identificaziun èn disponiblas sin dumonda en scrit confurm a l'Artitgel 13 DSGVO.*
