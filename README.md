
# Kala Catering — Platform Katering Digital

Kala Catering merupakan platform Food Ordering digital yang mendigitalkan pengalaman "prasmanan rumahan". Berbeda dengan katering tradisional pada umumnya yang membuat pelanggan hanya bisa memilih paket statis, Kala memberikan kendali penuh kepada pengguna untuk meracik sendiri menu mereka secara interaktif.

---

## Fitur Utama

### 1. Sistem Racik Menu Interaktif
Memadukan sistem kustomisasi menu interaktif dengan opsi pemesanan langsung untuk paket siap pesan. Sistem ini dilengkapi dengan validasi 4 kategori wajib (Nasi, Lauk, Side Dish, Sambal) dan melakukan kalkulasi harga pesanan secara real-time.

### 2. Logika Harga Dinamis (Dynamic Pricing)
Sistem otomatis yang mengkalkulasi batas aman diskon dan ongkos kirim progresif secara real-time agar bisnis tidak rugi saat menerima pesanan porsi yang banyak. Logika ini memproteksi margin dengan batas maksimal diskon Rp300.000 (minimal pembelian 10 porsi) dan ongkir yang dihitung progresif per kelipatan 10 porsi.

### 3. Checkout Terstruktur dan Validasi Data
Formulir pemesanan terintegrasi dengan sistem validasi data wajib pengguna. Sistem ini secara aktif mencegah masuknya pesanan fiktif atau data pengiriman yang tidak lengkap sebelum pesanan dapat diproses.

---

## Metodologi Pengerjaan (Workflow)

Pengembangan sistem Kala Catering dilakukan secara terstruktur melalui tahapan berikut:

1. **Ideasi & Perencanaan:** Pencarian ide dan menentukan fitur utama sistem, 276].
2. **Desain & Purwarupa:** Riset referensi desain serupa, perancangan tema dan struktur web, dilanjutkan dengan pembuatan wireframe, 278, 285].
3. **Pengembangan Tampilan (Front-end):** Implementasi antarmuka pengguna menggunakan HTML, CSS, dan JavaScript].
4. **Integrasi Logika (Back-end/Core Logic):** Implementasi logika fitur custom (racik menu) dan halaman order].
5. **Finalisasi:** Testing dan debugging sistem secara menyeluruh, diakhiri dengan proses deploy, 283].

---

## Filosofi Desain

Antarmuka web ini menggunakan identitas visual yang hangat dan organik untuk membangun persepsi masakan rumahan yang bersih.

* **Palet Warna:** Menggunakan warna bumi (Krem Hangat, Cokelat Utama, dan Hijau Zaitun) sebagai pengganti warna korporat klinis untuk memperkuat nuansa "Buatan Ibu".
* **Pola Antarmuka (UI):** Menggunakan desain berbasis kartu (Card-based UI) untuk memisahkan informasi dengan jelas, mempercepat proses pengambilan keputusan oleh pelanggan.

---

## Teknologi yang Digunakan (Tech Stack)

* **Tampilan (Frontend):** HTML5, CSS3 (memanfaatkan tata letak Flexbox & Grid kustom).
* **Logika Sistem:** JavaScript (Vanilla JS) untuk sistem validasi, manipulasi keranjang belanja, dan kalkulasi harga real-time.
* **Tipografi:** Poppins (Google Fonts) untuk estetika yang modern, bersih, dan mudah dibaca.

---

## Struktur Direktori

```text
.
├── images/
├── index.html
├── script.js        
└── style.css        
