# HTML
## Temel iskelet ve Üst bilgi (Metadata) Etiketleri
### Tarayıcıya belgenin türünü, dilini, başlığını ve dış dosya bağlantılarını tanıtan görünmeyen yapı taşlarıdır.

<!-- Not: * ile işaretli olan etiketler kapanış etiketi kullanmayan etiketlerdir (Örneğin; <h1></h1> vs <br>). -->

<!-- <!Doctype html>* = Document Type
Tarayıcıya bu dosyanın güncel bir HTML5 belgesi olduğunu bildirir.

<html> = Hypertext Markup Language
Sayfadaki tüm diğer etiketleri içine alan en dış kök kapsayıcıdır.

<head> = Head (Baş)
Sayfa ayarları, başlık ve CSS/JS bağlantılarının tutulduğu görünmeyen bölümdür.

<title> = Title (Başlık)
Tarayıcı sekmesinde ve arama motorlarında görünen sayfa adını belirler.

<meta>* = Metadata (Üst veri)
Türkçe karakter desteği (UTF-8), mobil uyum (viewport) ve sayfa açıklaması gibi bilgileri tanımlar.

<link>* = Link (Bağlantı)
Harici CSS stil dosyalarını ve sekme ikonunu (favicon) sayfaya bağlar.

<style> = Style (Stil)
HTML Dosyasının kendi içinde doğrudan CSS tasarım kodları yazmayı sağlar.

<script> = Script (Betik)
Sayfaya etkileşim katan JavaScript kodlarını yazar veya harici .js dosyasını bağlar.

<noscript> = No script (Betik yok)
Kullanıcının tarayıcısında JavaScript kapalıysa ekranda gösterilecek uyarı/yedek içeriktir.

<base>* = Base (Temel)
Sayfadaki tüm göreceli bağlantıların (linklerin) baz alacağı ana kök adresi belirler.

<body> = Body (Gövde)
kullanıcının ekranda gördüğü metin, resim ve butonların tamamını kapsayan ana alandır. -->

## Anlamsal (Semantik) Sayfa Düzeni Etiketleri
### Sayfanın hangi bölümünün menü, hangisinin makale veya alt bilgi olduğunu hem tarayıcıya hem de arama motorlarına (SEO) anlatır.

<!-- <header> = Header (Üst bölüm)
Sayfanın veya bir bölümün giriş kısmını (logo, ana başlık, üst menü) kapsar.

<nav> = Navigation (Gezinme)
Site içi ana menü ve gezinme bağlantılarını bir arada tutar.

<main> = Main (Ana içerik)
Sayfanın asıl ve benzersiz içeriğini barındırır; bir sayfada yalnızca bir kere kullanılır.

<section> = Section (Bölüm)
Sayfayı kendi başlığı olan tematik alt bölümlere (örneğin "Hakkımızda", "Hizmetler") ayırır.

<article> = Article (Makale)
Tek başına alınıp başka yerde yayınlansa bile anlamı bozulmayan bağımsız içerikleri (blog yazısı, haber) kapsar.

<aside> = Aside (Yan içerik)
Ana içerikle dolaylı ilişkili yan sütunları, bilgi kutularını veya reklam alanlarını belirtir.

<footer> = Footer (Alt bölüm)
Sayfa veya bölüm sonundaki telif hakkı, iletişim ve alt menü bilgilerini kapsar.

<hgroup> = Heading Group
Bir ana başlık ile ona bağlı alt başlığı veya sloganı anlamsal olarak gruplar.

<search> = Search (Arama)
Site veya sayfa içi arama kutusu ve filtreleme araçlarını kapsayan alandır.

<div> = Division (Bölüm/Kutu)
Anlamsal bir anlamı olmayan, elemanları gruplayıp CSS ile düzenlemek için kullanılan genel blok kutudur.

<span> = Span (Aralık)
Satır içi (inline) genel kapsayıcıdır; bir cümlenin sadece belirli kelimelerine CSS uygulamak için kullanılır. -->

## Başlık ve Paragraf Yapısı Etiketleri
### Metinleri hiyerarşik başlıklara, paragraflara ve alıntı bloklarına ayırır.

<!-- <h1> - <h6> = Heading 1-6
En büyük ve en önemli ana başlıktan (<h1>) en küçük alt başlığa (<h6>) kadar 6 seviyeli başlık oluşturur.

<p> = Paragraph
Standart metin paragrafı oluşturur; altına ve üstüne otomatik boşluk bırakır.

