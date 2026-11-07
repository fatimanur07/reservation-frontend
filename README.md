# 🏨 Artemis Hotel & Resort - Frontend

Artemis Hotel & Resort için geliştirilmiş, misafirlerin lüks oda seçeneklerini inceleyip rezervasyon yapabildiği ve yöneticilerin rezervasyonları takip edebildiği modern bir web arayüzüdür.

---

## ✨ Özellikler

- **Oda ve Süit Seçenekleri:** Standart Oda, Deluxe King Süit, Executive Süit ve Presidential Süit için özel fiyatlandırma, oda büyüklüğü ve manzara detayları.
- **Hızlı Rezervasyon:** Tarih ve oda seçimi ile anında rezervasyon tamamlama.
- **Yönetici Paneli:** Yetkili girişi ile (`oteladmin@artemis.com`) rezervasyonları görüntüleme ve yönetme ekranı.
- **Duyarlı Tasarım:** Mobil ve masaüstü cihazlarla tam uyumlu kullanıcı deneyimi.

---

## 🛠️ Kullanılan Teknolojiler

- **React 18**
- **Vite**
- **Axios**
- **CSS3**
- **ESLint**

---

## 📁 Proje Yapısı

```text
├── public/               # Favicon ve statik ikonlar
├── src/
│   ├── assets/           # Görseller ve medya varlıkları
│   ├── App.css           # Uygulama stilleri
│   ├── App.jsx           # Ana bileşen, oda tipleri, fiyatlar ve yönetici paneli
│   ├── index.css         # Temel stil tanımları
│   └── main.jsx          # Uygulama giriş noktası
├── eslint.config.js      # Linter yapılandırması
├── index.html            # Ana HTML şablonu
├── package.json          # Paket bağımlılıkları
└── vite.config.js        # Vite ayarları

Bağımlılıkları Yükleyin:
npm install


Geliştirme Sunucusunu Başlatın:
npm run dev


Uygulamayı Açın:
Tarayıcınızda http://localhost:5173 adresine gidin.

🔗 Backend Entegrasyonu
Uygulama yerel API servisine http://localhost:3000 üzerinden bağlanır.
