# Zásady ochrany osobních údajů

**Datum účinnosti:** 07.08.2026  
**Správce údajů:** Tomasz Rutkowski, fyzická osoba se sídlem v Polsku, provozující aplikaci „Chess M8“ jako nezávislý vývojář.  
**Název aplikace:** ChessM8  

---

## 1. Úvod
Respektujeme vaše soukromí. Tyto Zásady ochrany osobních údajů vysvětlují, jak aplikace ChessM8 (dále jen „Aplikace“) shromažďuje, používá a chrání informace. Používáním Aplikace vyjadřujete souhlas s podmínkami uvedenými v tomto dokumentu.

---

## 2. Shromažďování a zpracování údajů (Architektura Local-First)
Aplikace je navržena na základě principu „Local-First“ (přednost lokálního zpracování). To znamená, že klademe vaše soukromí na první místo a uchováváme vaše data přímo ve vašem zařízení.

### A. Osobní údaje
Aplikace stahuje veřejná data šachových partií (soubory PGN) ze služeb třetích stran, která mohou zahrnovat:
* Uživatelská jména (např. ze služeb Lichess.org nebo Chess.com).
* Tahy v partiích, časové značky a hodnocení (ratingy).

Neukládáme osobní údaje na vlastních serverech; na vaši žádost jsou data přenášena přímo z vašeho zařízení do rozhraní API třetích stran.

### B. Technické údaje
* **IP adresa:** Při připojování Aplikace k externím rozhraním API je vaše IP adresa viditelná pro tyto poskytovatele (Chess.com/Lichess), nikdy však není odesílána k nám ani námi ukládána.

### C. Oprávnění zařízení
Pro správné fungování Aplikace vyžaduje:
* **Přístup k internetu:** Výhradně za účelem připojení k rozhraním API služeb Chess.com a Lichess.org.
* **Úložiště (Čtení/Zápis):** Pro ukládání a načítání souborů PGN ve vašem zařízení (v příslušných případech).

---

## 3. Účely a právní základy zpracování

### A. Uživatelé z Evropského hospodářského prostoru (EHP / GDPR)
Pokud se nacházíte v EHP, zpracováváme osobní údaje pro následující účely:
1. **Poskytování služby a analýza partií:** Umožnění stahování šachových partií, jejich analýzy a zobrazování statistik v Aplikaci.  
   *Právní základ:* Čl. 6 odst. 1 písm. b) GDPR (plnění smlouvy za účelem poskytování požadovaných funkcí).
2. **Zajištění technické funkčnosti:** Využití přístupu k internetu pro bezpečnou a spolehlivou komunikaci se servery Chess.com a Lichess.org.  
   *Právní základ:* Čl. 6 odst. 1 písm. f) GDPR (oprávněný zájem spočívající v zajištění řádného fungování a bezpečnosti).
3. **Místní úložiště pro použití offline:** Ukládání souborů PGN do zařízení pro přístup k datům bez aktivního internetového připojení.  
   *Právní základ:* Čl. 6 odst. 1 písm. b) GDPR.

---

## 4. Služby třetích stran
Aplikace funguje jako klientské rozhraní. Při použití funkce „Importovat“ se vaše zařízení připojuje přímo k:
* **Chess.com** (v souladu s jejich Zásadami ochrany osobních údajů)
* **Lichess.org** (v souladu s jejich Zásadami ochrany osobních údajů)

Tuto výměnu nezprostředkováváme. Hlavičky vašich požadavků (včetně User-Agent Aplikace) jsou během trvání spojení viditelné pro tyto služby.

---

## 5. Regionální ustanovení o ochraně soukromí a práva uživatelů

Protože vaše data neukládáme na externích serverech, máte přímou kontrolu nad svými informacemi bez ohledu na to, kde žijete.

### 5.1. Evropský hospodářský prostor (EHP) a Spojené království (UK)
Podle GDPR a UK GDPR máte následující práva:
* **Přístup k údajům a přenositelnost:** Všechna data jsou uložena přímo ve vašem osobním zařízení.
* **Výmaz údajů:** Všechna data můžete kdykoli smazat vymazáním mezipaměti/dat Aplikace v nastavení zařízení nebo odinstalováním Aplikace.
* **Právo vznést námitku / Omezení zpracování:** Zpracování můžete kdykoli ukončit ukončením používání Aplikace nebo vypnutím funkcí importu.

### 5.2. Kalifornie / Spojené státy americké (CCPA / CPRA)
* **Žádný prodej ani sdílení osobních údajů:** Osobní údaje neprodáváme ani nesdílíme a nečinili jsme tak ani v uplynulých 12 měsících.
* **Citlivé osobní údaje:** Neshromažďujeme ani nezpracováváme citlivé osobní údaje vyžadující mechanismy odhlášení (opt-out).
* **Uplatnění práv:** Obyvatelé Kalifornie mohou svá práva uplatnit správou místního úložiště zařízení nebo tím, že nás kontaktují. V odpovědi potvrdíme, že mimo vaše zařízení neuchováváme žádné osobní údaje.

