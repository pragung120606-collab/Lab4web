# Lab4Web - Praktikum 4: CSS Layout

Repository ini berisi seluruh hasil latihan dan tugas praktikum Pemrograman Web (Modul 4: CSS Layout & Semantics Element) Universitas Pelita Bangsa.

## 📁 Struktur Folder & Berkas

```text
Lab4Web/
├── lab4_box.html             # Praktikum Box Element & CSS Float Clearfix
├── README.md                 # Laporan praktikum & dokumentasi
└── lab4_layout/
    ├── home.html             # Halaman utama (Home layout)
    ├── artikel.html          # Halaman artikel
    ├── about.html            # Halaman About (Deskripsi & Portfolio)
    ├── kontak.html           # Halaman Contact (Form Isian)
    ├── style.css             # Stylesheet CSS utama layout
    └── images/               # Aset gambar lokal
        ├── orange-circle.png
        ├── blue-circle.png
        ├── teal-circle.png
        ├── featurette-1.png
        ├── featurette-2.png
        └── profile.png
```

---

## 🚀 Penjelasan Langkah Praktikum

### 1. Praktikum Box Element (`lab4_box.html`) [cite: 4, 5]
- **Tujuan:** Memahami penggunaan tag `<div>`, properti `float`, dan penerapan `clear` (clearfix) [cite: 4, 5].
- **Langkah-Langkah:**
  1. Membuat dokumen HTML dengan elemen heading `<h1>Box Element</h1>` [cite: 4].
  2. Menambahkan `div` bertipe class `div1`, `div2`, dan `div3` [cite: 4].
  3. Mengatur gaya CSS `float: left;` dan `padding: 10px;` untuk membuat posisi div mengapung secara vertikal/horizontal berdampingan [cite: 4].
  4. Menambahkan `div4` dengan properti `clear: left; float: none;` untuk menetralkan efek float pada elemen berikutnya [cite: 5].

---

### 2. Layout Sederhana (`lab4_layout/`) [cite: 6, 7]
- **Tujuan:** Membuat web layout utuh menggunakan HTML5 Semantic Elements (`<header>`, `<nav>`, `<section>`, `<aside>`, `<footer>`) [cite: 7].

#### a. Halaman Utama (`home.html`) [cite: 6]
- Menampilkan navigasi utama, hero section banner ("Hello World!") [cite: 6, 9].
- Menampilkan 3 kolom fitur bertema lingkaran (Orange, Blue, Teal) [cite: 6, 13].
- Menampilkan 2 artikel featurette dengan gambar di sisi kiri dan kanan [cite: 6, 14, 15].
- Menampilkan sidebar widget (Link Widget dan Text Widget) [cite: 6, 11].

#### b. Halaman Artikel (`artikel.html`)
- Berisi kumpulan artikel edukatif seputar pengembangan web dan penggunaan HTML/CSS.

#### c. Halaman About (`about.html`)
- **Tugas 1 Praktikum:** Menambahkan layout menu About [cite: 15].
- Berisi deskripsi singkat tentang pengembang, foto profil, serta portofolio keahlian (Web Development, Database, & Programming) [cite: 15].

#### d. Halaman Kontak (`kontak.html`)
- **Tugas 2 Praktikum:** Menambahkan layout menu Contact [cite: 15].
- Berisi form isian lengkap yang mencakup input **Nama Lengkap**, **Email**, dan **Pesan (Textarea)** beserta tombol submit [cite: 15].

---

## 🛠️ Cara Menjalankan
1. Clone atau buka direktori `Lab4Web/` pada komputer Anda.
2. Buka berkas `lab4_box.html` atau `lab4_layout/home.html` langsung menggunakan browser pilihan Anda (Google Chrome, Firefox, Edge, dll.).
3. Navigasikan antar halaman melalui menu navigasi yang tersedia di bagian atas (Home, Artikel, About, Kontak) [cite: 6, 7].
