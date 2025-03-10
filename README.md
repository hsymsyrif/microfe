Weather Application Microfrontend

📌 Deskripsi

Weather Application adalah aplikasi cuaca berbasis microfrontend yang dikembangkan menggunakan teknologi modern seperti React, TypeScript, Vue, dan Vite. Aplikasi ini menyediakan informasi cuaca real-time dengan tampilan yang responsif dan user-friendly.

🚀 Teknologi yang Digunakan

Microfrontend Architecture (Vite Module Federation)

React.js (Frontend utama / Host)

Vue.js (Remote module untuk bagian tertentu)

TypeScript (Menjamin kode lebih aman dan terstruktur)

Vite (Bundler ringan dan cepat)

Redux (State management)

Weather API (Untuk mendapatkan data cuaca)

📂 Struktur Proyek

weather-app/
├── host/ # Aplikasi utama (React + TypeScript)
├── remote-weather/ # Remote module untuk tampilan cuaca (Vue + TypeScript)
├── shared/ # Modul bersama (utils, hooks, dll)
├── package.json # Konfigurasi proyek
├── vite.config.ts # Konfigurasi Vite Module Federation
└── README.md # Dokumentasi

⚙️ Instalasi dan Menjalankan Aplikasi

1. Clone Repository

git clone https://github.com/hsymsyrif/microfe.git
cd microfe

2. Install Dependencies

Install untuk host (React)

cd host
npm install

Install untuk remote module (Vue)

cd ../remote-weather
npm install

3. Jalankan Aplikasi

Jalankan host (React)

npm run dev

Jalankan remote module (Vue)

npm run dev

Akses aplikasi di: http://localhost:5173/

📡 API yang Digunakan

Aplikasi ini menggunakan OpenWeather API untuk mendapatkan data cuaca. Pastikan Anda memiliki API key dan menyimpannya dalam .env file:

VITE_APP_ID=your_api_key_here

📌 Fitur Utama

✅ Menampilkan informasi cuaca berdasarkan lokasi pengguna
✅ Pencarian cuaca berdasarkan kota
✅ Desain responsif dengan Tailwind CSS
✅ State management dengan Redux
✅ Microfrontend dengan Vue sebagai remote module

Dikembangkan oleh Muhammad Hisyam Syarif