<br>* = Line Break
Paragrafı bölmeden tek satır aşağı inmeyi sağlar.

<hr>* = Horizontal Rule
Konu veya sahne değişimini belirtmek için yatay bir ayırıcı çizgi çizer.

<pre> = Preformatted Text
İçine yazılan boşlukları, satır başlarını ve girintileri hiç bozmadan ekrana basar.

<block quote> = Block Quote
Başka bir kaynaktan alınan uzun alıntıları sayfa kenarından içeride (girintili) gösterir.

<address> = Address (Adres)
Yazarın veya kurumun fiziksel adres, e-posta ve telefon gibi iletişim bilgilerini tanımlar. -->

## Metin Biçimlendirme ve Anlam Vurgusu Etiketleri
### Kelimelerin hem görsel görünümünü hem de taşıdığı anlamsal değeri (kod, kısaltma, klavye tuşu vb.) belirler.

<!-- <strong> = Strong (Güçlü)
Anlamsal olarak çok önemli ve kritik uyarı niteliğindeki metinleri kalın gösterir.

<b> = Bold (Kalın)
Anlamsal bir önem yüklemeden metni yalnızca görsel olarak kalın yazar.

<em> = Emphasis (Vurgu)
Okurken tonlama vurgusu yapılması gereken kelimeleri italik (eğik) gösterir.

<i> = Italic (Eğik)
Yabancı kelimeler, teknik terimler veya iç ses ifadeleri için metni eğik yazar.

<mark> = Mark (İşaretle)
Metni fosforlu kalemle çizilmiş gibi sarı arkaplanla vurgular.

<small> = Small (Küçük)
Telif hakkı, yasal uyarı ve dipnot gibi yan metinleri normal yazı boyutundan küçük gösterir.

<del> = Deleted (Silinmiş)
Belgeden çıkarılan veya eskiyen bilgiyi (örneğin eski fiyatı) üzeri çizili gösterir.

<ins> = Inserted (Eklenmiş)
Belgeye sonradan eklenen yeni bilgiyi altı çizili olarak belirtir.

<s> = Strikethrough
Artık doğru veya geçerli olmayan bilginin üzerini çizer.

<u> = Underline
Yazım hatası veya özel ad gibi altı çizilmesi gereken metinleri işaretler.

<sub> = Subscript (Alt simge)
Kimya formüllerindeki gibi alt simge oluşturur (örneğin H2O).

<sup> = Superscript (Üst simge)
Matematiksel üs ifadeleri gibi üst simge oluşturur (örneğin X2).

<abbr> = Abbreviation (Kısaltma)
Kısaltmaları tanımlar; title özelliğiyle kullanıldığında fareyle üzerine gelince tam açılımını gösterir.

<cite> = Citation (Alıntı/Kaynak)
Bir kitabın, filmin, şarkının veya sanat eserinin adını belirtir.

<q> = Quote (Kısa alıntı)
Paragraf içindeki kısa alıntıları otomatik olarak tırnak işareti içine alır.

<dfn> = Definition (Tanım)
Bir kavramın veya terimin metinde ilk kez tanımlandığı yeri işaretler.

<code> = Code (Kod)
Paragraf içinde geçen bilgisayar kodu parçacıklarını sabit genişlikli yazı tipiyle gösterir.

<kbd> = Keyboard (Klavye)
Kullanıcının basması gereken klavye tuşlarını belirtir (örneğin Ctrl+S).

<samp> = Sample (Örnek çıktı)
Bir bilgisayar programının veya terminalin ürettiği örnek çıktıyı gösterir.

<var> = Variable (Değişken)
Matematik formüllerindeki veya kodlardaki değişken isimlerini belirtir.

<time> = Time (Zaman)
Tarih ve saat bilgilerini arama motorlarının anlayacağı standart formatta tanımlar.

<data> = Data (Veri)
Okunabilir bir metne (örneğin ürün adına) makinenin okuyacağı stok kodu veya sayısal değer ekler.

<bdi> = Bi-Directional Isolation
Türkçe gibi soldan sağa akan bir cümlenin içindeki Arapça/İbranice gibi sağdan sola yazılan kelimeleri izole eder.

<bdo> = Bi-Directional Override
İçindeki metnin yazım yönünü zorla soldan sağa (ltr) veya sağdan sola (rtr) çevirir.

<wbr>* = Work Break Opportunity
Çok uzun kelimelerin ekrana sığmadığında nereden bölünebileceğini tarayıcıya bildirir.

