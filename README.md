# Mum Yapımı — Sıfırdan Sanata

**Cage Art Studio** tarafından hazırlanan *Sıfırdan Mum Yapımı ve Satış Rehberi* e-kitabı.

- **Canlı sürüm:** https://mohanadbasrak.github.io/E-kitap-1/ (GitHub Pages, `main` dalından yayınlanır)
- **Güncel sürüm:** 2.0.0 · Kasım 2026
- **Biçim:** Tek dosya `index.html` (fotoğraflar dosyanın içine gömülüdür, ek dosya gerekmez)

> `main` dalına yapılan her push canlı kitabı değiştirir. Değişiklikleri önce ayrı bir dalda hazırlayın.

---

## Kitabı kullanma

| Ortam | Nasıl? |
|---|---|
| Telefon / tablet | Bağlantıyı açın. Üstteki **İçindekiler** düğmesi tüm bölümlere götürür. **Aa** yazı boyutunu değiştirir. Kitap, kaldığınız bölümü hatırlar. |
| Bilgisayar | Aynı bağlantı. Hesaplayıcılar sayfanın içinde çalışır. |
| A4 baskı / PDF | İçindekiler menüsündeki **A4 yazdır / PDF** düğmesi ya da tarayıcının Yazdır komutu. Chrome ile 111 sayfa çıkar. İçindekiler sayfa numaralıdır; her sayfada üst bilgi ve sayfa numarası bulunur. Hesaplayıcılar baskıda formül kutusuna dönüşür. |

---

## Sürüm geçmişi

### [2.0.0] — 2026-11-19

Kitap baştan sona yeniden yazıldı ve yeniden tasarlandı. İçerik; cagearts.com blogundaki mum yazıları, Akademi, Sıkça Sorulan Sorular, Silikon Kalıp Kullanım Talimatı ve Kalıp Nasıl Kesilir sayfalarıyla uyumlu hâle getirildi.

#### Tasarım

- **cagearts.com'un tasarımı birebir uygulandı.**
  - Yazı tipleri sitedekiyle aynı: başlıklarda **Manrope** (700), metinde **Inter Tight**. Vurgu kelimesi italik değil, sitedeki gibi düz ve turuncu.
  - Renkler: sıcak siyah `#1F1A16`, beyaz, marka turuncusu `#E34E05`; sitedeki gri paneller (`#F3F2F0`) ve ince çizgiler (`#E5E2DE`).
  - Bileşenler sitenin rehber sayfalarından alındı: numara rozetli kısım başlıkları, "Kısaca" özet kutusu, ince çerçeveli tablolar, turuncu numaralı adımlar, gri sayı kartları, açılır sorun kartları.
- **Cage Art Studio logosu** üst çubukta, kapakta, kapanışta ve baskıda her sayfanın üst bilgisinde kullanılıyor.
- **Düzenli bölüm yapısı:**
  - Her bölüm aynı sırayla açılıyor: üst etiket, başlık, kısa giriş, **Kısaca** kutusu (bölümün ana noktaları) ve **Bu bölümde** listesi.
  - Bölümün kısımları ince çizgilerle ayrılıyor; her kısım numara rozetiyle başlıyor.
- **Kapak:** Beyaz zemin, logo, başlık ve fotoğraf; sitedeki "öne çıkan rehber" kartı düzeninde.
- **Kapanış:** Sitedeki koyu iletişim kutusu düzeninde.
- **Telefona uyumlu akışkan düzen.** v1'in sabit 210 mm genişlikteki sayfaları telefonda küçülüyordu; artık metin her ekranda kendi boyutunda akıyor. Tablolar telefonda yana kaydırılabiliyor.
- **Ayrı A4 baskı düzeni:**
  - Üst bilgide logo, altta sayfa numarası.
  - Her bölüm yeni sayfada başlıyor.
  - Tablo, kart ve reçeteler sayfa arasında bölünmüyor.
  - Açılır sorun kartları baskıda otomatik açılıyor.
  - Kapak ve kapanış tam sayfa.
  - Boş ya da tek satırlık sayfa kalmayacak şekilde düzenlendi: uzun tablolar sayfalar arasında bölünüyor (başlık satırı her sayfada tekrar ediyor), reçeteler sayfa başına iki ya da üç tane, fotoğraflar sayfaya sığacak boyutta basılıyor ve bölüm sonları ölçülerek gerektiğinde sıkıştırılıyor.
