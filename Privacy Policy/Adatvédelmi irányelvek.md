# Adatvédelmi irányelvek

**Hatálybalépés dátuma:** 07.08.2026  
**Adatkezelő:** Tomasz Rutkowski, Lengyelországban letelepedett természetes személy, aki a „Chess M8” alkalmazást független fejlesztőként üzemelteti.  
**Alkalmazás neve:** ChessM8  

---

## 1. Bevezetés
Tiszteletben tartjuk az Ön magánéletét. A jelen Adatvédelmi irányelvek elmagyarázzák, hogy a ChessM8 („az Alkalmazás”) hogyan gyűjti, használja és védi az információkat. Az Alkalmazás használatával Ön elfogadja a jelen dokumentumban rögzített feltételeket.

---

## 2. Adatgyűjtés és -feldolgozás (Local-First architektúra)
Az Alkalmazás a „Local-First” elv (a helyi feldolgozás elsőbbsége) alapján készült. Ez azt jelenti, hogy az Ön adatvédelmét helyezzük előtérbe azáltal, hogy adatait közvetlenül az Ön eszközén tároljuk.

### A. Személyes adatok
Az Alkalmazás nyilvános sakkjátszma-adatokat (PGN-fájlokat) tölt le harmadik fél szolgáltatásokból, amelyek a következőket tartalmazhatják:
* Felhasználónevek (pl. a Lichess.org vagy a Chess.com oldalról).
* Játszmalépések, időbélyegek és értékszámok.

Nem tárolunk személyes adatokat saját szervereinken; az Ön kérésére az adatok közvetlenül az Ön eszközéről kerülnek továbbításra a harmadik felek API-jaihoz.

### B. Műszaki adatok
* **IP-cím:** Amikor az Alkalmazás külső API-khoz csatlakozik, az Ön IP-címe látható ezen szolgáltatók (Chess.com/Lichess) számára, de azt soha nem továbbítják hozzánk, és mi nem tároljuk.

### C. Eszközengedélyek
A megfelelő működéshez az Alkalmazásnak szüksége van:
* **Internet-hozzáférés:** Kizárólag a Chess.com és a Lichess.org API-khoz való csatlakozáshoz.
* **Tárhely (Olvasás/Írás):** PGN-fájlok mentésére és betöltésére az Ön eszközén (adott esetben).

---

## 3. Az adatkezelés céljai és jogalapjai

### A. Az Európai Gazdasági Térség (EGT / GDPR) felhasználói
Amennyiben Ön az EGT területén tartózkodik, a személyes adatokat a következő célokból kezeljük:
1. **A szolgáltatás nyújtása és játszmaelemzés:** Sakkjátszmák letöltésének, elemzésének és a statisztikák Alkalmazáson belüli megjelenítésének biztosítása.  
   *Jogalap:* GDPR 6. cikk (1) bekezdés b) pont (szerződés teljesítése a kért funkciók biztosítása érdekében).
2. **Műszaki működés biztosítása:** Internet-hozzáférés használata a biztonságos és megbízható kommunikációhoz a Chess.com és a Lichess.org szervereivel.  
   *Jogalap:* GDPR 6. cikk (1) bekezdés f) pont (jogos érdek a megfelelő működés és biztonság szavatolására).
3. **Helyi tárhely offline használatra:** PGN-fájlok mentése az eszközre, hogy aktív internetkapcsolat nélkül is hozzáférhessen az adatokhoz.  
   *Jogalap:* GDPR 6. cikk (1) bekezdés b) pont.

---

## 4. Harmadik felek szolgáltatásai
Az Alkalmazás kliensfelületként működik. Az „Importálás” funkció használatakor az Ön eszköze közvetlenül csatlakozik:
* **Chess.com** (az ő Adatvédelmi irányelveiknek megfelelően)
* **Lichess.org** (az ő Adatvédelmi irányelveiknek megfelelően)

