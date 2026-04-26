# 🍲 Kala Catering — Digital Home-Buffet Platform

Kala adalah platform katering digital yang mendigitalkan pengalaman "prasmanan rumahan". Berbeda dengan katering konvensional yang menawarkan paket kaku, Kala memberikan kendali penuh kepada pelanggan untuk meracik menu secara interaktif dan transparan.

---

## 🚀 Key Features

### 1. Interactive Custom Engine
Sistem pemesanan hibrida yang memadukan pemilihan paket instan dengan fitur racik menu mandiri. Dilengkapi dengan **validasi wajib 4 kategori** (Nasi, Lauk, Side Dish, Sambal) untuk memastikan akurasi pesanan di sisi dapur.

### 2. Smart Business Logic (Dynamic Pricing)
Sistem kalkulasi *real-time* yang melindungi margin bisnis melalui:
* **Diskon Bersyarat:** Otomatisasi diskon 10% (capped di Rp300.000) untuk pesanan di atas 30 porsi.
* **Ongkir Progresif:** Penyesuaian ongkos kirim berbasis volume porsi (otomatis bertambah setiap kelipatan 10 porsi) untuk menutupi biaya logistik.

### 3. Frictionless SPA Experience
Dibangun dengan arsitektur **Single Page Application (SPA)** menggunakan JavaScript murni (Vanilla JS) untuk manipulasi DOM. Navigasi, filter kategori, hingga manajemen keranjang dilakukan tanpa *reload* halaman.

---

## 🎨 Design Philosophy

Web ini menggunakan identitas visual **"Warm & Organic"** untuk membangkitkan persepsi masakan rumahan yang bersih.

* **Palet Warna:** * `#F5E9DA` (Krem Hangat) sebagai kanvas utama pengganti putih klinis.
    * `#64452a` (Cokelat Utama) untuk elemen aksi dan teks primer.
    * `#527356` (Hijau Zaitun) sebagai aksen untuk label status dan badge.
* **UI Pattern:** Menggunakan *Card-based UI* dengan *border-radius* lembut (16px) dan bayangan halus untuk meningkatkan keterbacaan data.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Flexbox & CSS Grid System).
* **Logic:** JavaScript (Vanilla JS) untuk sistem keranjang, validasi form, dan kalkulasi dinamis.
* **Fonts:** Poppins (Google Fonts) untuk estetika modern dan bersih.

---

## 📂 Folder Structure

```text
.
├── images/          # Aset visual (Logo, Icons, Food Images)
├── index.html       # Struktur utama SPA
├── script.js        # Logic, State Management, & DOM Manipulation
└── style.css        # Custom Styling & Layout System
