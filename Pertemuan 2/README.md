# BEM Universitas Pancasila — Profil Organisasi

Halaman web statis yang menampilkan profil organisasi Badan Eksekutif Mahasiswa (BEM) Universitas Pancasila, yang secara resmi dikenal sebagai **Senat Keluarga Mahasiswa Universitas Pancasila (Senat KMUP)**.

##  Deskripsi

Proyek ini merupakan tugas praktikum HTML yang berisi halaman profil organisasi kampus. Halaman ini menyajikan informasi mengenai profil, program unggulan, divisi organisasi, alur pendaftaran anggota baru, serta kontak resmi organisasi.

## Fitur

- **Navigasi Internal** — Menu navigasi dengan tautan anchor ke setiap bagian halaman.
- **Profil Organisasi** — Penjelasan singkat mengenai sejarah dan nama resmi organisasi.
- **Program Keahlian** — Daftar program unggulan menggunakan *ordered list*.
- **Divisi Organisasi** — Daftar divisi menggunakan *unordered list*.
- **Alur Pendaftaran** — Tahapan rekrutmen anggota baru menggunakan *description list*.
- **Kontak** — Informasi email, website resmi, dan media sosial.
- **Semantik HTML** — Menggunakan elemen semantik seperti `<header>`, `<nav>`, `<section>`, dan `<footer>`.

##  Struktur Proyek
```text
.
├── index.html
├── README.md
├── css/
│   └── style.css
├── logo/
│   └── logo.png
└── gedung/
    └── image.jpg
```

>  `css/style.css`, `logo/logo.png`, dan `gedung/image.jpg` tersedia agar tampilan halaman berjalan dengan baik.

##  Cara Menjalankan

1. Clone atau unduh repositori ini.
2. Pastikan seluruh struktur folder dan file pendukung (CSS & gambar) sudah lengkap.
3. Buka file `index.html` di browser favorit Anda (Chrome, Firefox, Edge, dsb).
4. Halaman akan langsung tampil tanpa memerlukan server khusus.

##  Bagian Halaman

| Bagian | ID | Deskripsi |
|--------|----|-----------|
| Beranda | `#beranda` | Judul dan tagline organisasi |
| Profil | `#profil` | Sejarah dan logo organisasi |
| Program | `#program` | Program unggulan (ordered list) |
| Divisi | `#divisi` | Divisi organisasi (unordered list) |
| Pendaftaran | `#pendaftaran` | Alur rekrutmen anggota baru |
| Kontak | `#kontak` | Email, website, dan media sosial |

##  Teknologi

- **HTML5** — Struktur halaman
- **CSS3** — Styling (file eksternal `css/style.css`)


##  Lisensi
&copy; 2026 BEM Universitas Pancasila. Dibuat untuk Tugas Praktikum HTML.
