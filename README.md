# Back-End Aplikasi Kontak

Ini adalah back-end untuk aplikasi manajemen kontak yang menggunakan Node.js dan Express. Back-end ini menyediakan API untuk operasi CRUD (Create, Read, Update, Delete) pada data kontak.

---

**nanti jalankan Back End nya pake perintah berikut, karena kesalahan di awal ketika buat folder nya disamakan seperti buat Front End, jadi gunakan perintah berikut untuk menjalankan Back End nya:**
   ```bash
   node src/server.js
   ```

## Prasyarat

1. **Node.js** (versi 14 atau lebih baru)
2. **npm** atau **yarn**
3. **MongoDB** (instalasi lokal atau cloud seperti MongoDB Atlas)

---

## Instalasi

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/username/project-repo-backend.git
   cd project-repo-backend
   ```

2. **Instal dependensi:**
   ```bash
   npm install
   ```

3. **Konfigurasi file environment:**
   Buat file `.env` di root proyek dan tambahkan konfigurasi berikut:
   ```env
   PORT=5000
   MONGO_URI=buat mongo db nya
   JWT_SECRET=your_jwt_secret
   ```

   - `PORT`: Port di mana server akan berjalan.
   - `MONGO_URI`: URL koneksi ke database MongoDB.
   - `JWT_SECRET`: Kunci rahasia untuk autentikasi JWT.

---

## Menjalankan Server

1. **Jalankan server:**
   ```bash
   node src/server.js
   ```

2. **Server akan berjalan di:**
   ```
   http://localhost:5000
   ```

---

## Struktur Direktori

```
project-repo-backend/
├── controllers/       # Logika untuk setiap endpoint
├── models/            # Skema database MongoDB
├── routes/            # Rute API
├── middlewares/       # Middleware seperti autentikasi
├── config/            # Konfigurasi database
├── .env               # Konfigurasi environment
├── server.js          # File utama aplikasi
├── package.json       # Dependensi proyek
└── README.md          # Dokumentasi proyek
```

---


