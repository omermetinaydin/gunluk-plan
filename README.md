# Günlük Plan (Android)

Tasarım `app/src/main/assets/index.html` içinde; uygulama onu bir WebView'da açar.
Görevler telefonda saklanır, her gün sıfırlanır.

## APK almak (kurulum gerektirmez)
1. github.com'da bir depo oluştur, bu klasörün içindekileri yükle (`.github` klasörü dahil).
2. Depoda Actions sekmesi → Build APK → Run workflow.
3. İş bitince Artifacts bölümünden GunlukPlan-apk dosyasını indir, zip'ten çıkan app-debug.apk dosyasını telefona at ve yükle.

Yeni sürümü yüklemeden önce eski uygulamayı sil (her derlemede imza değişir).

## Özellikler
- Tamamlayınca 3,5 saniye "Geri al"
- Tamamlarken hafif titreşim, hepsi bitince çift titreşim
- Outfit yazı tipi derleme sırasında indirilip uygulamaya gömülür
