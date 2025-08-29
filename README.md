# 🌐 Myths Global Map  
*Peta interaktif yang menyatukan dunia nyata & dunia paralel (isekai).*  

Selamat datang di Myths Global Map, platform interaktif revolusioner yang menggabungkan dunia nyata kita dengan dunia paralel (isekai) yang penuh misteri dan mitos. Di sini, Anda dapat menjelajahi kedua dunia secara bersamaan, menemukan cerita unik dari setiap clan, dan berinteraksi dengan komunitas global yang memiliki minat serupa. Platform ini dirancang untuk memberikan pengalaman imersif bagi para pengguna, mulai dari petualangan epik hingga diskusi strategis tentang lore clan favorit Anda. Dengan fokus pada kreativitas, inovasi, dan kebersamaan, Myths Global Map menjadi tempat ideal untuk menghubungkan pecinta fantasi dan mitologi dari seluruh dunia.

---

## 🎯 Tujuan Pembuatan  
Platform ini diciptakan untuk:  
- Menghadirkan pengalaman imersif menjelajahi dunia nyata + dunia isekai.  
- Menyediakan interaksi komunitas (chat, strategi, lore).  
- Memadukan mitologi, fantasi, dan teknologi modern.  

---

## 🏳️ Simbol Warna Clan  
| Simbol | Nama Clan | Makna |
|--------|-----------|-------|
| 🟦     | **VTA → Biru** | Kreativitas, keterbukaan, harmoni |
| 🟩     | **VTI → Hijau** | Pertumbuhan, inovasi, keseimbangan |
| 🟪     | **VTU → Ungu** | Imajinasi, eksplorasi, misteri kosmos |
| 🟨     | **VTE → Kuning/Emas** | Keunggulan, cahaya, nilai premium |
| 🟥     | **VTO → Merah** | Kekuatan, tradisi, semangat hidup |

---

## 🌍 Tampilan Peta  
Fitur utama peta:  
- Toggle antara **Map Dunia Nyata** & **Map Dunia Paralel (Isekai)**  
- Peta 3D (zoom, drag, rotate) via **Three.js / Mapbox GL JS**  
- Marker clan dengan detail interaktif  

---

## 💬 Fitur Komunikasi  
- Chat system global & private  
- Notifikasi real-time (WebSocket/Firebase)  

---

## ⚙️ Backend  
Arsitektur backend:  
- **Framework/API**: Node.js + Express / NestJS  
- **Database utama**: PostgreSQL + PostGIS  
- **Database pendukung**: MongoDB (chat)  
- **Auth**: JWT Login/Register  
- **Real-time**: WebSocket / Firebase  
- **Fungsi utama**: mengatur clan, user, lore, chat, leaderboard  

---

## 🎨 Frontend  
Stack frontend:  
- **Framework**: React.js  
- **Styling**: TailwindCSS + Shadcn UI/Material UI  
- **Animasi**: Framer Motion  
- **Map**: Mapbox GL JS / Three.js Globe  
- **Theme**: Dark/Light mode + Clan color  
- **Fungsi utama**: peta interaktif, chat, lore mode, leaderboard  

---

## ✨ Fitur Unik  
- Mode Lore (cerita tiap clan)  
- Leaderboard clan  
- Dark/Light mode  
- Tooltip interaktif  

---

## 🗄️ Skema Database  