- 15 fotoğrafın tamamı korundu ve **netleştirildi**: yüksek kaliteli büyütme ve hafif keskinleştirmeyle 1000–1100 pikselden 1600–1760 piksele çıkarıldı, WebP olarak gömüldü. Baskıda fotoğraflar 400 ppi'nin üzerinde çıkıyor; yüksek çözünürlüklü telefon ve bilgisayar ekranlarında bulanıklaşmıyor.
- Bütün şemalar yeni paletle yeniden çizildi; bunlara **16 yeni vektörel şema** eklendi: wax formları, çapa göre fitil, kap ölçüleri, kapasite çubuğu, kalıba fitil takma, su yöntemi, ikinci döküm, kalıptan çıkarma, koku piramidi, renk karışımı, ilk yakış, güvenli mesafe, yanma testi, fiyat yapısı, etiket örneği ve sezon takvimi. Telefonda şemalar okunur boyutta gösterilir ve yana kaydırılabilir.
- **19 yeni fotoğraf** eklendi (Pexels, ücretsiz lisans): termometreyle ölçüm, fitil yerleştirme, dinlendirme, çoklu döküm, esans, bubble mum, süsleme, fitil kesme, söndürücü, is, parti kaydı, etiket, ürün fotoğrafı, marka, hediye ve koleksiyon. Kitapta toplam 34 fotoğraf, 51 şekil ve 30 tablo var.

#### Yeni ekran özellikleri

- **Üst çubuk:** Okunan bölümün adını ve okuma ilerleme çubuğunu gösteriyor.
- **Okuma araçları:**
  - Bütün alt başlıkları listeleyen içindekiler çekmecesi.
  - Üç kademeli yazı boyutu.
  - "Kaldığınız yerden devam edin" bildirimi.
  - Başa dön düğmesi.
- **Dört hesaplayıcı:**
  - Kalıbım için kaç gram?
  - Elimdeki wax ile kaç mum çıkar?
  - Ne kadar malzeme lazım? (beş ürün türü)
  - Maliyet ve fiyat.
- **Kaydedilen kontrol listeleri:** Döküm öncesi hazırlık, kap kontrolü ve gönderim öncesi kontrol.
- **Sorun arama kutusu:** Sorun Giderme Atlası'nda belirti yazınca ilgili kartlar süzülüp açılıyor. Kartlar sitedeki gibi açılır; içinde "Neden olur?", "Nasıl düzelir?" ve "Önlemek için" kutuları var.
- **Tıklanabilir içindekiler:** Ekranda bağlantı olarak çalışıyor, baskıda sayfa numarası gösteriyor.

#### Eklenen içerik

- **Cep Kartı · Ölçüler tek bakışta:** Atölyede en çok gereken 12 sayı tek sayfada, Akademi'deki cep tablosuyla aynı değerlerle.
- **Bölüm 03 · Silikon Kalıp Ustalığı (yeni bölüm):**
  - Kalıbı tanıma ve ters döküm mantığı.
  - İlk kullanım hazırlığı.
  - Kesik ve kesiksiz kalıplar; adım adım kesim ve sarma.
  - Kalıba fitil takma.
  - "Kalıp kaç gram alır?" (su × 0,82; 25 modelin kapasite tablosu).
  - Döküm ve ikinci döküm.
  - Kalıptan çıkarma ve "üç işaret".
  - Temizlik, saklama, kalıp ömrü ve Özel Silikon Kalıp Hizmeti.
- **Bölüm 08 · Kullanım, Bakım ve Yanma Testi (yeni bölüm):**
  - Çapa göre ilk yakış tablosu ve her yakışta yedi kural.
  - Üç söndürme yöntemi ve tüneli kurtarma.
  - Mumun ne zaman bittiği.
  - Leke temizliği.
  - Profesyonel yanma testi protokolü.
  - Müşteriye verilecek bakım kartı.
- **Bölüm 05 · Koku ve Renk Atölyesi (genişletildi):**
  - Esans ekleme, soğuk ve sıcak koku.
  - Cage Art Studio esanslarının nota haritası ve 14 harman.
  - "Mumum neden kokmuyor?" teşhis tablosu.
  - Renk verme, beyaz tabak testi ve renk karışım tablosu.
  - Sararma.
  - Mum cilası, İnci Tozu Mum, mika ve sedef.
