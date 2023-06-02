# c-sharp-belge-yonetim-sistemi-1
BELGE ARŞİV YÖNETİM SİSTEMİ



Hedef kitlenin ihtiyaçları doğrultusunda yapılan içerik analizinde uygulama kullanıcıların kolayca adapte olabileceği; sade ve anlaşılır biçimde tasarlanıp uygulamanın görsel kısmı kullanışlı ve açık olacak şekilde dizayn edilecektir.

Uygulamamızda;
•	Evrak isimlerine göre arama
•	Departman isimlerine göre arama
•	Türe göre arama
•	Yeni evrak kaydı
•	Kullanıcı kayıt silme/ekleme
•	Evrak emanet alıp/verme
•	Personel kayıt silme/ekleme

 bulunacaktır.
 
 
 KULLANICI ANALİZİ:
Sisteme erişim sağlayabilecek olan kullanıcılarımız arşiv görevlilerimizdir.


•	Kullanıcıların evraklar ile ilgili bilgileri doldurarak arşive kayıt oluşturabilmeleri.
•	Kayıtlı evrakın emanet verilebilmesi.
•	Emanet verilmiş evrakların listelenmesi.
•	Arşivde bulunan evrakların yıl, dönem ve ay bazında listelenmesi.
•	Arşivde bulunan evraklarda arama işlevi yapılması.
•	Arşivde bulunan evraklar ile ilgili istatistikler.




Evrak işlemlerinin bilgisayarlı arşiv ortamı içerisine alınması için uygun bir çözüm sistemi modeli düşünüldü. Bu çalışma ile konuya ait işlemler tespit edilecek ve ana hatlarıyla bir hiyerarşi içerisinde yerleştirilerek işlem menüleri oluşturulacaktır. İşlem menüleri çalıştırıldığında veri alış verişini sağlayacak ekran formları tasarlanacaktır. Daha sonra ekran formları aracılığıyla okunacak veya yazılacak verilerin saklanacağı veri tabanı dosyaları tasarlanacaktır. Son aşamada kullanıcı, ekran formu, veri ve dosyalar arasındaki iş akışını ve koordinasyonu sağlayacak, bilgisayar ile kullanıcı arasında iletişim kuracaktır.

SİSTEM MİMARİSİ 
•	Ana Form
•	Evrak Listesi Formu
•	Kullanıcı Listesi Formu
•	Emanet Lisesi Formu
•	İstatistikler Formu
•	Personel Formu
•	Ayarlar Formu




İŞLEVSEL GEREKSİNİMLER
   Bu uygulama;
•	Mevcut evrak bilgilerini,
•	Yeni evrak bilgilerini,
•	Kullanıcı bilgilerini,
•	Emanet verme bilgilerini,
•	Teslim alma bilgilerini
İçermelidir.



Aktör: 
Yetkili personel (Fakülte sekreteri)                                
      Tanım:
•	Kullanıcı ekle-sil işlemlerini yapar.
•	Evrak ekle-sil işlemlerini yapar.
•	Teslim alma işlemlerini yönetir.
•	Kullanıcı Listesi’ne erişim sağlar.
•	Evrak Listesi’ne erişim sağlar.  (ay, dönem ve yıl bazında)
•	Arşivde bulunan evraklarda arama işlevine erişim sağlar.
•	Arşivde bulunan evraklar ile ilgili istatistikler bulundurur.

   İŞLEVSEL OLMAYAN GEREKSİNİMLER
•	Proje geliştirme ortamı: C#
•	Projenin kullanılacağı bilgisayar: Her bilgisayarda kullanılabilir bir sistem.

KULLANICI ARAYÜZLERİMİZ AŞAĞIDA ÖRNEKLENMİŞTİR;

UYGULAMAYA İLK GİRİŞ YAPTIĞIMIZDA BİZİ AŞAĞIDAKİ EKRAN KARŞILAR.
![Screenshot_6](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/9c6d03e0-52ff-4a88-b18c-829a5adc563f)


KULLANICI GİRİŞ SAYFASI 
![Menü1](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/1e951e15-d0f8-4b51-98a4-4f54aea1c197)


KULLANICI EVRAK SORGULAMA SAYFASI
![Screenshot_2](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/ffd0d209-7cd7-4a64-b7ed-d8b23fb18c7a)


KULLANICI EMANET LİSTESİNİ AŞAĞIDAKİ GİBİ GÖRÜNTÜLEYEBİLİR.
![Screenshot_3](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/6235234e-1cb6-4f6c-aff6-8cfb468cb1b8)


KULLANICI EVRAK SORGULAMA İŞLEMİ AŞAĞIDAKİ EKRANDAN YAPILIR.
![Screenshot_4](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/bcc8fb2e-a238-42ec-80f8-7f39ccdcc8da)


TÜM KULLANICILAR UYGULAMAYA YÖNELİK İSTATİSTİKLERİ AŞAĞIDAKİ EKRANDAN GÖRÜNTÜLEYEBİLİR.
![Screenshot_5](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/950e0154-d5c8-45c9-9f2c-9fcff30c62eb)


FAKÜLTE SEKRETERİNE AİT DİĞER KULLANICILARDAN FARKLI İŞLEMLERİN YAPILABİLDİĞİ EKRAN AŞAĞIDA GÖSTERİLMİŞTİR.
![Screenshot_7](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/6ce1533e-180a-491c-8c69-9600d87165a0)


FAKÜLTE SEKRETERİ YENİ KULLANICI EKLEME - SİLME , KULLANICI LİSTELERİ VE DETAYLARINA AŞAĞIDAKİ EKRANDAN ULAŞABİLİR.
![Screenshot_8](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/e9ed66bd-319c-40ce-b5f6-264b683df27e)


FAKÜLTE SEKRETERİ PERSONEL SORGULAMA , EKLEME - SİLME YA DA DİĞER BİLGİLERİNE AŞAĞIDAKİ EKRANDAN ULAŞIR. 
![Screenshot_9](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/99525fc7-b167-404c-85b0-7253f0cb51e7)


EVRAK EMANET ETME İŞLEMLERİ İÇİN AŞAĞIDAKİ EKRANI KULLANABİLİRİZ.
![Screenshot_10](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/1988f718-4aa5-4fc1-9719-3e56a5f1dcdb)


EVRAK EMANET TESLİM İŞLEMLERİ İÇİN AŞAĞIDAKİ EKRANI KULLANABİLİRİZ.
![Screenshot_11](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/8901f7ba-d886-40b7-9cfd-483264747a1b)


İŞLEM GEÇMİŞİNE ULAŞMAK İÇİN AŞAĞIDAKİ EKRANI KULLANABİLİRİZ.
![Screenshot_12](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/6b828c8a-56db-4e4d-93e0-13eb0011ea08)


UYGULAMAYA ADMİN İLE GİRİŞ YAPTIKTAN SONRA AŞAĞIDAKİ EKRANI KULLANIRIZ.
![Screenshot_13](https://github.com/tugceeylcn/c-sharp-belge-yonetim-sistemi-1/assets/92729671/143e8e6e-7fb1-432a-af9a-6ac5c3df45b5)





















