# Çalışkan Otomotiv — Multi-page + CMS

## Kurulum
```bash
npm install
npm run dev
```

## Sayfalar
- /
- /hizmetler
- /hizmetler/:slug
- /hakkimizda
- /blog
- /blog/:slug
- /iletisim
- /admin

## Admin
Demo yönetici şifresi: `caliskan2026`

Admin fonksiyonları:
- Genel site ayarları
- Hizmet CRUD + slug + SEO alanları + yayın durumu
- Blog CRUD + yayın durumu
- SSS CRUD
- İletişim talepleri ve durum takibi
- Tarayıcı içi medya yükleme/silme
- SEO merkezi
- Analytics dashboard
- Kullanıcı aktif/pasif yönetimi
- JSON yedek alma / geri yükleme
- Varsayılan verilere dönme

Veriler demo sürümünde localStorage'da tutulur. Gerçek üretim için Laravel/MySQL API ve güvenli sunucu tarafı authentication bağlanmalıdır.