- **Bölüm 06 · Teknikler:** Bubble mum, şamdan mumları, parafin sütun mumu, wax melt, jel mum ve eski mumları yeniden değerlendirme eklendi.
- **Bölüm 01 · Malzemeler:**
  - Cage Art Studio wax'ları: Pillar Soy Wax, Golden Soya Wax, Doğal Soya Wax, Amerikan Soya Wax, Boncuk Parafin, Yerli Parafin ve Jel Mum.
  - Stearik asit hesabı.
  - Fitil türleri ve sabitleme ürünleri, çapa göre fitil seçimi.
  - 22 esans ve gramla tartma kuralı.
  - Boya türleri.
  - Cage Art Studio kapları ve ilk dolum kontrolü.
  - Ekipman ve eritme yöntemleri.
- **Bölüm 02 · İlk Mumunuz:**
  - İki proje: Büyük Bubble kalıp mumu ve 150 g bardak mumu.
  - "Erime, ısıtma ve döküm üç ayrı aşamadır" açıklaması ve benmari adımları.
- **Bölüm 04 · Ölçü ve Hesap Merkezi:**
  - Altı temel formül.
  - Kap ve kalıba göre hazır wax + esans tablosu.
  - Ürün bazında sıcaklık cetveli.
  - "1 kg wax kaç mum çıkar?"
  - 12, 25 ve 50 adetlik çoklu sipariş tabloları.
  - Tartarak yanma süresi hesabı.
- **Bölüm 07 · Sorun Giderme Atlası:** 24 sorun kartı (belirti, sebep, çözüm, önlem) ve hızlı teşhis tablosu. Kalıba özgü sorunlar eklendi: yapışma, kırılma, dikiş izi, sızıntı ve yırtık.
- **Bölüm 09 · Hobiden Satışa:**
  - Gerçek rakamlarla maliyet örneği.
  - Marj formülü ve komisyonlu fiyat.
  - Kurumsal ve çoklu sipariş fiyatlaması.
  - Kalite kontrol ve parti kaydı.
  - Ön ve alt etiket.
  - SEA Yönetmeliği / CLP alerjen eşikleri, IFRA Kategori 12, MSDS.
  - Vergi ve e-ticaret adımları.
  - Hediye ve sezon takvimi, hazır kart metinleri.
- **Bölüm 10 · Reçete Koleksiyonu:** 12 reçeteden 16 reçeteye çıktı. Yeni reçeteler: Öğretmene Teşekkür, Kozalak ve Palamut, Yılbaşı Ağacı, Akşam Yemeği Şamdanları ve Lavanta Wax Melt.
- **Ekler:**
  - Yazdırılabilir dört form: kendi tarifim, parti kaydı, yanma testi günlüğü, birim maliyet.
  - 37 terimlik sözlük.

#### Değişen ve düzeltilen içerik

