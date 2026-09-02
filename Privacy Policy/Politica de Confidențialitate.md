# Politica de Confidențialitate

**Data intrării în vigoare:** 07.08.2026  
**Operatorul de Date:** Tomasz Rutkowski, persoană fizică cu sediul în Polonia, care operează aplicația „Chess M8” în calitate de dezvoltator independent.  
**Numele Aplicației:** ChessM8  

---

## 1. Introducere
Vă respectăm confidențialitatea. Această Politică de Confidențialitate explică modul în care ChessM8 („Aplicația”) colectează, utilizează și protejează informațiile. Prin utilizarea Aplicației, sunteți de acord cu termenii stabiliți în acest document.

---

## 2. Colectarea și Prelucrarea Datelor (Arhitectură Local-First)
Aplicația este concepută pe baza principiului „Local-First” (prioritate pentru prelucrarea locală). Aceasta înseamnă că punem confidențialitatea dumneavoastră pe primul loc, stocând datele direct pe dispozitivul dumneavoastră.

### A. Date cu Caracter Personal
Aplicația preia date publice privind partidele de șah (fișiere PGN) de la servicii terțe, care pot include:
* Nume de utilizator (de exemplu, de pe Lichess.org sau Chess.com).
* Mutările din partide, marcajele temporale și ratingurile/scorurile.

Nu stocăm date cu caracter personal pe serverele noastre; la cererea dumneavoastră, datele sunt transmise direct de pe dispozitiv către API-urile terților.

### B. Date Tehnice
* **Adresa IP:** Când Aplicația se conectează la API-uri externe, adresa dumneavoastră IP este vizibilă pentru acești furnizori (Chess.com/Lichess), dar nu este trimisă niciodată către noi și nici stocată de noi.

### C. Permisiuni ale Dispozitivului
Pentru o funcționare corectă, Aplicația necesită:
* **Acces la Internet:** Exclusiv pentru conectarea la API-urile Chess.com și Lichess.org.
* **Stocare (Citire/Scriere):** Pentru a salva și a citi fișierele PGN pe dispozitivul dumneavoastră (unde este cazul).

---

## 3. Scopurile și Temeiurile Juridice ale Prelucrării

### A. Utilizatori din Spațiul Economic European (SEE / GDPR)
Dacă vă aflați în SEE, prelucrăm datele cu caracter personal în următoarele scopuri:
1. **Furnizarea serviciului și analiza partidelor:** Pentru a vă permite descărcarea partidelor de șah, analiza acestora și afișarea statisticilor în Aplicație.  
   *Temei juridic:* Art. 6 alin. (1) lit. (b) GDPR (executarea unui contract pentru furnizarea funcționalităților solicitate).
2. **Asigurarea funcționalității tehnice:** Utilizarea accesului la Internet pentru o comunicare sigură și fiabilă cu serverele Chess.com și Lichess.org.  
   *Temei juridic:* Art. 6 alin. (1) lit. (f) GDPR (interes legitim de a asigura funcționarea corespunzătoare și securitatea).
3. **Stocare locală pentru utilizare offline:** Salvarea fișierelor PGN pe dispozitiv pentru a permite accesul la date fără o conexiune activă la Internet.  
   *Temei juridic:* Art. 6 alin. (1) lit. (b) GDPR.

---

## 4. Servicii Terțe
Aplicația funcționează ca o interfață client. Când utilizați funcția „Import”, dispozitivul dumneavoastră se conectează direct la:
* **Chess.com** (conform Politicii lor de Confidențialitate)
* **Lichess.org** (conform Politicii lor de Confidențialitate)

Nu acționăm ca intermediari. Anteturile solicitărilor dumneavoastră (inclusiv User-Agent-ul Aplicației) sunt vizibile pentru aceste servicii pe durata conexiunii.

---

## 5. Clauze Regionale de Confidențialitate și Drepturile Utilizatorilor

Deoarece nu stocăm datele dumneavoastră pe servere externe, mențineți controlul direct asupra informațiilor dumneavoastră, indiferent de locul în care locuiți.

### 5.1. Spațiul Economic European (SEE) și Regatul Unit (UK)
În conformitate cu GDPR și UK GDPR, beneficiați de următoarele drepturi:
* **Accesul și Portabilitatea Datelor:** Toate datele sunt stocate direct pe dispozitivul dumneavoastră personal.
* **Ștergerea Datelor:** Puteți șterge toate datele în orice moment prin golirea memoriei cache/datelor Aplicației din setările dispozitivului sau prin dezinstalarea Aplicației.
* **Dreptul de Opoziție / Restricționare:** Puteți opri prelucrarea în orice moment prin încetarea utilizării Aplicației sau dezactivarea funcțiilor de import.

### 5.2. California / Statele Unite ale Americii (CCPA / CPRA)
* **Fără Vânzare sau Partajare a Datelor Personale:** Nu vindem și nu partajăm date cu caracter personal și nu am făcut acest lucru în ultimele 12 luni.
* **Date Personale Sensibile:** Nu colectăm și nu prelucrăm date personale sensibile care să necesite mecanisme de renunțare (opt-out).
* **Exercitarea Drepturilor:** Rezidenții din California își pot exercita drepturile prin gestionarea memoriei locale a dispozitivului sau contactându-ne. Ca răspuns, vom confirma că nu păstrăm date personale în afara dispozitivului dumneavoastră.

