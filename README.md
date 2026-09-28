# Defter Notları

## Hafta 1

### Oyun Programlama: Unity Kavramları

Kavramları kısa tanımları ve derste kullanılan benzetmeleriyle yaz:

- **Unity Hub:** Unity projelerini ve Unity sürümlerini yönettiğimiz araç kutusu.
- **LTS:** Uzun Süreli Destek; daha kararlı ve uzun süre desteklenen sürüm.
- **Visual Studio:** Unity için kod yazıp düzenlediğimiz program.
- **Scene:** Oyunu hazırladığımız çalışma alanı; film seti gibi düşünülebilir.
- **Game:** Oyuncunun gördüğü oyun ekranı.
- **Hierarchy:** Sahnedeki nesnelerin isim listesi.
- **Project:** Oyun dosyalarının (ses, resim, kod vb.) bulunduğu depo.
- **Inspector:** Seçili nesnenin özelliklerini görüntüleyip değiştirdiğimiz panel.

### Grafik ve Photoshop

#### Çözünürlük ve renk modu

Aşağıdaki soruları cevaplayarak yaz:

- Matbaada afiş basmak için gereken en düşük çözünürlük ve renk modu nedir?
- Yalnızca Instagram'da paylaşılacak bir tasarım için çözünürlük ve renk modu ne olmalıdır?

#### Photoshop araçları

Photoshop Araç Kutusu'ndan üç araç seç. Her birinin simgesini çizip İngilizce adını ve kısayol harfini yanına yaz. Örnek: **Move Tool - V**.

#### Grafik türleri, bit derinliği ve dosya biçimleri

- Vektörel grafiğin matematiksel formüllere dayalı çizimini yap.
- Piksel tabanlı grafiğin ızgara/piksellerden oluşan çizimini yap.
- **Bit derinliği:** $2^8 = 256$ hesabını not et.
- **PSD:** Photoshop'un düzenlenebilir çalışma dosyası.
- **JPG/JPEG:** Fotoğraflarda sık kullanılan, sıkıştırılmış biçim; şeffaf arka planı desteklemez.
- **PNG:** Şeffaf arka planı destekleyebilir; logo ve arka planı kaldırılmış görsellerde kullanılır.

### Web Tabanlı Uygulama: Temel Kavramlar

#### İnternetin temel yapı taşları

- **IP adresi:** İnternete bağlı cihazı tanımlayan sayısal adres.
- **DNS:** Alan adlarını IP adreslerine çeviren sistem; internetin telefon rehberi.
- **Sunucu (Server):** Web sitelerini ve dosyaları barındırıp istekleri yanıtlayan bilgisayar.
- **HTTP:** Tarayıcı ile sunucu arasında web verilerinin aktarım kuralları.
- **HTTPS:** İletişimi şifreleyerek güvenli hale getiren HTTP sürümü.

#### Web sitesinin adresi ve konumu

- **Domain (Alan adı):** IP adresi yerine kullanılan, akılda kalıcı web sitesi adı.
- **URL:** Bir web kaynağının internetteki tam adresi.
- **WWW (World Wide Web):** URL'lerle erişilen, birbirine bağlı web sayfaları ve içeriklerden oluşan sistem.
- **Hosting (Barındırma):** Web sitesi dosyalarının internetten erişilebilen sunucuda tutulması hizmeti.
- **FTP:** Bilgisayar ile sunucu arasında dosya aktarma protokolü.

#### Web sayfasının yapısı ve görünümü

- **HTML:** Web sayfasının başlık, paragraf ve resim gibi içeriğini/yapısını oluşturan işaretleme dili.
- **Etiket (Tag):** HTML'de bir elementi tanımlayan, `<` ve `>` işaretleri arasındaki ifade. Örnek: `<p>`.
- **CSS:** Web sayfasının renk, yazı tipi ve yerleşim gibi görsel özelliklerini belirleyen dil.
- **JavaScript (JS):** Web sayfalarına etkileşim ve dinamizm katan programlama dili.

#### Web geliştirme rolleri ve araçları

