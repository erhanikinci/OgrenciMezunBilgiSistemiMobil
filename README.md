# Öğrenci Mezun Bilgi Sistemi Mobil Uygulama

## Gereksinimler
   - Android Studio İDE 
   - SQLite Server
   - JDK 11
   
## Kurulum
   - Kaynak kod, Android Studio IDE'ye import ederek aktarılır.

   - Proje Android Studio IDE ile açılıp build yapılıp çalıştırılır.

   - Açılan Emulator ekranı ya da uygulamaya dışarıdan bağlanan Android cihaz ile run edilir.




## Uygulamanın Yüklenmesi ve Çalıştırılması İşlemi
   - Uygulamayı Google Play Store, Apple Store yada APK dosyasından cihazınıza yükleyerek kullanıma başlayabilirsiniz.

   - Uygulamayı cep telefonuza indirip yüklediğinizde, Aşağıdaki resimde(ekran görüntüsü) görülen icon resmi ile
       cihazınıza yüklenmiş ve çalışır halde görülür.

   - İcon’a tıklandığında uygulama çalışmaya başlayacaktır.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155013861-da599f4d-acff-4478-9183-541d6227d6af.jpg">
</p>


### Başla Ekranı
    - Uygulamaya çift tıklandıktan sonra kullanıcı aşağıdaki gibi bir ekran görüntüsüne erişecektir. Bu aşamada
      kullanıcının Başla butonuna tıklaması gerekmektedir. Başla butonuna tıklandığında kullanıcı giriş ekranına erişecektir.
      
    - Oturum açma ekranında kullanıcıların Android uygulaması ile oturum açması sağlanmaktadır. Aşağıdaki ekranda
      görüldüğü gibi sisteme hangi türden giriş yapacağı seçilmelidir. Default olarak yönetici girişi seçeneği seçilmiş
      olarak gelir. Kullanıcı bu ekranda 2 tür giriş seçeneği ile karşılaşır, “yönetici” ve “fakülte” giriş seçenekleridir.       
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155014581-9b7dd062-6135-48c5-ad4e-bea885adf0f0.jpg">
</p>



### Yönetici Giriş Ekranı
    - Yönetici girişi ile sisteme kullanıcı adı : yönetici, şifre : yönetici123 ile sisteme giriş yapılabilir.
      Sisteme yönetici olarak giriş yapıldığında aşağıda görüldüğü gibi aşağıdaki gibi bir ekran ile karşılaşır.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155014605-2c0135d4-7e15-4e13-ba07-5724d309d196.jpg">
</p>   
 
 

### Yönetici Giriş Ekranı
    - Kullanıcı adı ve şifreyi başarılı bir şekilde yazıp giriş yapıldığında aşağıdaki gibi bir ekran ile karşılaşır. Bu ekranda
      sırasıyla Öğrenci Ekle, Öğrenci Görüntüle, Öğrenci Başına Mevcut Sayı, Fakülte Ekle, Fakülte Görüntüle ve Çıkış butonları
      bulunmaktadır. Yönetici burada Fakülte ekle seçeneği ile sisteme yeni bir kullanıcı tanımlama işlemini başlatabilir.
      Fakülte Ekle butonuna tıklandığında Aşağıdaki gibi bir ekran açılır.  
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155014628-c6300ce8-3bfd-40c6-95a5-a5ffe20e7854.jpg">
</p>  


### Fakülte Ekle Ekranı
    - Aşağıdaki açılan ekranda yönetici sisteme mezun/öğrenci kullanıcı işlemini tanımlayabilir. Bu ekranda kullanıcı bilgileri: isim, soyisim,
      telefon numarası, adres, kullanıcı adı ve şifre bilgilerini doldurarak sisteme kaydını gerçekleştirebilir. Bilgiler doldurulduktan sonra
      kaydet butonuna tıklandığında aşağıdaki gibi kullanıcı başarıyla kaydoldu mesajıyla karşılaşır. 
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155015874-1e34fc32-c603-48bf-9d8f-4ee7d76df594.jpg">
</p>  



