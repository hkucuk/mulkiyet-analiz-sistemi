# Mülkiyet Analiz Sistemi - MAS

Tapu ve Kadastro Genel Müdürlüğünün anlaşmalı olduğu paydaşları (Belediyeler, Kamu Kurum ve Kuruluşları) ile web servisleri üzerinden paylaştığı verilerin en doğru ve hızlı bir biçimde kullanılmasını sağlayan tamamen özgür bir yazılımdır.


## Genel Özellikler
- Yetki alanı içerisinde tapu kaydı sorgulama ve raporlama
-  İl, ilçe, mahalle ve ada parsel bazında sorgulama ve raporlama
- Gerçek ve Tüzel Kişi Bazında Sorgulama ve  raporlama,
- Şerh, Beyan, İrtifak, Muhdesat sorgulama ve  raporlama,
- Harita ekranı üzerinden TKGM verisi Sorgulama ve raporlama ve, TKGM verisi (MDB,SHP,DXF .. vb) indirme işlemi yapılabilir.
- Ücretsiz Altlık Haritaların (GoogleMap .. vb) kullanımı ile doğrulama ve analiz yapabilir
- Ücretsiz Altlık Haritaları, Koordinatlı veya Koordinatsız Raster olarak indirerek CAD veya GIS uygulamalarında kullandırma
- TKGM servislerinden gelen verileri, analiz ve planlama için hazır veri olarak (İmar Dağıtım Dosyası ve Geometrik Analizler.. vb) kaydederek gerek olmadıkça veri işçiliğinden zaman kazandırır.
- Harita ekranı üzerinde çizim, hesap ve arama imkânı sağlar.
- MAS harita, kadastro, tapu, geo raster ve ayarlar modüllerinden oluşur


## Harita Modülü
Bu modülde ;
-  Temel navigasyon işlemleri (Yakınlaş, uzaklaş, kaydırma, önceki ve sonraki ekran ),
- Google, Bing, OSM gibi online haritaları görüntüleme,
- Mahalle,ada parsel gibi kadastro haritaları katman olarak görüntülenebilir,
- Çizim ve ölçüm işlemleri, 
- Adres sorgulama (geocoding), 
- Enlem boylam ile koordinata git işlemleri yapılabilir.

![MAS - Harita Modülü](https://github.com/tapukadastro/mulkiyetanalizsistemi/blob/master/screens/harita-modulu-small.png?raw=true)
## Kadastro Modülü

Bu modülde;
- Kullanıcının yetki alanı dahilinde TKGM tarafından yayınlanan WMS ve WFS servislerine erişip sorgulama ve görüntüleme işlemleri, 
- Ekranda görüntülenen alanda, seçilen kriterlere göre parseller üzerinde filtreleme ve analiz,
- Tıklanan nokta ile kesişen parsel öznitelikleri görüntüleme,
- Seçili alana ait veriyi farklı formatlarda indirme 
- İmar dağıtım verisi (NIV) indirme işlemleri yapılabilir.

![MAS - Kadastro Modülü](https://github.com/tapukadastro/mulkiyetanalizsistemi/blob/master/screens/harita-modulu-small.png?raw=true)
## GEO Raster Modülü
CAD veya GIS uygulamalarında internet bağlantısına ihtiyaç duymadan ücretsiz altlık haritaların koordinatlı Raster olarak kullanılmasını sağlar. Görüntülenen harita ekranını, sol üst köşe ve sağ alt köşe koordinatları girilerek koordinatların kapsadığı alanı veya harita ekranından seçilen alanı koordinatlı veya koordinatsız Raster olarak indirme imkânı sağlar

![MAS - Geo raster modülü](https://github.com/tapukadastro/mulkiyetanalizsistemi/blob/master/screens/georaster-modulu-small.png?raw=true)

## Tapu Sorgu Modülü
Web Servisleri üzerinden alınan tapu bilgilerinin tüm fonksiyonlar kullanılarak sorgulanması ve raporlanmasını sağlar. Temel olarak üç sorgu tipi vardır. Bunlar Taşınmaz, Kişi veya Gerçek Kişi sorgularıdır. Ancak bu üç temel sorgulama yönteminin her biri için birden fazla kriterde sorgu yapmak mümkündür. Bu modülde temel kullanımlar için Basit sorgulama, çok amaçlı kullanımlar için ise gelişmiş sorgulama imkanı sağlanmıştır.

![MAS - Tapu Sorgu Modülü](https://github.com/tapukadastro/mulkiyetanalizsistemi/blob/master/screens/tapu-mod%C3%BCl%C3%BC-small.png?raw=true)

## Tapu Analiz Modülü
Web Servisleri üzerinden alınan tapu bilgilerinin, tüm fonksiyonlar kullanılarak listelenmesini ve indirilmesini sağlar.
![MAS - Tapu Analiz Modülü](https://github.com/tapukadastro/mulkiyetanalizsistemi/blob/master/screens/tapu-analiz-small.png?raw=true)
