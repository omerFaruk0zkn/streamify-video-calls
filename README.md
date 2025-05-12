# 📹 Streamify Video Calls

**Streamify Video Calls**, gerçek zamanlı mesajlaşma ve video görüşme özellikleri sunan tam kapsamlı bir web uygulamasıdır. Uygulama, bire bir ve grup video görüşmeleri, ekran paylaşımı, mesajlaşma, yazma göstergeleri ve reaksiyonlar gibi modern iletişim özelliklerini destekler.

🔗 [Canlı Uygulama](https://streamify-video-calls-ue7g.onrender.com)

---

## 🚀 Özellikler

- **Gerçek Zamanlı Mesajlaşma**: Yazma göstergeleri ve emoji reaksiyonları ile zenginleştirilmiş anlık mesajlaşma.
- **Video Görüşmeleri**: Bire bir ve grup video görüşmeleri, ekran paylaşımı ve kayıt özellikleri.
- **Kimlik Doğrulama**: JWT tabanlı kimlik doğrulama ve korumalı rotalar.
- **Tema Desteği**: 32 farklı kullanıcı arayüzü teması ile kişiselleştirilebilir deneyim.
- **Hata Yönetimi**: Hem ön uç hem de arka uç için kapsamlı hata yönetimi.
- **Ücretsiz Dağıtım**: Render.com üzerinden ücretsiz dağıtım imkanı.

---

## 🛠️ Teknoloji Yığını

- **Frontend**: React, TailwindCSS, Vite
- **Backend**: Node.js, Express.js
- **Veritabanı**: MongoDB
- **Gerçek Zamanlı İletişim**: Stream API
- **Durum Yönetimi**: Zustand
- **Veri Yönetimi**: TanStack Query (React Query)

---

## 📁 Proje Yapısı

```
streamify-video-calls/
├── backend/
│   ├── src/
│     ├── controllers/
│     ├── lib/
│     ├── middleware/
│     ├── models/
│     ├── routes/
│     └── server.js
├── frontend/
│   ├── src/
│     ├── components/
│     ├── constants/
│     ├── hooks/
│     ├── lib/
│     ├── pages/
│     ├── store/
│     ├── App.jsx
│     └── main.jsx
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Kurulum ve Çalıştırma

### 1. Depoyu Klonlayın

```bash
git clone https://github.com/omerFaruk0zkn/streamify-video-calls.git
cd streamify-video-calls
```

### 2. Ortam Değişkenlerini Ayarlayın

#### Backend (`/backend` dizininde `.env` dosyası oluşturun):

```
PORT=5001
MONGO_URI=your_mongo_uri
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

#### Frontend (`/frontend` dizininde `.env` dosyası oluşturun):

```
VITE_STREAM_API_KEY=your_stream_api_key
```

### 3. Bağımlılıkları Yükleyin ve Uygulamayı Başlatın

#### Backend:

```bash
cd backend
npm install
npm run dev
```

#### Frontend:

```bash
cd frontend
npm install
npm run dev
```

---

## 🧪 Test ve Geliştirme

- **Geliştirme Ortamı**: Vite ile hızlı geliştirme ve sıcak yeniden yükleme.
- **Hata Ayıklama**: Hem istemci hem de sunucu tarafında kapsamlı hata ayıklama araçları.
