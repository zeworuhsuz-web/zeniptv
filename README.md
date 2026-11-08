# 🌟 ZenIPTV - Extreme Cinema & IPTV Player (Windows v1.0.1)

Modern, ultra akıcı ve profesyonel Windows IPTV, Film ve Dizi Oynatıcı. Özel yerel HLS akış motoru (`ZenPlayer`), dahili `Playerjs (v22.3.6)` entegrasyonu ve obsidyen OLED sinema temasıyla donatılmıştır.

---

### 📦 Doğrudan İndirme Linkleri (v1.0.1 Direct Downloads)

| Sürüm | Tür | Dosya / İndirme Linki |
|---|---|---|
| **ZenIPTV Portable** | ⚡ **Kurulumsuz (Tıkla Direkt Açılsın)** | [ZenIPTV-1.0.1.exe İndir](https://github.com/zeworuhsuz-web/zeniptv/releases/download/v1.0.1/ZenIPTV-1.0.1.exe) |
| **ZenIPTV Setup** | 🚀 **Kurulumlu / Windows Entegrasyonlu** | [ZenIPTV-Setup-1.0.1.exe İndir](https://github.com/zeworuhsuz-web/zeniptv/releases/download/v1.0.1/ZenIPTV-Setup-1.0.1.exe) |

---

### 🏪 Microsoft Store Win32 Gönderim Parametreleri
- **Installer URL:** `https://github.com/zeworuhsuz-web/zeniptv/releases/download/v1.0.1/ZenIPTV-1.0.1.exe`
- **Silent Install Parameters:** `/S`
- **Silent Uninstall Parameters:** `/S`
- **Install Return Codes:** `0`

---

## 🚀 Öne Çıkan Özellikler

1. **Çift Motorlu Oynatıcı Mimarisi**:
   - **ZenPlayer (Özel Dahili Motor)**: Düşük gecikmeli yerel HLS oynatıcı, canlı yayınlarda donma ve geri atlama engelleme, otomatik Türkçe dublaj / orijinal ses ve altyazı parça tarayıcısı.
   - **Playerjs (v22.3.6)**: Playerjs web oynatıcısı, yerleşik medya kontrolleri ve HLS desteği.
   - Oynatıcı açıkken üst bardaki hızlı buton ile motorlar arasında anında tek tıkla geçiş.

2. **Gelişmiş Favoriler Sistemi**:
   - Canlı TV, Film ve Dizileri tek tıkla favorilere ekleme.
   - Ayrı "Favorilerim ⭐" sekmesiyle tüm favori içerikleri filtreleme ve hızlı erişim.

3. **Xtream & M3U Desteği**:
   - M3U URL ve Xtream Codes API (Sunucu + Kullanıcı Adı + Şifre) ile doğrudan senkronizasyon.
   - Kategori filtreleme, A-Z / Z-A sıralama ve anlık arama.

4. **Dahili CORS & Akış Proxy'si**:
   - IPTV sunucularının tarayıcı/ağ kısıtlamalarını aşan entegre yerel akış motoru.

5. **Harici Oynatıcı Desteği**:
   - Tek tıkla VLC veya MPV harici masaüstü oynatıcılarında açma.

---

## 🛠️ Kurulum & Geliştirici Komutları

```bash
# Bağımlılıkları yükleme
npm install

# Geliştirici modunda başlatma (Web + Proxy)
npm run dev

# Masaüstü uygulaması olarak başlatma (Electron)
npm run electron:dev

# Windows Kurulumlu EXE üretme (NSIS)
npm run electron:build

# Kurulumsuz Taşınabilir (Portable) EXE üretme
npm run electron:build:portable
```

---

## ⌨️ Kısayol Tuşları
- **Ctrl + K**: Hızlı Arama
- **Esc**: Oynatıcıyı kapat
- **F**: Tam ekran
- **Boşluk (Space)**: Oynat / Duraklat
- **Yukarı / Aşağı Ok**: Ses seviyesi
- **Sol / Sağ Ok**: Geri / İleri sarma
