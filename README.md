# AY.İŞ — Kariyer Takip Uygulaması

İş başvuruları, sınavlar ve yüksek lisans başvurularını tek bir yerden takip et.

## Kurulum

### 1. Gereksinimler
- **Node.js** (v18+): https://nodejs.org adresinden LTS sürümünü indir
- **VS Code**: https://code.visualstudio.com

### 2. Projeyi Aç
```bash
# Bu klasörü VS Code ile aç
# Ardından VS Code'da Terminal > New Terminal ile terminal aç
```

### 3. Bağımlılıkları Kur
```bash
npm install
```

### 4. Geliştirme Sunucusunu Başlat
```bash
npm run dev
```
Tarayıcıda `http://localhost:5173` adresine git.

### 5. Yayınla (Deploy)

#### Vercel ile (Önerilen - Ücretsiz)
1. https://vercel.com adresine GitHub hesabınla giriş yap
2. Projeyi GitHub'a yükle
3. Vercel'de "New Project" > GitHub reposunu seç > Deploy

#### Netlify ile (Alternatif - Ücretsiz)
1. https://netlify.com adresine giriş yap
2. `npm run build` komutunu çalıştır
3. `dist` klasörünü Netlify'a sürükle-bırak

Deploy sonrası aldığın linki arkadaşlarınla paylaşabilirsin!

## Proje Yapısı
```
ayis-project/
├── index.html          # Ana HTML dosyası
├── package.json        # Proje ayarları ve bağımlılıklar
├── vite.config.js      # Vite yapılandırması
└── src/
    ├── main.jsx        # Giriş noktası
    └── App.jsx         # Uygulama kodu
```

## Özellikler
- 3 modül: İş Başvurusu, Sınavlar, Yüksek Lisans
- Koyu / Açık tema
- Modül bazlı renk temaları
- Etiket sistemi ve filtreleme
- Mülakat aşamaları takibi
- Belge checklist (YL)
- Yaklaşan etkinlikler dashboard'u
- Responsive tasarım (mobil + masaüstü)
