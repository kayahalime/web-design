# web-design
Not: webtasarim.docx dosyasında görsellerle anlatımımı destekledim inceleyebilirsiniz.
WEB TASARIM “CENTRAL PERK” PROJESİ 

![resim](https://github.com/kayahalime/web-design/blob/master/img/sembol4.jpg)

•	“webtasarım” adında bir klasör oluşturdum, tüm dosyalarımı burada tutacağım.
•	VS Code editörünü kullanarak klasörümün içine girdim ve “index.html” adında bir dosya oluşturdum burada anasayfamı düzenleyeceğim.
•	! + Tab ‘a bastığımda dosya içerisinde bizim için gerekli olan yapıyı oluşturuyor.

 
•	Burada body içerisinde içeriğimi ekledim ve içeriğimde neler olacağını belirledim.

•	Head içerisinde ise gerekli css kodlarımı bağladım.
•	Başlangıçta style.css adında bir dosya oluşturdum burada css kodlarım olacak ilk olarak bu dosyayı html sayfama bağladım.
` <link rel="stylesheet" href="style.css">`

•	Style.css’de yaptığımız değişikliklerin daha güzel görünmesini sağlayacağız.

•	Box-sizing değerini border-box olarak verdik. Genişlik ve yükseklik değeri padding ve border değerlerinide içerir.
•	Burada margin ve padding değerlerini boşluk olmayacak şekilde verdik ve background-color ile arka plan rengini belirledik.

•	Sayfanın genel hatlarını ve rengini belirledikten sonra navbar ile ilgili düzenlemeleri yaptık ilk olarak bir div açıp id’sini social olarak verdik style.css’te değişiklilerimizi bu id üzerinden yapacağız. 




•	#social altında navbarımızın daha güzel görünmesi için değişiklikler yaptık. Background-color ile arka planını siyah yaptık ve color ile yazılarımızın ve ikonlarımızın rengini beyaz olarak belirledik. Height ile yüksekliğimizi 55px yaptık ve width ile uzunluğumuzu 100% yaptık yani sayfanın uzunluğunu kaplayacak şekilde. Top:0 yaparak navbarın üst kısma yapışmasını sağladık. Font-size ile yazı büyüklüğünü belirledik ve text-align :right kodu ile textlerin sağa yaslanmasını sağladık.
•	Font bizim başlığımızın olduğu kısım navbarın float:left koduyla navbarın sağ tarafına aldık.
•	Navbarda ikonlarımızı eklemek için font awsome kütüphanesini kullandık.
•	[link](https://fontawesome.com/)  bu siteden ikonlar kısmından ücretsiz ikonları kullanabilirsiniz. Öncelikle bu ikonları kullanabilmem için html sayfamda font awsomeyi dahil ettim.

•	` <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp" crossorigin="anonymous">`
•	Linki yukarıdaki gibidir.

 
 
•	Buradaki ikonlarımı css sayfamda “#social>i “ kısmında düzenledim.
•	Sonrasında container’ı düzenlemeye başladım.
•	Container yardımı ile site yerleşimini içine oluşturacağımız div’i oluştururuz.
 
•	Html kodlarımda bir container div’i oluşturarak içerisine header kısmını yazıyoruz burada bir resim ve başlık ekledim. Burada kullanacağım resim projemin olduğu klasörün içindeki img klasörünün içerinde bulunuyor.
 
•	Burada container’ı şekillendirdim yükseklik uzunluk ve margin kısmını ayarladık.
 
•	Html sayfamızda verdiğimiz id ile css sayfamızda düzenlemeleri yaptık, yüksekliği ve boyutu ayarladık.
 
•	Resmimizi ekleyip konumunuz şekillendirdikten sonra sectionumuzu düzenlemeye geçiyoruz.
 

•	Html sayfasında bir liste oluşturdum ve her maddeyi bir sayfaya bağladım index.html dışındaki sayfaları tek tek oluşturacağım.
 
•	Menünün içinde olacağı sectionu css ile düzenledim. Buradaki border-top-left-radius ve -right-radius kodları sectionun kenarlarının oval olmasını sağlar. Box-shadow ile etrafını gölgelendirdik. 
 
•	Css kodları ile menü görünümünü daha güzel hale getiriyoruz.
 
•	Listeye a etiketi eklediğimizde yazı mavi oluyor ve altı çizili oluyor bu durumu düzeltmek için list-style-type:none olarak ayarladık.
•	Konumunu ve renklerini daha önceki gibi ayarladık ancak burada nav li a:hover kısmı var burada Mouse ile liste elemanı üzerine gittiğimde arka plan rengi gri ve yazının beyaz olması durumunu ayarladık.
 
•	Burada yazıların yanına menüdeki ikonlarımızı dahil ettik(font awsome kütüphanesi ile)
 

•	Sonrasında içerik kısmını düzenlemeye başladım.
 
•	Html sayfasında her bir içeriğimi koyacağım içerik classları oluşturdum yapı olarak resim altında başlık ve onun altında içeriği anlatan metin olacak şekilde ayarladımve altına da bir buton ekledim css kodlarıyla konumlarını ve görüntülerini düzenledim.
 
•	İçeriklerim main içinde olacağı için ilk olarak maini konumlandırdım ve içerik classıyla oluşturduğum divleri konumlandırdım daha önce kullandığım yöntemlerle. Burada farklı olarak resim kısmında transition:opacity 0.8s; kodunu kullandım burada Mouse zerine geldiğimizde opaklık 0.8 saniyede düşecek sekilde ayarladık(.rsm:hover içerisinde opaklığı düşürdük)
 


 
•	Sorasında diğer html dosyalarımıda oluşturmaya başladım yapı olarak index.html ile aynı ancak sadece içerik kısımlarını değiştirdim ve aynı yöntemleri uyguladım.
•	İletişim sayfasında farklı yöntemler kullandığım için o sayfa üzerinden anlatmaya devam edeceğim.
 

•	İlk olarak başlığımızı oluşturduk h1 etiketiyle oluştruduğum için css sayfasında düzenlemelerimi o şekilde yaptım(tüm sayfalardaki başlığımı h1 ile oluşturdum.
 
•	Başlığın konumunu ve renklerini bu şekilde düzenledim.
•	Sonrasında haritayı oluşturmak için Google maps’e gittim ve oradan central parkın adresini aradım adresi paylaş butonuna tıkladığımızda bir ekran geliyor orada html kodlarına tıkladım ve html kodunu kopyaladım.
 
•	Bu şekilde başlığımın altına yapıştırdım ve css sayfasında gerekli düzenlemeleri yaptım.
 
•	Sonrasında form kısmımı oluşturmaya başladım.

 
•	Adresimi ve formumu section içinde konumlandırdım ancak daha önce başka sayfada da section kullandığımdan dolayu buradaki sectionda değişiklik yapabilmem için classını section1 yaptım. Burada label ve input alanı tek bir satır olucak bu yüzden her bir label ve inputumu row divlerinin içerisine aldım. Mesaj için daha büyük bir alana ihtiyaç duyacağımız için textarea kullandım. Placeholder ile text-boxların içine yazılar yazdım.
 
•	Burada aynı yöntemler ile konumları ve boyutları belirledik(col25 alanın %25ini kaplayacak kısım ör: Adınız kısmı %25’ini kaplar text-box kısmı %75ini kaplar)
•	Son olarak adres kısmını oluşturdum.
 
•	Burada alanları span ile oluşturdum ve css kısmında düzenleme yapacağım için classlarını span1 olarak adlandırdım.
 
•	Font-family ile yazı tipini belirledim.



























