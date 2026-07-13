# ZALE — Two Characters. One Balance.

Landing page minimalis, modern, dan estetik untuk brand fashion/streetwear lokal **ZALE**. Didesain dengan tema *Liquid Glassmorphism* (efek kaca transparan) dengan aksen warna *Cobalt Blue* dan *Cream* yang berani, dinamis, dan menarik bagi kalangan anak muda.

Situs ini berupa landing page statis murni (1 file HTML lengkap dengan CSS dan JavaScript inline) sehingga sangat ringan, cepat dimuat, dan mudah di-deploy.

---

## ✨ Fitur Utama

1. **Liquid Glassmorphism Aesthetic**
   - Panel kartu, navbar, tombol, dan modal menggunakan efek kaca transparan (`rgba(255, 255, 255, 0.6)`) dengan efek blur latar belakang (`backdrop-filter: blur(12px)`) yang dinamis.
   - Dilengkapi efek pantulan cahaya (*glare*) dan animasi kilau kaca (*shimmer*) saat kursor di-hover.

2. **Spacious Typography (Plus Jakarta Sans)**
   - Menggunakan font *Plus Jakarta Sans* secara eksklusif dengan pengaturan jarak huruf (*letter-spacing*) dan tinggi baris (*line-height*) yang longgar untuk memberikan kesan editorial kelas atas dan "ruang bernapas" pada setiap kata.

3. **⚙️ WhatsApp Size Selector (Pemesanan Dinamis)**
   - Pembeli dapat memilih ukuran baju (S, M, L, XL, XXL) langsung di halaman web sebelum memesan.
   - Ketika tombol **Order Now** diklik, tautan WhatsApp akan terbuat secara dinamis otomatis mencantumkan ukuran yang dipilih (contoh: *"Hallo, saya mau order Zale T-Shirt size L"*).

4. **📏 Interactive Size Chart Modal (Panduan Ukuran)**
   - Pop-up modal interaktif yang menampilkan tabel panduan ukuran detail baju.
   - Menggunakan efek transisi *fade-in* & *scale-up* yang halus dan performa yang dioptimalkan. Dapat ditutup via klik di luar modal, tombol silang (X), tombol tutup, maupun tombol **Escape (Esc)**.

5. **🎯 Hitbox Kontak Diperluas**
   - Seluruh area kartu kontak (WhatsApp, Instagram, Email) dapat diklik secara langsung untuk membuka tautan terkait, mempermudah navigasi bagi pengguna mobile.

6. **📱 Fully Responsive Layout**
   - Dioptimalkan secara penuh untuk kenyamanan tampilan di layar Desktop, Tablet, hingga Handphone kecil (mobile friendly).

---

## 📁 Struktur Folder

```text
Project Zale/
│
├── index.html         # File utama website (HTML, CSS, JS terpadu)
├── README.md          # File panduan dan deskripsi repository ini
└── assets/            # Folder penyimpanan aset gambar
    └── bg.jpg         # Gambar latar belakang (background) website
```

---



> [!TIP]
> Anda bisa mengubah URL acak pemberian Netlify tersebut dengan nama brand Anda (misal: `zale.netlify.app`) secara gratis melalui menu **Site Configuration** > **Domain Management** > **Options** > **Edit site name** di dashboard Netlify Anda.
