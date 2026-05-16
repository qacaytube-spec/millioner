# 📱 Kim Milyoner Olmak İster? — Android Studio Kurulum Kılavuzu

## Gereksinimler
- Android Studio (ücretsiz): https://developer.android.com/studio
- Windows / Mac / Linux bilgisayar

---

## Adım 1 — Android Studio'yu İndir ve Kur
1. https://developer.android.com/studio adresine gidin
2. "Download Android Studio" butonuna tıklayın
3. Kurulumu tamamlayın (yaklaşık 15 dakika)

---

## Adım 2 — Projeyi Aç
1. Android Studio'yu açın
2. **"Open"** (veya "Open an Existing Project") seçin
3. Bu ZIP'i çıkardığınız klasörü seçin → **MilyonerApp** klasörü
4. "OK" tıklayın
5. Gradle sync otomatik başlar, bitene kadar bekleyin (internet bağlantısı gerekli, 2-5 dk)

---

## Adım 3 — APK Oluştur
1. Üst menüden: **Build → Build Bundle(s)/APK(s) → Build APK(s)**
2. Build tamamlandığında sağ altta "locate" linki çıkar
3. APK dosyası: `app/build/outputs/apk/debug/app-debug.apk`

---

## Adım 4 — Telefona Kur
**USB ile:**
1. Telefonu USB ile bilgisayara bağlayın
2. Android Studio'da ▶️ Run butonuna tıklayın — direkt telefona yükler

**APK dosyası ile:**
1. `app-debug.apk` dosyasını WhatsApp/Drive/USB ile telefona atın
2. Dosyaya tıklayın
3. "Bilinmeyen kaynak" uyarısına "Yükle" deyin
4. ✅ Uygulama kuruldu!

---

## Özellikler
- ✅ Tam ekran (durum çubuğu yok)
- ✅ Ses sistemi çalışır
- ✅ İnternet gerekmez (offline)
- ✅ Ekran her zaman açık kalır (oyun sırasında)
- ✅ Android 5.0+ (Lollipop) ve üzeri desteklenir

---

## Sorun mu var?
Gradle sync sırasında hata alırsanız:
- File → Invalidate Caches → Invalidate and Restart