### Fakülte Görüntüle Ekranı
    - Aşağıdaki ekranda Fakülte Görüntüle butonuna tıklandığında aşağıdaki gibi bir ekran açılır. 
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155015887-22b0634b-7afa-415c-ba09-50c51bca801c.jpg">
</p>  


### "Fakülte Görüntüle" Mezun öğrencileri görünteleme ekranı
    - Bu ekranda aşağıdaki sisteme daha önceden tanımladığım kullanıcıların Adı ve Soyadı bilgileri yer almaktadır.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155015902-89380ff3-d557-4d98-b641-e0ee123b1d51.jpg">
</p>  



### Fakülte Öğrenci Görüntüleme ekranı
    - Aşağıda görülen ekranda, Öğrenci Görüntüle butonuna tıklandığında Fakülte Öğrenci Görüntüleme ekranı açılır.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155017113-93ee46aa-0936-40b6-9a45-9edf6de9bb9a.jpg">
</p> 



### Hangi fakülte ve hangi yıldaki mezunların bulunması Görüntüleme ekranı
    - Aşağıdaki ekranda çorlu mühendislik fakültesinin 2017 yılındaki mezun ve aktif öğrencilerin görüntülenmesi
      istenildiğinde gönder butonuna tıklanır ve fakülte ile hangi yıldaki mezunların bulunması Görüntüleme gibi bir ekran ile karşılaşılır.
      
    - Gönder butonuna tıklandığında 2017 yılındaki Çorlu Mühendislik Fakültesindeki mezunlar gibi bir ekran açılır.  
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155017465-98390669-1c31-4796-a840-5781e711d138.jpg">
   <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155017850-dcbee194-1594-4f45-8e3d-9feea8b63cab.jpg">
   <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155017894-a1c7d852-83f6-43b9-9e0e-647aab804e95.jpg">
</p> 



### Mezun sisteminden öğrencinin Silinmesi işlemi
    - Aşağıdaki ekranda sisteme daha önceden kayıt ettiğim 2017 yılına çorlu mühendislik fakültesine ait kullanıcıların bilgileri görülmektedir.
      Kullanıcıların üzerine yaklaşık 4 saniye ile tıklandığında aşağıdaki gibi bir seçenek ile karşılaşılır.
      
    - Aşağıda görüldüğü gibi sistemden kullanıcı Silme işlemi gerçekleştirilebilir. Mezun öğrenci bilgi sistemi sil seçeneği ile evet
      butonuna tıklandığında sistemden kullanıcı silme işlemi gerçekleştirilebilir.  
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155017941-9527818a-03a1-4e81-a756-70284fa7a8e8.jpg">
</p>  


### Mezun kullanıcı bilgi sistemi giriş ekranı
    - Sisteme kayıt ettiğim kullanıcı adı ve şifre ile oturum açma işlemi başlatabilir, bu sayfada yönetici yerine fakülte seçeneğinin seçilmiş
      olması gerekmektedir. Aşağıdaki ekranda Mezun kullanıcı bilgi sistemine giriş yapıldığında şekil 16’ da ki gibi bir ekran açılır. 
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155019673-615d9b43-b2bf-42f7-acbb-3c03e1649a6b.jpg">
     <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155019726-3e91cff5-7ab9-4e25-9456-1a82a71e4243.jpg">
</p>  



### Mezun öğrenci Fakülte, yıl ve bölüm eklenmesi
    - Yukarıda görüldüğü gibi katılımcı ekle butonuna tıklandığında mezun öğrenci fakülte, yıl ve bölüm eklenmesi yapılabilir. Bu ekranda
      fakülteler arasında Çorlu mühendislik fakültesi, yıllardan 2017 yılı, bölümlerden ise Bilgisayar Mühendisliği bölümü’ nü seçelim.
      
    - Tarih seçinin butonuna tıklandığında aşağıda görüldüğü gibi kullanıcının hangi tarihte mezun olduğu bilgisi ayarlanabilir ve 
      Tamam seçeneğine tıklandığında aşağıda görüldüğü gibi bir metin kutusu içerisine seçilen tarih basılır.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155019673-615d9b43-b2bf-42f7-acbb-3c03e1649a6b.jpg">
     <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/155019726-3e91cff5-7ab9-4e25-9456-1a82a71e4243.jpg">
</p>  




