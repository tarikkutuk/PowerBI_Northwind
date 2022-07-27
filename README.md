# PowerBI_Northwind
Northwind veri tabanını kullanarak oluşturduğum bazı gösterge örnekleridir. "Şu da olsa iyi olabilirdi" dediğiniz göstergeler için iletişime geçerseniz sevinirim.

Bilindiği üzere Northwind veri tabanının web'de bir çok versiyonu bulunmaktadır. Benim kullandığım parçası 04.08.1994 ile 05.06.1996 tarihleri arasındaki parçadır. Dosyalarda bu veri tabanını bulabilirsiniz.


**Müşteri başına sipariş sayısı:** Bu sayfada şirketin verilen tarih aralığındaki sipariş sayısı, siparişlerden elde edilen ciro verilmiştir.

Sol üstteki haritada şirketin müşterilerinin bulunduğu ülkeler verilirken, haritadaki balonların boyutu ve renkleri o ülkedeki müşterilerin verdiği sipariş sayısıyla 
orantılıdır.

Sayfanın sağ tarafındaki Ağaç Haritası ise yine müşterilerin ülkelerini vermektedir fakat bu haritada hiyerarşik şekilde o ülkedeki müşteri firmaların adına ve daha 
sonra da seçim yapılmak sureti ile müşteri firmanın sipariş sayısına ve şirketin cirosu gösterilebilmektedir.

Ciro göstergesinin hemen yanından ise müşteri firmanın hangi ülkeden olduğu bilinmediği durumlar için firmaların isim listesi verilmiştir. Bu listeden seçilerek de aynı 
bilgilere ulaşılabilir.


**Sipariş detay:** Bu sayfada da bir öncekine benzer şekilde sipariş sayısına göre bir ağaç haritası verilmiştir.
Fakat bu sefer bu ağaç haritasında müşteri firmalardan sonra firmanın sipariş numarasına ulaşılabilmektedir. Dilenen sipariş numarası seçildiği zaman ise alttaki tabloda
bu siparişe ait detay bilgiler görüntülenir. Bu bilgiler firma adı, sipariş numarası, sipariş tarihi, sipariş edilen ürün adı, adeti, indirim oranı, ürünlerin birim fiyatı
siparişin teslim edildiği tarih, sipariş edilme süresi (gün bazında) verilmiştir. Tablonun hemen yanında ise bu siparişlerin cirosu verilmiştir. 
Dilenirse sipariş numarası ile filteleme yapılabilmesi için tablonun hemen yanında bir filtre paneli bulunmaktadır. 

**Sipariş-Stok durumu:** Bu sayfada ise solda şirketin tüm ürünlerinin stok bilgisi bulunmaktadır. 

Ürünlerin stokta olan miktarlarına karşılık, sipariş edilen miktarları 
görülebilir. 

Soldaki ilk filtreleme panelinden siparişte olan ürünler için "In Order", siparişi olmayan ürünler içinse "Out Order" seçilmelidir. 

Siparişi olup stoğu yetersiz ürünleri görmek içinse ikinci filtreleme panelinden "Off Stock", stoğu yeterli ürünler içinse "On Stock" seçilmelidir. 

Solda ortadaki çoklu kartta ise ürünlerin tedarikçi bilgileri yer almaktadır. Bu kart örneğin siparişi olup stoğu olmayan bir ürün seçildiğinde bu ürünün tedarikçi
bilgilerine ulaşabilmek için vardır. Bu tedarikçi bilgileri, tedarikçi şirketteki iletişim kurulan kişinin adı, bu kişinin ünvanı, tedarikçi şirketin adı, şirketin
ülkesi, şehri ve adresi, telefon numarası ve tedarikçi numarasıdır.

Sol altta ise tedarikçilerin konumuna yönelik bir harita yer almaktadır. Haritadaki balonların boyutları, firmanın Northwind'e tedarik ettiği ürün sayısıyla orantılıdır.

**Ürün-Tedarikçi ve Müşteri bilgileri:** Bu sayfada ise şirketin sattığı ürünlerin bilgisine yönelik göstergeler bulunmaktadır.

