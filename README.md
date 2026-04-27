# Kala Catering — Platform Katering Digital

Kala adalah platform katering digital yang mendigitalkan pengalaman "prasmanan rumahan". Berbeda dengan katering konvensional yang menawarkan paket kaku, Kala memberikan kendali penuh kepada pelanggan untuk meracik menu secara interaktif dan transparan.

---

## Fitur Utama

### 1. Sistem Pemesanan Interaktif
Sistem pemesanan hibrida yang memadukan pemilihan paket instan dengan fitur racik menu mandiri. Dilengkapi dengan **validasi wajib 4 kategori** (Nasi, Lauk, Lauk Pendamping, Sambal) untuk memastikan akurasi pesanan yang masuk ke dapur.

### 2. Logika Bisnis Cerdas (Penetapan Harga Dinamis)
Sistem kalkulasi *real-time* (waktu nyata) yang dirancang untuk melindungi margin keuntungan bisnis melalui:
* **Diskon Bersyarat:** Otomatisasi diskon 10% (batas maksimal Rp300.000) untuk pesanan di atas 30 porsi.
* **Ongkos Kirim Progresif:** Penyesuaian ongkos kirim berbasis volume pesanan (otomatis bertambah setiap kelipatan 10 porsi) untuk menutupi biaya logistik secara adil.

### 3. Pengalaman Navigasi Mulus (Frictionless SPA)
Sistem dibangun dengan arsitektur Aplikasi Halaman Tunggal (Single Page Application / SPA) menggunakan JavaScript murni (Vanilla JS) untuk manipulasi elemen web secara langsung. Perpindahan halaman, penyaringan kategori, hingga manajemen keranjang belanja dilakukan secara instan tanpa perlu memuat ulang (reload) halaman.

---

## Filosofi Desain

Antarmuka web ini menggunakan identitas visual yang hangat dan organik untuk membangun persepsi masakan rumahan yang bersih.

* **Palet Warna:** * `#F5E9DA` (Krem Hangat) sebagai kanvas utama, menggantikan warna putih klinis yang kaku.
    * `#64452a` (Cokelat Utama) untuk elemen tombol dan teks utama agar kontras dan mudah dibaca.
    * `#527356` (Hijau Zaitun) sebagai warna aksen untuk label status dan lencana (badge).
* **Pola Antarmuka (UI):** Menggunakan desain berbasis kartu (Card-based UI) dengan lengkungan sudut yang lembut (16px) dan bayangan halus untuk memisahkan informasi dengan jelas tanpa membuat mata lelah.

---

## Teknologi yang Digunakan (Tech Stack)

* **Tampilan (Frontend):** HTML5, CSS3 (menggunakan tata letak Flexbox & Grid kustom).
* **Logika Sistem:** JavaScript (Vanilla JS) untuk logika keranjang belanja, validasi formulir, dan kalkulasi harga dinamis.
* **Tipografi:** Poppins (Google Fonts) untuk estetika teks yang modern dan bersih.

---

## Struktur Direktori

```text
.
├── images/          
├── index.html       
├── script.js        
└── style.css        
