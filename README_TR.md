# Study Tracker

Bu proje, Android için çevrimdışı çalışan bir çalışma takip uygulamasının kaynak kodudur.

## Özellikler
- 1–15 günlük döngü oluşturma
- Döngü günlerine görev ekleme
- Günlük görevleri işaretleme
- Tamamlanmayan görevleri sonraki güne taşıma
- 0–3 değerlendirme sistemi
- 1 puan verilen tamamlanmış görevleri Stack bölümünde tutma
- Not ekleme, düzenleme ve silme
- Verileri cihazdaki SQLite veritabanında saklama

## APK oluşturma
1. Android Studio'yu kur.
2. Bu klasörü Android Studio'da `Open` ile aç.
3. Gradle senkronizasyonunun tamamlanmasını bekle.
4. `Build > Build Bundle(s) / APK(s) > Build APK(s)` seç.
5. APK, `app/build/outputs/apk/debug/` klasöründe oluşur.

Bu proje internet bağlantısı olmadan uygulama çalışırken veri senkronizasyonu yapmaz. İlk derleme için Android Studio gerekli bağımlılıkları indirebilir.