Nem működünk közreműködőként ebben az adatcserében. Az Ön kérésfejlécei (beleértve az Alkalmazás User-Agent-jét) láthatók ezen szolgáltatások számára a kapcsolat fennállása alatt.

---

## 5. Regionális adatvédelmi rendelkezések és felhasználói jogok

Mivel az Ön adatait nem tároljuk külső szervereken, Ön közvetlenül ellenőrzése alatt tartja az adatait, függetlenül attól, hogy hol él.

### 5.1. Európai Gazdasági Térség (EGT) és Egyesült Királyság (UK)
A GDPR és a UK GDPR értelmében Önt a következő jogok illetik meg:
* **Hozzáférés és adathordozhatóság:** Minden adat közvetlenül az Ön személyes eszközén tárolódik.
* **Adattörlés:** Bármikor törölheti az összes adatot az Alkalmazás gyorsítótárának/adatainak törlésével az eszköz beállításaiban, vagy az Alkalmazás eltávolításával.
* **Tiltakozáshoz való jog / Korlátozás:** Az adatkezelést bármikor leállíthatja az Alkalmazás használatának befejezésével vagy az importálási funkciók kikapcsolásával.

### 5.2. Kalifornia / Egyesült Államok (CCPA / CPRA)
* **Személyes adatok értékesítésének vagy megosztásának tilalma:** Nem adunk el és nem osztunk meg személyes adatokat, és nem tettünk ilyet az elmúlt 12 hónapban sem.
* **Érzékeny személyes adatok:** Nem gyűjtünk és nem kezelünk olyan érzékeny személyes adatokat, amelyek leiratkozási (opt-out) mechanizmust igényelnének.
* **Jogok gyakorlása:** Kalifornia lakosai az eszköz helyi tárhelyének kezelésével vagy velünk való kapcsolatfelvétel útján gyakorolhatják jogaikat. Válaszul megerősítjük, hogy az Ön eszközén kívül nem tárolunk semmilyen személyes adatot.

### 5.3. Brazília (LGPD)
A Lei Geral de Proteção de Dados (LGPD) alapján:
* **Jogalapok:** A játszmaelemzés és a helyi tárolás céljából történő adatkezelés az LGPD 7(V) cikke (szerződés teljesítése) alapján történik. A külső API-khoz való technikai csatlakozások az LGPD 7(IX) cikke (jogos érdek) alapján valósulnak meg.
* **Jogok:** Az adatkezelés megerősítésére, a hozzáférésre vagy a törlésre vonatkozó jogait közvetlenül az eszközén lévő helyi tárhely kezelésével gyakorolhatja.

### 5.4. India (2023. évi DPDP-törvény)
A Digital Personal Data Protection Act 2023 alapján:
* **Az érintett jogai:** Önnek joga van kérni az adatok törlését és visszavonni a kezeléshez adott hozzájárulását.
* **Gyakorlás:** Mivel minden adat helyben található az eszközén, ezeket a jogokat közvetlenül az Alkalmazás adatainak törlésével vagy az Alkalmazás eltávolításával gyakorolhatja.

### 5.5. Egyéb joghatóságok
Amennyiben Ön más joghatóság alatt él (pl. Kanada, Ausztrália, Svájc, Japán vagy Szingapúr), teljes körű joga van a helyi adataihoz való hozzáféréshez és azok törléséhez közvetlenül az eszközén.

---

## 6. Nemzetközi adattovábbítás
Az importálási funkció használatakor az Ön eszköze közvetlenül harmadik felek szervereihez csatlakozik:
* **Chess.com:** A szerverek az Egyesült Államokban találhatók. A Chess.com-hoz való csatlakozás szabványos hálózati kéréseket (beleértve az IP-címet és a kért felhasználónevet) küld közvetlenül az USA-beli szerverekre.
* **Lichess.org:** Az infrastruktúra az Európai Unió területén található (Franciaország/Németország).