<ruby> = Ruby Annotation
Japonca, Çince gibi Doğu Asya Karakterlerinin üzerine telaffuz notu ekleyen kapsayıcıdır.

<rt> = Ruby Text
<ruby> etiketi içindeki karakterin tam üstünde görünecek okunuş metnini yazar.

<rp> = Ruby Parentheses
Ruby özelliğini desteklemeyen eski tarayıcılarda okunuş metninin etrafına parantez koyar. -->

## Bağlantılar ve Listeler
### Sayfalar arası geçişleri ve maddeli sıralamaları oluşturur.

<!-- <a> = Anchor (Çapa/Bağlantı)
Başka bir web sitesine, sayfa içi bölüme, dosyaya veya e-posta adresine tıklanabilir link verir.

<ul> = Unordered List
Sıra numarası olmayan, madde işaretli (noktalı) liste oluşturur.

<ol> = Ordered List
Numaralı (1,2,3) veya harfli (A,B,C) sıralı liste oluşturur.

<li> = List Item (Liste öğesi)
<ul> veya <ol> etiketlerinin içindeki her bir liste maddesini tanımlar.

<dl> = Description List
Terimlerden ve o terimlerin açıklamalarından oluşan sözlük tarzı liste kapsayıcısıdır.

<dt> = Description Term
<dl> listesi içindeki tanımlanacak terim veya başlığı yazar.

<dd> = Description Details
<dt> ile belirtilen terimin açıklamasını girintili olarak yazar.

<menu> = Menu (Menü)
Etkileşimli araç çubuğu veya işlem butonlarından oluşan anlamsal liste oluşturur. -->

## Görsel, Ses, Video ve Gömülü Medya Etiketleri
### Sayfaya çoklu ortam öğeleri, çizim alanları ve harici pencereler ekler.

<!-- <img>* = Image (Görsel)
Sayfaya resim ekler (src ile dosya yolu, alt ile alternatif açıklama verilir).

<figure> = Figure (Şekil/Bütün)
Görsel, diyagram veya kod bloğunu kendi açıklamasıyla birlikte bağımsız bir bütün olarak kapsar.

<figcaption> = Figure Caption
<figure> içindeki görselin veya çizimin alt yazısını (açıklamasını) oluşturur.

<picture> = Picture (Resim seçici)
Ekran genişliğine veya cihaz desteğine (WebP, AVIF, vb.) göre farklı görsel kaynakları sunar.

<source>* = Source (Kaynak)
<picture>, <audio>, ve <video> etiketleri için alternatif medya dosyalarını tanımlar.

<audio> = Audio (Ses)
Sayfaya oynat/duraklat kontrollü ses veya müzik oynatıcısı ekler.

<video> = Video
Sayfaya doğrudan video oynatıcısı yerleştirir.

<track>* = Track (Altyazı izi)
<video> veya <audio> oynatıcılarına altyazı (.vtt) ve bölüm bilgisi ekler.

<svg> = Scalable Vector Graphics
Zoom yapıldığında bile kalitesi bozulmayan vektörel ikon ve şekiller çizer

<canvas> = Canvas (Tuval)
JavaScript kullanarak 2D/3D grafikler, animasyonlar ve oyunlar çizilen boş alandır.

<map> = Image Map (Görsel haritası)
Tek bir resmin üzerindeki farklı bölgeleri ayrı ayrı tıklanabilir linklere dönüştürür.

<area>* = Area (Bölge)
<map> içindeki tıklanabilir dikdörtgen, daire veya çokgen alanların koordinatlarını tanımlar.

<iframe> = Inline Frame
Mevcut sayfanın içine başka bir web sitesini, haritayı veya videoyu çerçeve içinde gömer.

<embed>* = Embed (Gömme)
Harici bir uygulamayı veya etkileşimli eklentiyi sayfaya doğrudan gömer.

<object> = Object (Nesne)
PDF dosyalarını veya harici medya kaynaklarını sayfaya nesne olarak yerleştirir. -->

## Tablo Etiketleri
### Verileri satırlar ve sütunlar halinde düzenli biçimde göstermek için kullanılır.

<!-- <table> = Table (Tablo)
Tablo yapısını başlatan ve tüm tablo öğelerini içine alan ana kapsayıcıdır.

<caption> = Caption (Tablo başlığı)
Tablonun en üstüne genel başlık veya açıklama ekler.

