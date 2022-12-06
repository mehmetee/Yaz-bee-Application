# Yaz-bee-Application
## Yaz-bee instant status
Bu gelişim sürecinmde yaptığım uygulamada  anlık durumların paylaşıldığı ve tüm kullanıcılar tarafından erişim sağlanabilir bir uygulama.
Bu uygulamamızda başlangıç olarak bizi login erkranı karşımıza çıkıyor burda eğer bir üyelik yok ise kayıt ol butonu ile yeni bir kullanıcı oluşturuyoruz,
burada verilerimizi Firebase-Authentication yardımı ile üye kayıt veya giriş form işlemlerini veritabanına kaydediyoruz.
Form ekranında basit düzeyde de olsa belli başlı giriş kontrolleri yapılıyor ve kayıt durumuna göre bize uyarı göndermekte blidirim paneline comminty'nin geliştirmiş oduğu
FlashMessage paketini import ettim , form yapısında ise yine comminty'nin geliştirmis olduğu Formik paketini kullandım. Kullanıcı girişi onaylandıktan sonra bizi paylaşım
yapabildiğimiz ana sayfaya yönlendiriyor burada bizi alt tarafta  paylaşım yapabilmek için msj ekranını önümüze getiren bir buton bulunmakta, üst tarafta ise  uygulamadan 
çıkış butonu bulunmakta.
Durum paylaşmak için oluştutulan message ekranını açtığımızda alttan kayan bir yapı mevcut bu yapıyı  modal paketi ile gerçekleştirdim.
Durum paylaştıktan sonra mesajlarımız dinamik olarak database kaydolur ve görüntülemek içi yine database'den çekeriz bu sayaede uygulamayı oonline olarak kullanılabiliriz.
paylaşımın ne zaman yapıldığını görüntülmek için ve gelen tarih zaman bilgisini formatlamak için date-fns modülünü import ettim bu sayede  daha efeltif bir yapı sağlandı.

https://user-images.githubusercontent.com/44464636/205908891-0e330b41-4f8c-44de-a8d8-8d264aca3815.mp4

