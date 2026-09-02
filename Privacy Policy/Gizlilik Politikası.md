# Gizlilik Politikası

**Yürürlük Tarihi:** 07.08.2026  
**Veri Sorumlusu:** Tomasz Rutkowski, Polonya'da yerleşik, "Chess M8" uygulamasını bağımsız geliştirici olarak işleten gerçek kişi.  
**Uygulama Adı:** ChessM8  

---

## 1. Giriş
Gizliliğinize saygı duyuyoruz. Bu Gizlilik Politikası, ChessM8 ("Uygulama") uygulamasının bilgileri nasıl topladığını, kullandığını ve koruduğunu açıklar. Uygulamayı kullanarak, bu belgede belirtilen şartları kabul etmiş olursunuz.

---

## 2. Veri Toplama ve İşleme (Local-First Mimarisi)
Uygulama, "Local-First" (yerel işlem önceliği) ilkesine göre tasarlanmıştır. Bu, verilerinizi doğrudan kendi cihazınızda saklayarak gizliliğinizi ilk sıraya koyduğumuz anlamına gelir.

### A. Kişisel Veriler
Uygulama, üçüncü taraf hizmetlerden aşağıdakileri içerebilecek herkese açık satranç oyunu verilerini (PGN dosyaları) çeker:
* Kullanıcı adları (ör. Lichess.org veya Chess.com'dan).
* Oyun hamleleri, zaman damgaları ve reyting puanları.

Kişisel verileri kendi sunucularımızda saklamıyoruz; talebiniz üzerine veriler doğrudan cihazınızdan üçüncü taraf API'lerine iletilir.

### B. Teknik Veriler
* **IP Adresi:** Uygulama harici API'lere bağlandığında, IP adresiniz bu sağlayıcılar (Chess.com/Lichess) tarafından görülebilir, ancak bu adres hiçbir zaman bize gönderilmez veya tarafımızca saklanmaz.

### C. Cihaz İzinleri
Düzgün çalışması için Uygulama şunları gerektirir:
* **İnternet Erişimi:** Yalnızca Chess.com ve Lichess.org API'lerine bağlanmak amacıyla.
* **Depolama (Okuma/Yazma):** PGN dosyalarını cihazınıza kaydetmek ve cihazınızdan yüklemek için (geçerli olduğu durumlarda).

---

## 3. İşleme Amaçları ve Hukuki Sebepleri

### A. Avrupa Ekonomik Alanı (AEA / GDPR) Kullanıcıları
AEA'da bulunuyorsanız, kişisel verileri aşağıdaki amaçlarla işleriz:
1. **Hizmetin sağlanması ve oyun analizi:** Satranç oyunlarını indirmenizi, analiz etmenizi ve istatistikleri Uygulamada görüntülemenizi sağlamak.  
   *Hukuki Sebep:* GDPR Madde 6(1)(b) (talep edilen özellikleri sağlamak için sözleşmenin ifası).
2. **Teknik işlevselliğin sağlanması:** Chess.com ve Lichess.org sunucularıyla güvenli ve güvenilir iletişim kurmak için internet erişimini kullanmak.  
   *Hukuki Sebep:* GDPR Madde 6(1)(f) (uygun işleyişi ve güvenliği sağlama meşru menfaati).
3. **Çevrimdışı kullanım için yerel depolama:** Aktif bir internet bağlantısı olmadan verilere erişebilmeniz için PGN dosyalarını cihaza kaydetmek.  
   *Hukuki Sebep:* GDPR Madde 6(1)(b).

---

## 4. Üçüncü Taraf Hizmetleri
Uygulama bir istemci arayüzü olarak işlev görür. "İçe Aktar" (Import) özelliğini kullandığınızda cihazınız doğrudan şunlara bağlanır:
* **Chess.com** (Gizlilik Politikalarına tabidir)
* **Lichess.org** (Gizlilik Politikalarına tabidir)

Bu veri alışverişinde aracı olarak hareket etmiyoruz. İstek başlıklarınız (Uygulamanın User-Agent bilgisi dahil), bağlantı süresince bu hizmetler tarafından görülebilir.

---

## 5. Bölgesel Gizlilik Hükümleri ve Kullanıcı Hakları

Verilerinizi harici sunucularda saklamadığımız için, nerede yaşarsanız yaşayın bilgileriniz üzerinde doğrudan kontrol sahibi olursunuz.

### 5.1. Avrupa Ekonomik Alanı (AEA) ve Birleşik Krallık (UK)
GDPR ve UK GDPR kapsamında aşağıdaki haklara sahipsiniz:
* **Erişim ve Veri Taşınabilirliği:** Tüm veriler doğrudan kişisel cihazınızda saklanır.
* **Veri Silme:** Cihaz ayarlarından Uygulamanın önbelleğini/verilerini temizleyerek veya Uygulamayı kaldırarak tüm verileri istediğiniz zaman silebilirsiniz.
* **İtiraz Etme / Kısıtlama Hakkı:** Uygulamayı kullanmayı bırakarak veya içe aktarma işlevlerini devre dışı bırakarak işlemeyi istediğiniz zaman durdurabilirsiniz.

### 5.2. Kaliforniya / Amerika Birleşik Devletleri (CCPA / CPRA)
* **Kişisel Verilerin Satılmaması veya Paylaşılmaması:** Kişisel verileri satmıyoruz veya paylaşmıyoruz ve son 12 ay içinde de satmadık veya paylaşmadık.
* **Hassas Kişisel Veriler:** Ayrılma (opt-out) mekanizmaları gerektiren hassas kişisel verileri toplamıyoruz veya işlemiyoruz.
* **Hakların Kullanılması:** Kaliforniya sakinleri, cihazın yerel depolama alanını yöneterek veya bizimle iletişime geçerek haklarını kullanabilirler. Yanıt olarak, cihazınız dışında hiçbir kişisel veri tutmadığımızı teyit ederiz.

### 5.3. Brezilya (LGPD)
Lei Geral de Proteção de Dados (LGPD) uyarınca:
* **Hukuki Sebepler:** Oyun analizi ve yerel depolama amaçlı işleme LGPD Madde 7(V) (sözleşmenin ifası) uyarınca gerçekleştirilir. Harici API'lere teknik bağlantılar LGPD Madde 7(IX) (meşru menfaat) uyarınca yürütülür.
* **Haklar:** İşlemenin teyidi, erişim veya silme haklarınızı doğrudan cihazınızdaki yerel depolamayı yöneterek kullanabilirsiniz.

### 5.4. Hindistan (2023 DPDP Yasası)
Digital Personal Data Protection Act 2023 uyarınca:
* **İlgili Kişi Hakları:** Verilerin silinmesini talep etme ve işleme onayınızı geri çekme hakkına sahipsiniz.
* **Uygulama:** Tüm veriler yerel olarak cihazınızda bulunduğundan, bu hakları doğrudan Uygulama verilerini temizleyerek veya Uygulamayı kaldırarak kullanabilirsiniz.

### 5.5. Diğer Yargı Alanları
Başka bir yargı alanında (ör. Kanada, Avustralya, İsviçre, Japonya veya Singapur) yaşıyorsanız, yerel verilerinize doğrudan cihazınızdan erişme ve bunları silme hakkınız saklıdır.

---

## 6. Uluslararası Veri Aktarımı
İçe aktarma işlevini kullanırken cihazınız doğrudan üçüncü taraf sunucularına bağlanır:
* **Chess.com:** Sunucular Amerika Birleşik Devletleri'nde bulunabilir. Chess.com'a bağlanmak, standart ağ isteklerini (IP adresi ve talep edilen kullanıcı adı dahil) doğrudan ABD'deki sunuculara iletir.
* **Lichess.org:** Altyapı Avrupa Birliği sınırları içerisindedir (Fransa/Almanya).

Uygulamayı ABD veya AB dışından kullanıyorsanız, bir içe aktarma işlemi başlatmak, bağlantı verilerinin bu harici sunuculara doğrudan sınır ötesi aktarımına neden olur. Bu aktarımları kontrol etmiyoruz; bunlar ilgili hizmetin Gizlilik Politikasına tabidir.

---

## 7. Analitik, Profil Oluşturma ve Üçüncü Taraf SDK'ları
* **İzleme SDK'sı Yoktur:** Uygulama analiz, reklam veya kilitlenme raporlama için herhangi bir SDK (Google Analytics, Firebase veya AdMob gibi) kullanmaz.
* **Profil Oluşturma veya Otomatik Karar Verme Yoktur:** Sizin profilinizi oluşturmuyoruz veya kişisel verilere veya oyun geçmişine dayalı otomatik kararlar almıyoruz.
* **Telemetri Yoktur:** Uygulama ile etkileşimlerinize ilişkin hiçbir veri bize gönderilmez.

---

## 8. Veri Güvenliği
Veri depolamanın yerel niteliği nedeniyle güvenlik, cihazınızın korunmasına bağlıdır. Şunları öneririz:
* Cihaz şifresi veya biyometrik kilit kullanılması.
* İşletim sisteminin güncel tutulması.
* Uygulamanın yetkisiz değişiklikler yapılmış ("rootlu" veya "jailbreakli") cihazlarda kullanılmasından kaçınılması.

---

## 9. Çocukların Gizliliği
Uygulama 16 yaşın altındaki (veya daha düşükse yerel yasaların gerektirdiği asgari yaşın altındaki – hiçbir koşulda 13 yaşın altındaki) çocuklara yönelik değildir.

Bu yaşın altındaki çocukların içe aktarma özelliklerini kullanmasına bilerek izin vermiyoruz. Üçüncü taraf hizmetlerin (Chess.com ve Lichess.org) Uygulama aracılığıyla kullanımı kendi yaş kısıtlamalarına tabidir. Bir çocuğun harici hizmetlere eriştiğini düşünen ebeveynler veya vasiler doğrudan Chess.com veya Lichess.org ile iletişime geçmelidir.

---

## 10. Geçerli Hukuk ve Uyuşmazlıkların Çözümü
Bu Gizlilik Politikası ve bundan kaynaklanan tüm uyuşmazlıklar, kanunlar ihtilafı kuralları hariç olmak üzere Polonya hukukuna tabidir ve buna göre yorumlanır. Tüm hukuki talepler yalnızca Polonya'daki yetkili mahkemelerin yetkisindedir.

---

## 11. Şikayet Hakkı (AEA Kullanıcıları)
AEA'da bulunuyorsanız ve gizlilik haklarınızın ihlal edildiğini düşünüyorsanız, yerel veri koruma otoritenize veya lider denetim makamımıza şikayette bulunma hakkına sahipsiniz:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Varşova, Polonya  
Web sitesi: [https://uodo.gov.pl](https://uodo.gov.pl)

---

## 12. Bu Politikadaki Değişiklikler
Uygulamalarımızdaki veya yasal gerekliliklerdeki değişiklikleri yansıtmak için bu Gizlilik Politikasını periyodik olarak güncelleyebiliriz. Değişiklikleri yeni sürümü Uygulamada veya resmi web sitemizde yayınlayarak ve belgenin başındaki "Yürürlük Tarihi"ni güncelleyerek bildireceğiz.

Veri işleme yönteminde önemli değişiklikler olması durumunda (örneğin yerel mimariden vazgeçilmesi), değişiklikler yürürlüğe girmeden önce Uygulama içinde bir mesaj gibi daha belirgin bir bildirim sunacağız.

---

## 13. İletişim
Gizlilikle ilgili sorularınız veya haklarınızı kullanmak için lütfen Veri Sorumlusu ile iletişime geçiniz:

**E-posta:** WorldiPL@protonmail.com  
*Tam posta adresi ve ek kimlik bilgileri GDPR Madde 13 uyarınca yazılı talep üzerine sunulur.*
