TEDAŞ CANLI KAMERA - ANDROID STUDIO PROJESİ

Bu paket, yüklediğiniz HTML uygulamasını Android WebView içinde açan Android Studio projesidir.

APK oluşturma:
1. Bilgisayara Android Studio'yu kurun.
2. Android Studio > Open ile bu klasörü açın.
3. Gradle senkronizasyonunun bitmesini bekleyin.
4. Build > Build Bundle(s) / APK(s) > Build APK(s) seçin.
5. APK, app/build/outputs/apk/debug/app-debug.apk konumunda oluşur.

Uygulama:
- Kamera izni ister.
- HTML içindeki Gemini API ayarını kullanır.
- API anahtarı uygulamanın WebView yerel depolamasında tutulur.
- Görüntü analizi için internet bağlantısı gerekir.

Önemli:
- İlk kullanımda ⚙️ API bölümüne kendi Gemini API anahtarınızı girmeniz gerekir.
- API anahtarınızı başkalarıyla paylaşmayın.
- Kamera ile görüntü yalnızca uygulamanın yaptığı Gemini isteği kapsamında gönderilir.
- Bu çalışma klasörü APK dosyası değil, APK üretmeye hazır Android Studio kaynak projesidir.
