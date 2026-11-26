# Günlük Plan (Android)

Tasarım `app/src/main/assets/index.html` içinde; uygulama onu bir WebView'da açar.
Görevler telefonda saklanır, her gün sıfırlanır.

## APK almak (kurulum gerektirmez)
1. github.com'da boş bir depo oluştur, bu klasörün içindekileri yükle (`.github` klasörü dahil).
2. Depoda Actions sekmesi → Build APK → Run workflow.
3. İş bitince sayfanın altındaki Artifacts bölümünden GunlukPlan-apk dosyasını indir, zip'ten çıkan app-debug.apk dosyasını telefona at ve yükle.

## Android Studio ile
Klasörü Android Studio'da aç, Gradle 8.9 ile eşitle, ardından Build → Build APK(s).

Not: Yazı tipi (Outfit) internetten yüklenir; bağlantı yoksa Roboto'ya düşer.
