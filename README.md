# 🎈 Pop Balon Matematika

Game edukasi interaktif berbasis web untuk melatih kemampuan berhitung dasar anak Sekolah Dasar dengan cara yang seru dan menyenangkan.

## 🎯 Fitur Utama

- **4 Mode Hitung**: Penjumlahan (+), Pengurangan (−), Perkalian (×), dan Pembagian (÷).
- **3 Tingkat Kesulitan**: Mudah, Sedang, dan Sukar.
- **Sistem Permainan**: 10 soal per putaran, 3 nyawa, dengan animasi balon meletus dan efek suara.
- **Skor & Rekor**: Menyimpan rekor skor terbaik pemain di browser (*localStorage*).
- **Ringan & Bebas Dependensi**: Berjalan langsung tanpa instalasi apa pun.

## 🕹️ Cara Bermain

1. Masukkan nama pemain (opsional), lalu pilih **Mode** dan **Level**.
2. Klik **MULAI ▶**.
3. Baca soal di bagian atas, lalu klik balon dengan jawaban yang benar.
4. Kumpulkan skor sebanyak-banyaknya sebelum 3 nyawa habis!

## 🚀 Cara Menjalankan

Untuk penggunaan cepat, berkas `index.html` dapat dibuka langsung di browser. Agar penyimpanan nama dan rekor lebih konsisten, jalankan server lokal dari folder proyek:

```bash
python3 -m http.server
```

Kemudian buka `http://localhost:8000` di browser.

## 📁 Struktur Berkas

- `index.html` — Tampilan game
- `style.css` — Gaya dan animasi
- `script.js` — Logika game dan efek suara