Ağaç haritası Northwind'in ürünlerinin kategorilerini vermektedir. Haritadaki kutu boyutları ise bu kategorilerdeki ürün sayısıyla orantılıdır. Kutuların altında ise
kategorilerin kısa açıklamaları verilmiştir. Dilenirse bu ağaç haritasındaki bir kategori seçilebilir veya hiyerarşik olarak inildiğinde ise kategorilerdeki ürünlerin
saklama birimleri görülebilir. Bu sayede depo personeli istediği birimdeki ürünlere ulaşabilirken, isterse de kategoriyi tek seçerek o kategorideki tüm ürünlerin 
listesine ulaşabilir. 

Alttaki tablo ürünlerin özelliklerine yöneliktir. Bu tablodan ürünlerin kategori adına, ürün adına, saklama birimine, birim fiyatına, ürünün siparişte olup olmamasına,
siparişteki ürünlerin adetlerinin yeterlilik durumuna ve ürün sayımının yapılıp yapılmamasına ulaşılabilir.

Sağdaki kartlarda üstteki kartta seçilen ürünün tedarikçi bilgilerine ulaşılabilir. 

Sağdaki kartlarda alttaki kartta seçilen ürünün gönderildiği müşteri bilgilerine ulaşılmaktadır.  

Örneğin Seafood kategorisi seçildiğinde (deniz ürünleri ve balıklar) bu kategorideki ürünlerin bilgilerine ulaşılabilir. Bu ürünlerden herhangi biri de tablodan
seçilerek tedarikçi ve müşteri bilgilerine ulaşılabilir.


**Kargodaki ürünler:** Bu sayfada ise kargoya verilmiş, fakat henüz müşterilere teslim edilmemiş siparişler verilmiştir. (Veride sipariş oluşturulmuş fakat henüz kargoya verilmemiş hiç sipariş bulunmamaktadır. Bu sayfanın aynısı henüz kargoya da verilmemiş ürünler için oluşturulabilir)

Tabloda kargoya verilen siparişlerin, sipariş tarihi, sipariş numarası, siparişteki ürünlerin kategorileri, ürün kodları, siparişi veren müşterinin kodu, ürünün 
kategori ismi, ürün isimleri, ürünlerin saklama birimleri ve müşteri firma isimleri verilmiştir. Tablodan herhangi bir ürün seçildiğinde ise alttaki kartlardan 
soldakinde ürünün teslim edildiği kargo şirketi adı, sağdaki kartta ise siparişi veren firmanın iletişim bilgileri yer almaktadır. 

Son olarak **Çalışanların sipariş sayıları** sayfasında ise tarihe göre çalışanların sipariş sayıları verilmiştir. Soldaki filtrelerde çalışanların ünvanı ile birlikte 
tam isimleri verilmişitir. Bu filtreden istenilen çalışan seçilerek, çalışanın tarih bazında sipariş sayısı grafiğine ulaşılabilir. Bir çalışan seçildiğinde ise 
alttaki kartta bu çalışana ait bilgiler görülmektedir.
En alttaki kart ise bu çalışanın şirkete kazandırıdığı ciro verilmiştir.

Oluşturulan Sütunlar: 

Employees tablosu;

FullNamesofEmployees: Çalışanların ünvanı ile birlikte tam ismini veren bir sütun

Invoices tablosu;

Order-Shipped Differance: Sipariş tarihi ile teslim tarihi arasındaki fark (gün)

Order Details tablosu; 

Profit: Siparişten elde edilen ciro;

Orders tablosu;

ActiveOrder: Sipariş verilmiş fakat henüz kargoya teslim edilmemiş siparişleri belirten bir sütun

RequiredOrder: Kargoya teslim edilen fakat henüz müşteriye ulaşmamış ürünleri belirten bir sütun

Product tablosu;

OutStockOrder: Sipariş edilen ürün miktarının, stokta olan ürün miktarından az olduğu durumları belirten bir sütun

ProductInOrder: Siparişte olan ürünleri belirten bir sütun

Suppliers tablosu;

FullAdress: Tedarikçilerin tam adresini veren bir sütun


Oluşturulan Değerler;

Total Profit: Oluşturulan Profit sütunundaki değerlerin toplamı





Önerilere açığım. Eğer "bu göstergede şu olsa daha güzel olurdu veya şunun göstergesini de eklemelisin" gibi önerileriniz olrsa lütfen iletişime geçin.

Linkedin.com/in/tarık-kütük