- **Front-end (Ön yüz):** Kullanıcının tarayıcıda gördüğü ve etkileştiği arayüz.
- **Back-end (Arka yüz):** Sunucu, veritabanı ve iş mantığı gibi kullanıcıya görünmeyen sistemler.
- **Full-stack (Tam yığın):** Hem ön yüz hem arka yüz geliştirme.
- **Tarayıcı (Browser):** Web sayfalarını görüntüleyip kullanmamızı sağlayan yazılım.
- **Kod editörü:** HTML ve CSS gibi kodları yazıp düzenlediğimiz program; örnek: VS Code.
- **WYSIWYG editör:** Kod yazmadan görsel araçlarla sayfa oluşturan, “Ne Görürsen Onu Alırsın” yaklaşımındaki editör.

#### Yaygın alan adı uzantıları

- **.gov:** Devlet kurumları
- **.edu:** Eğitim kurumları
- **.k12:** Temel eğitim ve ortaöğretim kurumları
- **.org:** Ticari olmayan kuruluşlar
- **.com:** Ticari kuruluşlar

## Hafta 2

### Grafik ve Photoshop: Kısayol Sözlüğü

Kısayolları defterine sözlük olarak yaz ve ezberle:

- **V:** Taşıma Aracı (Move Tool); işlemler arasında seçili araca dönmek için kullanılır.
- **Z:** Büyüteç (Zoom); yakınlaştırır. **Alt** ile tıklamak uzaklaştırır.
- **Boşluk (Space):** El Aracı (Pan); sayfa içinde gezinmeyi sağlar.
- **C:** Kırpma Aracı (Crop Tool); görüntünün fazlalıklarını keser.
- **J:** Yara Bandı (Spot Healing); küçük leke ve kusurları siler.
- **B:** Fırça Aracı (Brush Tool); boyama yapar.
- **Ctrl + N:** Yeni belge oluşturur (New Document).
- **Ctrl + O:** Var olan dosyayı açar (Open).
- **Ctrl + Z:** Son işlemi geri alır (Undo).
- **Ctrl + D:** Seçimi kaldırır (Deselect).
- **Ctrl + Shift + N:** Yeni katman oluşturur (New Layer).
- **Ctrl + S:** Dosyayı kaydeder (Save).

### Oyun Programlama: Kod Sözlüğü

Kavramları kendi anlayacağın dille, kısaca yaz:

- **Script:** Oyundaki nesnelere ne yapacaklarını söyleyen kod dosyası.
- **`void Start()`:** Oyun başladığında bir kez çalışan kod bölümü.
- **`void Update()`:** Oyun açık olduğu sürece sürekli çalışan kod bölümü.
- **`Debug.Log()`:** Unity Konsolu'na mesaj yazdırmaya ve hata ayıklamaya yarayan komut.
- **`public`:** Değişkeni Unity Inspector panelinde görünür ve düzenlenebilir yapan erişim belirleyicisi.
- **`transform.Translate`:** Nesneyi X, Y veya Z yönünde hareket ettirmek için kullanılan kod.

### Web Tabanlı Uygulama: Web Tasarımın 7 İlkesi

İlkeleri defterine yaz:

1. **İçerik:** Yazı, resim ve videoların özgün, doğru ve hedef kitleye uygun olması.
2. **Tasarım (Layout):** Logo, menü ve içeriklerin sayfada nasıl yerleşeceğinin planlanması.
3. **Biçimsellik:** Renk uyumu, kontrast ve okunabilir yazı tiplerinin (tipografi) kullanılması.
4. **İşlevsellik ve kullanılabilirlik:** Sitenin hızlı çalışması; menü ve butonların doğru, kullanımın kolay olması.
5. **Güncellik:** İçeriklerin güncel, kullanılan teknolojilerin modern olması.
6. **Uygunluk ve güvenilirlik:** İletişim bilgilerinin bulunması, bağlantıların çalışması ve yazım hatalarının olmaması.
7. **Uyumluluk:** Sitenin farklı tarayıcı ve cihazlarda bozulmadan çalışması; duyarlı (responsive) tasarım.