Ha az Alkalmazást az Egyesült Államokon vagy az EU-n kívülről használja, az importálás elindítása a kapcsolati adatok közvetlen határokon átnyúló továbbítását eredményezi ezen külső szerverek felé. Ezeket a továbbításokat nem mi ellenőrizzük – azokra a megfelelő szolgáltatás Adatvédelmi irányelvei vonatkoznak.

---

## 7. Analitika, profilalkotás és harmadik féltől származó SDK-k
* **Nincsenek követő SDK-k:** Az Alkalmazás nem használ semmilyen analitikai, hirdetési vagy összeomlás-jelentési SDK-t (mint a Google Analytics, Firebase vagy AdMob).
* **Nincs profilalkotás vagy automatizált döntéshozatal:** Nem készítünk profilt Önről, és nem hozunk automatizált döntéseket személyes adatok vagy játékelőzmények alapján.
* **Nincs telemetria:** Semmilyen adatot nem küldünk el nekünk az Alkalmazással való interakcióiról.

---

## 8. Adatbiztonság
Az adattárolás helyi jellege miatt a biztonság az Ön eszközének védelmétől függ. Javasoljuk:
* Eszköz-PIN-kód vagy biometrikus zár használatát.
* Az operációs rendszer naprakészen tartását.
* Az Alkalmazás használatának elkerülését jogosulatlanul módosított operációs rendszerű („rootolt” vagy „jailbreakelt”) eszközökön.

---

## 9. Gyermekek adatvédelme
Az Alkalmazás nem 16 év alatti gyermekeknek szól (vagy a helyi jogszabályok által megkövetelt minimális életkor alattiaknak, ha az alacsonyabb – semmiképpen sem 13 év alattiaknak).

Tudatosan nem engedélyezzük az ezen életkor alatti gyermekek számára az importálási funkciók használatát. A harmadik fél szolgáltatások (Chess.com és Lichess.org) Alkalmazáson keresztüli használatára saját életkori korlátozásaik vonatkoznak. Azok a szülők vagy gondviselők, akik úgy vélik, hogy gyermekük külső szolgáltatásokhoz fért hozzá, forduljanak közvetlenül a Chess.com-hoz vagy a Lichess.org-hoz.

---

## 10. Irányadó jog és vitarendezés
A jelen Adatvédelmi irányelvekre és az abból eredő vagy azzal kapcsolatos bármely vitára a lengyel jog az irányadó, és annak megfelelően kell értelmezni, a kollíziós szabályok kizárásával. Minden jogi követelés kizárólag a lengyelországi illetékes bíróságok elé terjeszthető.

---

## 11. Panasztételhez való jog (EGT-felhasználók)
Ha Ön az EGT területén tartózkodik, és úgy ítéli meg, hogy adatvédelmi jogait megsértették, jogosult panaszt tenni a helyi adatvédelmi hatóságnál vagy a vezető felügyeleti hatóságunknál:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varsó, Lengyelország  
Weboldal: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. A jelen irányelvek módosítása
Időről időre frissíthetjük a jelen Adatvédelmi irányelveket, hogy tükrözzék az eljárásainkban vagy a jogszabályi követelményekben bekövetkezett változásokat. A változásokról az új verzió Alkalmazásban vagy hivatalos weboldalunkon történő közzétételével, valamint a dokumentum tetején található „Hatálybalépés dátuma” frissítésével értesítjük Önt.

Az adatkezelési gyakorlatunk lényeges módosítása esetén (pl. a helyi architektúra elhagyása esetén) a változások hatálybalépése előtt figyelemfelkeltőbb értesítést adunk, például az Alkalmazáson belüli üzenet formájában.

---

## 13. Kapcsolat
Adatvédelemmel kapcsolatos kérdésekben vagy jogai gyakorlása érdekében kérjük, forduljon az Adatkezelőhöz:

**E-mail:** WorldiPL@protonmail.com  
*A teljes postai cím és a további azonosító adatok a GDPR 13. cikkének megfelelően írásbeli kérésre elérhetők.*