<thead> = Table Head
Tablonun sütun isimlerini barındıran üst başlık satırlarını gruplar.

<tbody> = Table Body
Tablonun asıl içerik ve veri satırlarını gruplar.

<tfoot> = Table Foot
Tablonun en altındaki genel toplam veya özet satırlarını gruplar.

<tr> = Table Row (Tablo satırı)
Tabloda soldan sağa yeni bir yatay satır oluşturur.

<th> = Table Header
Tablodaki sütun veya satır başlığı hücresidir; metni varsayılan olarak kalın ve ortalı yazar.

<td> = Table Data (Tablo verisi)
Tablodaki standart veri hücrelerinin her birini oluşturur.

<colgroup> = Column Group
Tablodaki bir veya birden fazla dikey sütuna toplu stil uygulamak için gruplama yapar.

<col> = Column (Sütun)
<colgroup> içinde tek bir dikey sütunun arkaplan veya genişlik özelliğini belirler. -->

## Form ve Kullanıcı Girdisi Etiketleri
### Kullanıcıdan bilgi almak, seçim yaptırmak ve verileri sunucuya göndermek için kullanılır.

<!-- <form> = Form
İçindeki tüm veri giriş alanlarını toplayıp sunucuya gönderen ana kapsayıcıdır.

<input>* = Input (Girdi)
Type özelliğine göre metin kutusu, şifre, onay kutusu, radyo butonu, tarih veya dosya seçiciye dönüşür.

<label> = Label (Etiket)
Form kutularının ne işe yaradığını yazar; üzerine tıklandığında ilgili kutuyu aktif hale getirir.

<textarea> = Text Area (Metin alanı)
Mesaj, adres veya yorum gibi çok satırlı uzun metinlerin yazıldığı geniş kutudur.

<button> = Button (Düğme)
Formu gönderen, temizleyen veya JavaScript fonksiyonu çalıştıran tıklanabilir buton oluşturur.

<select> = Select (Seçim kutusu)
Tıklandığında aşağı doğru açılan seçenek listesi (dropdown) oluşturur.

<option> = Option (Seçenek)
<select> açılır listesi veya <datalist> içindeki her bir seçeneği tanımlar.

<optgroup> = Option Group
<select> içindeki uzun seçenek listelerini kategori başlıkları altında gruplar.

<datalist> = Data List (Veri listesi)
<input> kutusuna yazı yazarken kullanıcıya otomatik tamamlama önerileri sunar.

<fieldset> = Field Set (Alan grubu)
Bir form içindeki ilişkili kutuları (örneğin "fatura bilgileri") ince bir çerçeve içine alır.

<legend> = Legend (Çerçeve başlığı)
<fieldset> çerçevesinin tam üst çizgisine başlık yazar.

<output> = Output (Çıktı)
Form içindeki anlık bir hesaplamanın veya kullanıcı işleminin sonucunu gösterir.

<progress> = Progress (İlerleme)
Dosya yükleme veya kurulum gibi bir işlemin tamamlanma yüzdesini çubuk olarak gösterir.

<meter> = Meter (Ölçer)
Bilinen minimum ve maksimum aralığındaki bir ölçümü (örneğin disk doluluğu, sınav puanı) gösterir. -->

## Etkileşimli ve Modern Bileşen Etiketleri
### Ekstra JavaScript yazmadan açılır kutular ve yeniden kullanılabilir şablonlar oluşturur.

<!-- <details> = Details (Detaylar)
Kullanıcının tıklayıp açıp kapatabileceği gizli bilgi (akordeon) kutusu oluşturur.

<summary> = Summary (Özet)
<details> kutusunun kapalıyken bile her zaman görünen tıklanabilir başlığıdır.

<dialog> = Dialog (Diyalog penceresi)
Sayfa üzerinde açılan uyarı, onay veya bilgi penceresi (Modal/Popup) oluşturur.

<template> = Template (Şablon)
Sayfa ilk yüklendiğinde ekranda görünmeyen, gerektiğinde JavaScript ile çoğaltılan HTML kalıbıdır.

<slot> = Slot (Yuva)
Özel bileşenler (Web Components) oluştururken dışarıdan gelecek içeriğin yerleşeceği yeri belirler. -->

<!-- Not: Eski HTML4 döneminde kullanılan <font>, <center>, <big> ve <strike> gibi görsel biçimlendirme etiketleri güncel HTML5 standartında kaldırılmıştır; tasarım ve hizalama işlemlerinin tamamı artık CSS ile yapılır. -->
