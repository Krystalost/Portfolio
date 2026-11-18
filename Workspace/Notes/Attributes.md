# Attributes

<!-- id = Identifier (Kimlik)
Tekil eleman tanımlama

class = Classification (Sınıf)
Çoklu gruplama ve stil

style = Style (Stil)
Satır içi CSS yazımı

title = Title (Başlık)
İpucu metni gösterme

hidden = Hidden (Gizli)
Elemanı ekranda gizleme

data-* = Data (Veri)
Özel veri saklama

href = Hypertext Reference (Hipermetin Referansı)
Bağlantı adresi belirtme

target = Target (Hedef)
Bağlantı açılış konumu

rel = Relationship (İlişki)
Bağlantı ilişki türü

src = Source (Kaynak)
Dış dosya yolu

alt = Alternate Text (Alternatif Metin)
Görsel açıklama metni

width / height = Width / Height (Genişlik / Yükseklik)
Eleman boyutlandırma

action = Action (Eylem)
Form gönderim adresi

method = Method (Yöntem)
HTTP gönderim türü

type = Type (Tür)
Girdi davranış türü

name = Name (İsim)
Backend veri anahtarı

value = Value (Değer)
Girdi başlangıç değeri

placeholder = Placeholder (Yer Tutucu)
Geçici ipucu yazısı

required = Required (Zorunlu)
Boş geçmeyi engelleme

disabled = Disabled (Devre Dışı)
Etkileşimi kapatma

for = For (İçin)
Etiketi girdiye bağlama

lang = Language (Dil)
Belge dili tanımı

charset = Character Set (Karakter Seti)
Harf kodlama standardı -->

## Genel Nitelikler (Global Attributes)

<!-- id: Sayfadaki tek bir elemana benzersiz kimlik verir; JavaScript ile o elemanı seçmek veya sayfa içi yönlendirme yapmak için kullanılır.

class: Birden fazla elemanı aynı grup altında toplar; CSS ile toplu tasarım yapmak ve JavaScript ile çoklu seçim sağlamak için kullanılır.

style: Harici CSS dosyasına gitmeden doğrudan etiketin içine satır içi tasarım kuralları yazmayı sağlar.

title: Fare imleci elemanın üzerine geldiğinde küçük bir kutucuk (tooltip) içinde ek açıklama gösterir.

hidden: Elemanı sayfa yüklendiğinde görünmez yapar; genellikle JavaScript ile bir koşul gerçekleştiğinde görünür hale getirilir.

data-*: Yıldız yerine kendi belirlediğin bir isimle HTML içinde özel veri tutmanı ve bu veriyi JavaScript ile okumanı sağlar. -->

## Bağlantı ve Medya Nitelikleri

<!-- href: Link etiketlerinde tıklanıldığında gidilecek URL adresini veya indirilecek dosyanın yolunu belirtir.

target: Linkin mevcut sekmede mi yoksa yeni bir sekmede mi (_blank değeri ile) açılacağını belirler.

rel: Mevcut sayfa ile bağlanılan dosya arasındaki ilişkiyi (örneğin stylesheet veya noopener) tarayıcıya bildirir.

src: Görsel, video veya harici JavaScript dosyalarının projedeki ya da internetteki kaynak adresini sayfaya çağırır.

alt: Görsel yüklenemediğinde ekranda çıkacak metni belirler; görme engelli ekran okuyucuları ve SEO için kritiktir.

width ve height: Görsel, video veya tablo gibi elemanların piksel bazında genişlik ve yükseklik değerlerini ayarlar. -->

## Form ve Fullstack Veri Nitelikleri

<!-- action: Kullanıcı formu doldurup gönderdiğinde verilerin backend tarafında hangi URL veya API uç noktasına gideceğini belirler.

method: Form verilerinin sunucuya hangi HTTP protokolüyle (GET ile adres çubuğunda veya POST ile gizli gövdede) gönderileceğini seçer.

type: Input etiketinin metin kutusu, şifre alanı, onay kutusu (checkbox) veya gönderim butonu (submit) olacağını belirler.

name: Fullstack için en önemli niteliktir; form gönderildiğinde verinin backend tarafında hangi değişken adıyla yakalanacağını belirler.

value: Bir girdi alanının varsayılan değerini veya seçilen bir seçeneğin sunucuya göndereceği gerçek veriyi tutar.

placeholder: Kullanıcı veri girene kadar kutunun içinde silik şekilde duran örnek veya açıklayıcı metni gösterir.

required: JavaScript yazmaya gerek kalmadan, ilgili alan doldurulmadan formun gönderilmesini tarayıcı düzeyinde engeller.

disabled: Buton veya girdi alanını tıklanamaz hale getirir ve o alandaki verinin form ile birlikte sunucuya gitmesini önler.

for: Label etiketinin içine hangi input elemanının id değeri yazılırsa o ikisini birbirine bağlar; yazıya tıklanınca kutucuk aktifleşir. -->

## Belge Yapısı Nitelikleri

<!-- lang: HTML kök etiketine yazılarak sayfanın hangi dilde olduğunu arama motorlarına ve tarayıcı çeviri araçlarına bildirir.

charset: Meta etiketinde UTF-8 değeriyle kullanılarak Türkçe karakterlerin ve emojilerin bozulmadan görüntülenmesini sağlar. -->