- **Sıcaklıklar Cage Art Studio değerlerine göre düzeltildi:**
  - Soya wax ısıtma: 80–85 °C (v1'de 70–75 °C).
  - Esans ekleme: 80–85 °C'de, pot ocaktan alınınca (v1'de 60–65 °C).
  - Pillar Soy Wax: "genellikle 55–65 °C'de dökülür; oda soğuksa 70 °C'ye kadar çıkabilirsiniz."
  - Kavanoz dökümü: 55–60 °C.
  - Parafin dökümü: boncuk parafinde yaklaşık 70 °C, sütun mumunda 77–82 °C (v1'de 60–70 °C). Parafin en fazla 93 °C'ye ısıtılır.
- **Süreler düzeltildi:**
  - Kalıptan çıkarma "genellikle 3–5 saat (kalıbın boyutuna göre)". v1'deki "kalın olanlar bir geceyi bulabilir" ifadesi kaldırıldı.
  - Takılan mum için buzdolabında yaklaşık 5 dakika (v1'de 15–20 dakika). Dondurucu asla.
  - Yakmadan önce en az 24 saat.
- **Hesaplar düzeltildi:**
  - Kap hacmi × 0,8 yerine su ağırlığı × 0,82 (cagearts.com Hesap Makinesi ile aynı).
  - Esans hesabında "wax = toplam ÷ (1 + oran)".
  - İkinci döküm için %10 pay.
  - Tahmini yanma süresi tablosunun yerine tartarak ölçme yöntemi geldi.
- **Kesik kalıp bilgisi eklendi:** Yalnızca Şamdan M1–M11 ve Hayalet Şamdan kesik gelir, diğer kalıplar kesiksizdir. Kesim dökümden önce, arka ya da yan yüzden, maket bıçağıyla yapılır; ardından kalıp para lastiği ya da koli bandıyla sarılır.
- **Silikon tanımı** "birinci kalite, yumuşak ve şeffaf silikon" olarak sabitlendi.
- **Fitil tablosu** Cage Art Studio fitillerine göre yeniden yazıldı: 8 ve 12 cm çıtçıtlı, 10 m mumlanmış ince fitil, ahşap fitil.
- **Balmumu ve hindistan cevizi wax'ı** karşılaştırma tablosundan çıkarılıp "Diğer wax'lar" bilgi notuna taşındı.
- **Reçeteler:**
  - Gramajlar Cage Art Studio kaplarına (100 cc, 150 g, 250 cc) ve kalıplarına göre yeniden hesaplandı.
  - "Yasemin Zarafeti" yerine "Akşam Yemeği Şamdanları" geldi.
  - "Yeşil Orman" ve "Kış Masalı" koku formülleri yenilendi.
- **Satış bölümünde** "toptan" ifadeleri "kurumsal ve çoklu sipariş" olarak değiştirildi.
- **Hitap dili** sitenin diliyle uyumlu olsun diye "sen"den "siz"e geçti.

#### Yayın öncesi son kontrolde düzeltilenler

- **Doğal Soya Wax:** Cep Kartı ve sıcaklık cetvelinde 55–60 °C döküm değeri kaldırıldı; wax 65–70 °C'de eridiği için "ürün talimatı + deneme dökümü" yazıldı.
- **Yanıcı süsler (Bölüm 6.4):** Yakılacak mumda kuru çiçek, tarçın, kurdele gibi süsler artık paketin dışında tutuluyor. Süs gömülen mum yalnızca "Dekoratif ürün, yakmayın" notuyla sunuluyor. Koku teşhis tablosu da buna uyduruldu.
- **Güvenlik:**
  - Alev çok büyüdüğünde önce mum söndürülüyor, fitil soğuyunca kesiliyor.
  - Cereyanda yanan mum taşınmıyor; önce söndürülüyor.
  - Folyo yöntemine cam uyarısı eklendi.
  - Bakım kartına kalıp mumu için 5 cm sınırı eklendi.
  - Buhurdanlıkta açık alev uyarısı eklendi.
  - Jelde esans uyumluluğu uyarısı eklendi.
  - Cila için maske ve göz koruması için gözlük eklendi.
- **Hesaplar:**
  - Şekil 9.1'deki kâr %15 komisyon ve %40 marjla yeniden hesaplandı: ~278 TL yerine ~222 TL.
  - Yanma süresi "teorik süre" olarak açıklandı; dipte kalan wax'ın yanmadığı belirtildi.
  - Wax melt formülü "toplam ÷ 1,10" olarak düzeltildi.
  - Harman örneği 60/40 orana getirildi (24 + 16 g).
  - Reçete 14'e esans payı eklendi.
- **Alerjen eşikleri (Tablo 9.3):** Eşikler tek bileşen için veriliyor (%0,1 ve %1; güçlü bileşenlerde %0,01 ve %0,1). EUH208 metni "yol açabilir" olarak düzeltildi. Örnek hesap %0,09'a düzeltildi.
- **Kurumsal fiyatlama:** "Birim fiyat düşer" ifadesi kaldırıldı. İki katmanlı fiyat yapısı ve mağazanın raf fiyatı açıkça anlatıldı.
- **Ürün bilgileri:**
  - Şamdan M3 (21,2 × 2,6 cm) ve M9–M11 (22 × 1,9 cm) ölçüleri eklendi.
  - "Swirl Küre" adı sitedeki gibi "Swiral Küre" oldu.
  - Fitil boyu kuralı ve fitil çapı aralıkları düzeltildi.
  - 150 g bardak için "kapağını kapatmayın" yerine "üstünü örtmeyin" yazıldı.
- **Tutarlılık ve dil:**
  - Kapakta "10 bölüm" yerine "11 bölüm" yazıldı (00–10).
  - Önsözdeki ters anlamlı cümle düzeltildi.
  - Şekil 7.2 ve 9.3 altyazıları fotoğraflara uyduruldu.
  - Küçük yazım düzeltmeleri yapıldı.

#### Kaldırılanlar

- Kaynaklar: künyedeki "Kaynaklar" satırı ve "Ek 3 · Cage Art Studio kaynakları" bölümü; okuru başka sayfalara yönlendiren cümleler kitabın kendi içinde çözüldü. "Tedarikte üç altın kural" kutusu Bölüm 1.9'a taşındı.

- Sayfalarda gizli duran "Fotoğraf Alanı" yer tutucuları ve görsel üretim istemleri.
- Playfair Display ve Poppins yazı tipleri (yerine sitedeki Manrope ve Inter Tight geldi).

### [1.0.0]

İlk yayın.

- **Bölümler:** Başlamadan, Malzemeler ve Ekipman, İlk Mumun, Ölçü ve Reçete Merkezi, Kalıp ve Dekoratif Mumlar, Sorun Giderme Atlası, Hobiden İlk Satışa, Reçete Koleksiyonu (12 reçete), Terimler Sözlüğü, Tedarik ve Kaynaklar.
- **Biçim:** Yaklaşık 70 A4 sayfa, 15 gömülü fotoğraf.

---

## İçerik kuralları (editörler için)

Kitapta değişiklik yaparken şu kurallara uyun:

**Marka ve dil**
- Marka adı her zaman **"Cage Art Studio"** yazılır, asla tek başına "Cage Art" yazılmaz.

**Sıcaklık ve süreler**
- Pillar Soy Wax: "genellikle 55–65 °C'de dökülür; oda soğuksa 70 °C'ye kadar çıkabilirsiniz."
- Kalıptan çıkarma: "genellikle 3–5 saat (kalıbın boyutuna göre)".
- Yakmadan önce: "en az 24 saat".

**Kalıplar**
- Yalnızca Şamdan M1–M11 ve Hayalet Şamdan kesik gelir; diğer kalıplar kesiksizdir.
- Kesim dökümden önce, arkadan ya da yandan, maket bıçağıyla yapılır.
- Kesimden sonra kalıp para lastiği ya da koli bandıyla sarılır.
- Silikon "platin" olarak anılmaz; "birinci kalite, yumuşak ve şeffaf silikon" denir.

**Kitapta yer almayacaklar**
- Jesmonite ve "vakumlu döküm" vurgusu.
- Fitil yapımı ve silikon kalıp yapımı (öğretilmez).
- Etsy ve "toptan" kelimesi.
- Taş tozu, beton ve alçı karışım oranları.

**Kaynaklar**
- cagearts.com/blog mum yazıları.
- Sıkça Sorulan Sorular, Akademi, Kalıp Kullanım Talimatı ve /pages/kalip-nasil-kesilir sayfaları.

## Fotoğraflar

- 15 fotoğraf 1.0.0 sürümünden geliyor.
- 19 fotoğraf [Pexels](https://www.pexels.com/license/) üzerinden alındı. Pexels lisansı ticari kullanıma izin veriyor ve kaynak gösterme zorunluluğu yok. Kitapta kaynak bölümü bulunmadığı için fotoğraf kimlikleri burada kayıtlı: 6755628, 5760780, 6755744, 8272376, 7615878, 6044963, 7233956, 7033937, 6755809, 6752300, 8271829, 6311870, 7309930, 6755793, 6333008, 6755760, 7233971, 6634662, 7004668.

## Notlar

- Bazı blog yazıları e-kitabı "12 reçete" ile tanıtıyor. 2.0.0 sürümünde 16 reçete var; ilgili yazılar güncellenebilir.
- "Evde mum yapıp satmak" yazısındaki alerjen tablosu "hassaslaştırıcıların toplamı %1" diyor. Kitapta eşikler tek bileşen için verildi; blogdaki satır da buna göre güncellenebilir.
- Maliyet örneğindeki fiyatlar Ekim 2026 tarihlidir. Fiyatlar değiştikçe Tablo 9.1'in güncellenmesi gerekir.
- Baskıdaki içindekiler sayfa numaraları Chrome'un A4 çıktısına göre hesaplanmıştır. İçerik değişirse bu numaraları yeniden hesaplayın.
