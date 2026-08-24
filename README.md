### Celse uygulaması ile doğrudan 3. parti UDF görüntüleyicilerini kullanabilmek için gerekli yama

Android için Celse uygulaması, UDF dosyaları açmak için Uyap Döküman Editörü uygulamasının da cihazda yüklü olmasını şart koşuyor.  

Evrak gibi 3. parti bir UDF görüntüleyici kullanananlar, cihazlarında başka bir UDF görüntüleyici yüklü olmasını istemeyebilirler. İşte [UDF_yama.apk](https://github.com/symbuzzer/UDE_stub/releases/latest/download/UDF_yama.apk) dosyası bu sorunu çözüyor.  

UDF_yama.apk dosyası, tamamen boş (stub) bir Android uygulaması olup, menüde hiç bir şekilde görünmez. İşini yapmak için hiç bir izne ihtiyaç duymaz. Sadece Resmi Uyap Döküman Editörü Android uygulamasının paket adını taklit ederek, Celse uygulamasının doğrudan 3. parti UDF görüntüleyicilerle sorunsuz çalışmasını sağlar.  

Güvenlik ve gizlilikten emin olmanız için, bu repo ile UDF_yama.apk Android uygulamasının kaynak kodunu paylaşıyorum.
