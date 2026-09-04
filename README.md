### CELSE uygulaması ile doğrudan 3. parti UDF görüntüleyicilerini kullanabilmek için gerekli yama

Android için CELSE uygulaması, UDF dosyaları açmak için Uyap Doküman Editörü uygulamasının da cihazda yüklü olmasını şart koşuyor.  

Evrak gibi 3. parti bir UDF görüntüleyici kullananlar, cihazlarında başka bir UDF görüntüleyici yüklü olmasını istemeyebilirler. İşte [UDF_yama.apk](https://github.com/symbuzzer/UDE_stub/releases/latest/download/UDF_yama.apk) dosyası bu sorunu çözüyor.  

UDF_yama.apk dosyası, tamamen boş (stub) bir Android uygulaması olup, menüde hiç bir şekilde görünmez. İşini yapmak için hiç bir izne ihtiyaç duymaz. Sadece Resmi Uyap Doküman Editörü Android uygulamasının paket adını taklit ederek, CELSE uygulamasının doğrudan 3. parti UDF görüntüleyicilerle sorunsuz çalışmasını sağlar.  

Güvenlik ve gizlilikten emin olmanız için, bu repo ile UDF_yama.apk Android uygulamasının kaynak kodunu paylaşıyorum.

### Nasıl kullanırım?  
Eğer cihazınızdan Uyap Doküman Editörü uygulamasını tamamen kaldırmak ve CELSE uygulaması üzerinden UDF dosyalarını görüntülemeye Evrak uygulaması veya başka bir 3. parti uygulamayla devam etmek istiyorsanız, aşağıdaki adımları sırasıyla gerçekleştirmeniz gerekmektedir:
- Uyap Doküman Editörü uygulamasını cihazınızdan kaldırın.
- [UDF_yama.apk](https://github.com/symbuzzer/UDE_stub/releases/latest/download/UDF_yama.apk) dosyasını cihazınıza indirin ve kurun.

### Bilinen sorunlar
Google Play Store'daki güncelleme ekranında, Uyap Doküman Editörü uygulaması gerçekte yüklü olmadığı halde güncelleme varmış gibi görünür ve güncelleme yapmak istemeniz halinde başarısız olur. Bunun nedeni Play Store'un güncellemeleri kontrol ederken paket adlarını göz önünde bulundurması ve UDF_yama.apk dosyasının Uyap Doküman Editörü uygulaması ile aynı paket adını kullanmasıdır. Bu sorun, güncelleme ekranında hata görünmesi dışında başka bir soruna yol açmadığından, rahatlıkla göz ardı edebilirsiniz.
