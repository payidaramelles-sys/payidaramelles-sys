### Merhaba 👋

[English](README.md) · **Türkçe**

**Windows** ve **Linux** için küçük, dürüst açık kaynak araçlar ve bağımsız oyun projeleri geliştiriyorum. Büyük iddialar yerine ne yaptığını gösteren, ne yapamadığını saklamayan işler.

---

#### 🔧 Açık Kaynak Araçlar

| Proje | Platform | Özet |
|---|---|---|
| **[Sentinel](https://github.com/payidaramelles-sys/sentinel-av)** | Windows (.NET 8) | Windows'ta Defender'ın yanında çalışan hafif tarama ve izleme katmanı (İndirilenler/`%TEMP%` izleme, DPAPI şifreli karantina, YARA-X/ClamAV, AppLocker güven listesi). |
| **[win-port-audit](https://github.com/payidaramelles-sys/win-port-audit)** | Windows (PowerShell) | Sıfır bağımlılıklı, salt okunur port denetleyici; dinlemedeki TCP/UDP portlarını, süreçleri ve Authenticode imzalarını kontrol eder. |
| **[win-startup-audit](https://github.com/payidaramelles-sys/win-startup-audit)** | Windows (PowerShell) | Sıfır bağımlılıklı, salt okunur başlangıç denetleyici; `Run`/`RunOnce`, Başlangıç klasörleri ve Microsoft dışı Zamanlanmış Görevleri imza/eksik dosya açısından tarar. |
| **[Hafif TV](https://github.com/payidaramelles-sys/hafif-tv-launcher)** | Android TV (Java) | 950 MB RAM'li projeksiyon cihazları için tek Activity'li, sıfır bağımlılıklı launcher (382 KB APK, 30 MB PSS, 629 ms soğuk açılış). |
| **[xbox-bt-fedora](https://github.com/payidaramelles-sys/xbox-bt-fedora)** | Linux / Fedora | Bluetooth Xbox kontrolcüsünde Steam Input ve titreşimi tek udev kuralıyla düzelten araç. |
| **[steam-ntfs-library](https://github.com/payidaramelles-sys/steam-ntfs-library)** | Linux / Steam | NTFS disk bölümünü Proton'u bozmadan Linux'ta Steam kütüphanesi olarak kullanma scriptleri. |

#### 🎮 Oyun ve Topluluk Projeleri

- **[Karanlık Taht](https://github.com/payidaramelles-sys/karanlik-taht)** — Tarayıcıda oynanan çok oyunculu RPG projesi ([oyunu aç](https://taht.mehmetacar.org)).
- **[BonkMentor](https://github.com/payidaramelles-sys/BonkMentor)** — Megabonk için yükseltme ve eşya seçim danışmanı (derlenmiş mod paketi).

---

#### 💭 Önemsediklerim

- **Dürüstlük ölçülebilir olmalı.** "Ne yapmaz" bölümü, "ne yapar" kadar önemli.
- **Varsayılan ayar güvenli olmalı.** Salt okunur veya `dry-run` varsayılan — kullanıcı bir şey değişmeden önce görmeli.
- **Tek kişilik projeler de ciddi olabilir** — test, CI, lisans ve güvenlik politikası dahil.

---

#### 📬 İletişim

- 🌐 [mehmetacar.org](https://mehmetacar.org)
- 🐞 Hata bildirimi ve öneriler: ilgili deponun **Issues** sekmesi
- 🔐 Sentinel güvenlik açığı: herkese açık issue açmayın; depodaki `SECURITY.md` yolunu izleyin