### 5.3. Brazilia (LGPD)
Conform Lei Geral de Proteção de Dados (LGPD):
* **Temeiuri Juridice:** Prelucrarea pentru analiza partidelor și stocarea locală se bazează pe Art. 7(V) LGPD (executarea contractului). Conexiunile tehnice la API-uri externe se bazează pe Art. 7(IX) LGPD (interes legitim).
* **Drepturi:** Vă puteți exercita drepturile de confirmare, acces sau ștergere direct prin gestionarea stocării locale de pe dispozitiv.

### 5.4. India (Legea DPDP din 2023)
Conform Digital Personal Data Protection Act 2023:
* **Drepturile Persoanei Vizate:** Aveți dreptul de a solicita ștergerea datelor și de a vă retrage consimțământul pentru prelucrare.
* **Exercitare:** Deoarece toate datele se află local pe dispozitivul dumneavoastră, vă puteți exercita aceste drepturi direct prin ștergerea datelor Aplicației sau prin dezinstalarea acesteia.

### 5.5. Alte Jurisdicții
Dacă locuiți într-o altă jurisdicție (de exemplu, Canada, Australia, Elveția, Japonia sau Singapore), vă păstrați dreptul deplin de a accesa și șterge datele locale direct pe dispozitivul dumneavoastră.

---

## 6. Transferul Internațional de Date
La utilizarea funcției de import, dispozitivul dumneavoastră se conectează direct la servere terțe:
* **Chess.com:** Serverele pot fi situate în Statele Unite. Conectarea la Chess.com trimite solicitări standard de rețea (inclusiv adresa IP și numele de utilizator solicitat) direct către serverele din SUA.
* **Lichess.org:** Infrastructura se află pe teritoriul Uniunii Europene (Franța/Germania).

În cazul utilizării Aplicației din afara SUA sau a UE, inițierea unui import va genera o transmitere directă transfrontalieră a datelor de conectare către aceste servere externe. Nu controlăm aceste transferuri – ele sunt guvernate de Politica de Confidențialitate a serviciului respectiv.

---

## 7. Analiză, Profilare și Pachete SDK Terțe
* **Fără SDK-uri de Urmărire:** Aplicația nu utilizează pachete SDK pentru analiză, publicitate sau raportare a erorilor (cum ar fi Google Analytics, Firebase sau AdMob).
* **Fără Profilare sau Decizii Automatizate:** Nu realizăm profilări și nu luăm decizii automatizate pe baza datelor dumneavoastră personale sau a istoricului jocurilor.
* **Fără Telemetrie:** Nu ni se transmite niciun fel de date cu privire la interacțiunea dumneavoastră cu Aplicația.

---

## 8. Securitatea Datelor
Având în vedere natura locală a stocării datelor, securitatea acestora depinde de protecția dispozitivului dumneavoastră. Vă recomandăm:
* Utilizarea unui cod de acces sau a unei blocări biometrice pe dispozitiv.
* Păstrarea sistemului de operare actualizat la zi.
* Evitarea utilizării Aplicației pe dispozitive cu modificări neautorizate de firmware („root”, „jailbreak”).

---

## 9. Confidențialitatea Minorilor
Aplicația nu se adresează copiilor cu vârsta sub 16 ani (sau vârsta minimă cerută de legea locală, dacă este mai mică – în niciun caz sub 13 ani).

Nu permitem în mod conștient copiilor sub această vârstă să utilizeze funcțiile de import. Utilizarea serviciilor terțe (Chess.com și Lichess.org) prin intermediul Aplicației este supusă propriilor restricții de vârstă. Părinții sau tutorii care consideră că un minor a accesat servicii externe ar trebui să contacteze direct Chess.com sau Lichess.org.

---

## 10. Legea Aplicabilă și Soluționarea Litigiilor
Prezenta Politică de Confidențialitate și orice dispute care decurg din sau sunt legate de aceasta sunt guvernate și interpretate în conformitate cu legea poloneză, excluzând normele conflictuale. Orice pretenții legale vor fi soluționate exclusiv de instanțele competente din Polonia.

---

## 11. Dreptul de a Depune o Plângere (Utilizatori din SEE)
Dacă vă aflați în SEE și considerați că v-au fost încălcate drepturile la confidențialitate, aveți dreptul de a depune o plângere la autoritatea națională de protecție a datelor sau la autoritatea noastră principală de supraveghere:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varșovia, Polonia  
Site web: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Modificări ale Prezentei Politici
Putem actualiza periodic această Politică de Confidențialitate pentru a reflecta modificările din procedurile noastre sau din cerințele legale. Vă vom informa despre modificări prin publicarea noii versiuni în Aplicație sau pe site-ul nostru oficial și prin actualizarea „Datei intrării în vigoare” din partea superioară.

În cazul unor modificări substanțiale privind prelucrarea datelor (de exemplu, abandonarea arhitecturii local-first), vom furniza o notificare mai vizibilă, de exemplu sub forma unui mesaj în Aplicație, înainte ca modificările să intre în vigoare.

---

## 13. Contact
Pentru întrebări legate de confidențialitate sau pentru exercitarea drepturilor dumneavoastră, vă rugăm să contactați Operatorul de Date:

**E-mail:** WorldiPL@protonmail.com  
*Adresa poștală completă și datele suplimentare de identificare sunt disponibile la cerere scrisă, în conformitate cu Art. 13 GDPR.*
