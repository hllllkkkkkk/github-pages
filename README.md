# Gizlilik Politikası — Çocuklar İçin Türkçe

**Yürürlük tarihi:** 25 Nisan 2026
**Son güncelleme:** 25 Nisan 2026

Bu uygulama (paket adı `com.minikturkce.app`, bundan sonra "Uygulama"), 3–6 yaş aralığındaki çocuklara Türkçe öğretmek amacıyla tasarlanmıştır. Çocukların gizliliğini ciddiye alıyoruz. Bu politika, Uygulama'nın hangi verileri topladığını, hangilerini toplamadığını ve verilerinizin nasıl işlendiğini açıklar.

## 1. Topladığımız Veriler

Uygulama **kişisel veri toplamaz**. Hesap oluşturmaz, ad, e-posta, doğum tarihi, konum veya iletişim bilgisi istemez.

Uygulama'nın eriştiği veriler:

| Veri | Nerede saklanır | Neden gerekli |
|---|---|---|
| Mikrofon sesi | Cihaz dışına çıkmaz; sadece sistemin konuşma tanıma motoruna iletilir | Çocuğun söylediği kelimeyi tanımak ve puanlamak için |
| İlerleme (yıldızlar, modül durumu, seri gün sayısı) | Sadece cihazda (SharedPreferences) | Çocuğun nerede kaldığını hatırlamak için |
| Anonim cihaz kimliği (UUID) | Sadece cihazda | İlerlemeyi yerel olarak ilişkilendirmek için |
| Çökme raporları | Google Firebase Crashlytics (yalnızca uygulama çöktüğünde) | Hataları bulup düzeltmek için |
| Satın alma bilgileri | Google Play Faturalandırma | Premium içeriği etkinleştirmek için |

## 2. Mikrofon Hakkında

Uygulama, telaffuz alıştırmaları için mikrofona erişim ister. Ses **kaydedilmez, saklanmaz veya sunucumuza gönderilmez** — sadece Android'in yerleşik konuşma tanıma motoruna anlık olarak aktarılır ve metne çevrilir. Cihaz ayarlarınıza bağlı olarak Android, bu metne çevirme işlemini Google'ın sunucularını kullanarak yapabilir; bu Android sisteminin bir özelliğidir, Uygulama'nın değil.

## 3. Verilerinizi Kimseyle Paylaşmıyoruz

Uygulama:
- **Reklam göstermez.**
- **Üçüncü taraf analiz veya izleme SDK'ları kullanmaz.**
- **Verileri reklamcılık veya pazarlama için satmaz veya paylaşmaz.**

Sadece şu Google hizmetleri çalışır:
- **Firebase Crashlytics** — yalnızca çökme anında, çökme yığınını ve cihaz modelini gönderir. [Google'ın gizlilik politikası](https://policies.google.com/privacy) geçerlidir.
- **Google Play Faturalandırma** — yalnızca satın alma yapıldığında. [Google Play'in gizlilik politikası](https://policies.google.com/privacy) geçerlidir.

## 4. Çocuklara Yönelik Bildirim (COPPA / KVKK / GDPR-K)

Uygulama 13 yaş altı çocuklara yöneliktir. Hiçbir kişisel bilgi toplanmadığı için, hiçbir kişisel bilgi kullanılmaz, satılmaz veya saklanmaz. Ebeveyn izni gerektiren herhangi bir veri toplama yoktur.

## 5. Verilerinizi Silme

Tüm uygulama verisi yereldir. Silmek için:
- Android: **Ayarlar → Uygulamalar → Çocuklar İçin Türkçe → Depolama → Verileri Temizle**, veya uygulamayı kaldırın.

Bu, ilerleme, seri ve anonim cihaz kimliğini siler. Crashlytics çökme raporları otomatik olarak 90 gün içinde silinir.

## 6. Politikadaki Değişiklikler

Bu politikayı güncellersek, "son güncelleme" tarihini değiştiririz. Önemli değişikliklerde uygulama içinde de bilgi vereceğiz.

## 7. İletişim

Sorularınız için: **[YOUR_EMAIL]**

---

# Privacy Policy — Turkish for Kids

**Effective date:** 25 April 2026
**Last updated:** 25 April 2026

This app (package `com.minikturkce.app`, the "App") is designed to teach Turkish to children ages 3–6. We take children's privacy seriously. This policy explains what the App collects, what it does not collect, and how your data is handled.

## 1. Data We Collect

The App **does not collect personal data**. It does not create accounts, and does not ask for name, email, date of birth, location, or contact info.

What the App accesses:

| Data | Stored where | Why it is needed |
|---|---|---|
| Microphone audio | Never leaves the device beyond the system speech recognizer | To recognize and score the child's spoken word |
| Progress (stars, module status, streak days) | On-device only (SharedPreferences) | To remember where the child left off |
| Anonymous device ID (UUID) | On-device only | To associate progress locally |
| Crash reports | Google Firebase Crashlytics (only when the app crashes) | To find and fix bugs |
| Purchase info | Google Play Billing | To enable premium content |

## 2. About the Microphone

The App requests microphone access for pronunciation exercises. Audio is **not recorded, stored, or sent to our servers** — it is streamed in real time to Android's built-in speech recognition engine and converted to text. Depending on your device settings, Android may perform this transcription using Google's servers; that is a feature of the Android system, not the App.

## 3. We Do Not Share Your Data

The App:
- **Shows no ads.**
- **Uses no third-party analytics or tracking SDKs.**
- **Does not sell or share data for advertising or marketing.**

The only Google services in use:
- **Firebase Crashlytics** — sends a stack trace and device model only when a crash occurs. Subject to [Google's Privacy Policy](https://policies.google.com/privacy).
- **Google Play Billing** — used only when a purchase is made. Subject to [Google Play's Privacy Policy](https://policies.google.com/privacy).

## 4. Notice for Children (COPPA / GDPR-K)

The App is directed to children under 13. Because no personal information is collected, none is used, sold, or stored. There is no data collection requiring parental consent.

## 5. Deleting Your Data

All app data is local. To delete:
- Android: **Settings → Apps → Turkish for Kids → Storage → Clear Data**, or uninstall the app.

This removes progress, streaks, and the anonymous device ID. Crashlytics crash reports auto-delete within 90 days.

## 6. Changes to This Policy

If we update this policy, we will change the "last updated" date. For material changes, we will also notify you in-app.

## 7. Contact

Questions: **[YOUR_EMAIL]**