### 5.3. Brazílie (LGPD)
Podle Lei Geral de Proteção de Dados (LGPD):
* **Právní základy:** Zpracování za účelem analýzy her a lokálního ukládání probíhá na základě čl. 7(V) LGPD (plnění smlouvy). Technická spojení s externími API jsou realizována na základě čl. 7(IX) LGPD (oprávněný zájem).
* **Práva:** Svá práva na potvrzení zpracování, přístup nebo výmaz můžete uplatnit přímo správou místního úložiště ve svém zařízení.

### 5.4. Indie (Zákon DPDP z roku 2023)
Podle Digital Personal Data Protection Act 2023:
* **Práva subjektu údajů:** Máte právo požadovat výmaz údajů a odvolat souhlas s jejich zpracováním.
* **Realizace:** Vzhledem k tomu, že se všechna data nacházejí lokálně ve vašem zařízení, můžete tato práva uplatnit přímo vymazáním dat Aplikace nebo jejím odinstalováním.

### 5.5. Ostatní jurisdikce
Pokud žijete v jiné jurisdikci (např. Kanada, Austrálie, Švýcarsko, Japonsko nebo Singapur), zachováváte si plné právo na přístup ke svým lokálním datům a jejich výmaz přímo ve svém zařízení.

---

## 6. Mezinárodní předávání údajů
Při použití funkce importu se vaše zařízení připojuje přímo k serverům třetích stran:
* **Chess.com:** Servery se mohou nacházet v USA. Připojení k Chess.com odesílá standardní síťové požadavky (včetně IP adresy a požadovaného uživatelského jména) přímo na servery v USA.
* **Lichess.org:** Infrastruktura se nachází na území Evropské unie (Francie/Německo).

V případě používání Aplikace mimo USA nebo EU způsobí spuštění importu přímý přeshraniční přenos dat připojení k těmto externím serverům. Tyto přenosy nekontrolujeme – řídí se Zásadami ochrany osobních údajů příslušné služby.

---

## 7. Analytika, profilování a externí sady SDK
* **Žádné sledovací SDK:** Aplikace nepoužívá žádné SDK pro analýzu, reklamu ani hlášení chyb (např. Google Analytics, Firebase nebo AdMob).
* **Žádné profilování ani automatizované rozhodování:** Neprofilujeme vás ani neprovádíme automatizovaná rozhodnutí na základě osobních údajů nebo herní historie.
* **Žádná telemetrie:** Žádná data o interakci s Aplikací nám nejsou zasílána.

---

## 8. Zabezpečení údajů
Vzhledem k lokální povaze ukládání dat závisí jejich bezpečnost na zabezpečení vašeho zařízení. Doporučujeme:
* Používat přístupový kód zařízení nebo biometrický zámek.
* Udržovat operační systém zařízení aktualizovaný.
* Vyvarovat se používání Aplikace na zařízeních s neoprávněně upraveným systémem („rootnutých“ nebo po „jailbreaku“).

---

## 9. Ochrana soukromí dětí
Aplikace není určena pro děti mladší 16 let (nebo minimálního věku vyžadovaného místním právem, pokud je nižší – v žádném případě mladší 13 let).

Dětem mladším tohoto věku vědomě neumožňujeme používat funkce importu. Používání služeb třetích stran (Chess.com a Lichess.org) prostřednictvím Aplikace podléhá jejich vlastním věkovým omezením. Rodiče nebo zákonní zástupci, kteří se domnívají, že dítě získalo přístup k externím službám, by měli kontaktovat přímo Chess.com nebo Lichess.org.

---

## 10. Rozhodné právo a řešení sporů
Tyto Zásady ochrany osobních údajů a veškeré spory z nich vyplývající se řídí a vykládají v souladu s polským právem, s vyloučením kolizních norem. Veškeré právní nároky budou řešeny výhradně příslušnými soudy v Polsku.

---

## 11. Právo podat stížnost (Uživatelé z EHP)
Pokud se nacházíte v EHP a domníváte se, že vaše práva na ochranu osobních údajů byla porušena, máte právo podat stížnost u místního úřadu pro ochranu osobních údajů nebo u našeho hlavního dozorového úřadu:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varšava, Polsko  
Webové stránky: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Změny těchto zásad
Tyto Zásady ochrany osobních údajů můžeme pravidelně aktualizovat, aby odrážely změny v našich postupech nebo právních předpisech. O veškerých změnách budeme informovat zveřejněním nové verze v Aplikaci nebo na našich oficiálních stránkách a aktualizací „Data účinnosti“ na začátku dokumentu.

V případě podstatných změn ve způsobu zpracování údajů (např. odklon od architektury local-first) poskytneme viditelnější oznámení, např. formou zprávy v Aplikaci, předtím než změny vstoupí v platnost.

---

## 13. Kontakt
V případě dotazů týkajících se soukromí nebo uplatnění vašich práv kontaktujte Správce údajů:

**E-mail:** WorldiPL@protonmail.com  
*Úplná poštovní adresa a další identifikační údaje jsou k dispozici na písemnou žádost v souladu s čl. 13 GDPR.*
