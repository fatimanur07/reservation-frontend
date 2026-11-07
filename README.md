# 🏨 Artemis Hotel & Resort - Frontend

Artemis Hotel & Resort için geliştirilmiş, misafirlerin lüks oda seçeneklerini inceleyip rezervasyon yapabildiği ve yöneticilerin rezervasyonları takip edebildiği modern bir web arayüzüdür.

---

## ✨ Özellikler

- **Oda ve Süit Seçenekleri:** Standart Oda, Deluxe King Süit, Executive Süit ve Presidential Süit için özel fiyatlandırma, oda büyüklüğü ve manzara detayları[cite: 1, 2].
- **Hızlı Rezervasyon:** Tarih ve oda seçimi ile anında rezervasyon tamamlama[cite: 1].
- **Yönetici Paneli:** Yetkili girişi ile (`oteladmin@artemis.com`) rezervasyonları görüntüleme ve yönetme ekranı[cite: 1, 2].
- **Duyarlı Tasarım:** Mobil ve masaüstü cihazlarla tam uyumlu kullanıcı deneyimi.

---

## 🛠️ Kullanılan Teknolojiler

- **React 18**[cite: 1]
- **Vite**[cite: 4]
- **Axios**[cite: 1]
- **CSS3**[cite: 1]
- **ESLint**[cite: 2]

---

## 📁 Proje Yapısı

```text
├── public/               # Favicon ve statik ikonlar[cite: 4]
├── src/
│   ├── assets/           # Görseller ve medya varlıkları[cite: 4]
│   ├── App.css           # Uygulama stilleri[cite: 1]
│   ├── App.jsx           # Ana bileşen, oda tipleri, fiyatlar ve yönetici paneli[cite: 1]
│   ├── index.css         # Temel stil tanımları[cite: 1]
│   └── main.jsx          # Uygulama giriş noktası[cite: 3]
├── eslint.config.js      # Linter yapılandırması[cite: 2]
├── index.html            # Ana HTML şablonu[cite: 4]
├── package.json          # Paket bağımlılıkları[cite: 4]
└── vite.config.js        # Vite ayarları[cite: 6]

🚀 Kurulum ve Çalıştırma
npm install

Geliştirme Sunucusunu Başlatın:
npm run dev

Uygulamayı Açın:
Tarayıcınızda http://localhost:5173 adresine gidin.

🔗 Backend Entegrasyonu
Uygulama yerel API servisine http://localhost:3000 üzerinden bağlanır[cite: 1, 2].


<FollowUp label="Bu README içeriğini GitHub üzerindeki dosyaya doğrudan nasıl ekleyeceğinizi göstereyim mi?" query="GitHub üzerindeki README.md dosyasını tarayıcıdan düzenleyip bu içeriği nasıl kaydedebilirim?"/>
