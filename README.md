draft 

# 🚀 Task Master - Advanced Task Management Application

Task Master adalah aplikasi manajemen tugas modern dan kaya fitur yang dibuat dengan **React** dan **Tailwind CSS**. Aplikasi ini menyediakan solusi komprehensif untuk mengatur tugas pribadi dan profesional dengan pemfilteran canggih, kategorisasi, dan statistik *real-time*.

Ini adalah aplikasi **CRUD** (Create, Read, Update, Delete) berfitur lengkap yang dirancang untuk membantu pengguna mengelola tugas harian mereka secara efisien. Aplikasi ini menawarkan antarmuka yang intuitif dengan fitur-fitur canggih termasuk organisasi tugas berbasis prioritas, manajemen kategori, pelacakan status, dan kemampuan pencarian tingkat lanjut.

*Proyek ini dikembangkan sebagai bagian dari **IBM Student Developer Initiative Capstone Project**, yang menampilkan integrasi alat pengembangan berbantuan AI untuk mempercepat dan mengoptimalkan proses pengembangan.*

## 📍 Demo Langsung

[**Lihat aplikasi yang sedang berjalan di sini**](https://your-live-demo-link.com)

## 📸 Pratinjau Aplikasi

*Tambahkan demo GIF atau beberapa tangkapan layar di sini untuk memamerkan aplikasi Anda secara visual.*

| Tampilan Desktop | Tampilan Seluler |
| :---: | :---: |
|  |  |

-----

## ✨ Fitur Utama

### 📊 Fungsionalitas Inti & Lanjutan

  * **Operasi CRUD Penuh:** Buat, Baca, Perbarui, dan Hapus tugas dengan detail komprehensif (judul, deskripsi, kategori, prioritas, tanggal jatuh tempo, dan status).
  * **Dasbor Statistik Real-time:** Penghitung langsung yang menunjukkan jumlah **Total Tugas**, **Tertunda**, **Sedang Dikerjakan**, dan **Selesai**.
  * **Pencarian Lanjutan:** Pencarian teks lengkap di seluruh judul dan deskripsi tugas.
  * **Pemfilteran Multi-level:** Filter tugas berdasarkan:
      * **Status** (tertunda/sedang dikerjakan/selesai)
      * **Prioritas** (rendah/sedang/tinggi)
      * **Kategori** (pribadi/pekerjaan/belanja/kesehatan/lainnya)
  * **Persistensi Data:** Menggunakan `sessionStorage` API untuk menyimpan tugas, sehingga data tetap ada bahkan setelah halaman disegarkan.
  * **Toggle Status Cepat:** Klik ikon lingkaran untuk beralih status tugas dengan cepat (Tertunda ➔ Sedang Dikerjakan ➔ Selesai).

### 🎨 Pengalaman Pengguna (UX) & Antarmuka

  * **Sistem Prioritas Visual:** *Badge* berkode warna untuk pengenalan prioritas instan:
      * 🔴 **Prioritas Tinggi**
      * 🟡 **Prioritas Sedang**
      * 🟢 **Prioritas Rendah**
  * **Desain Sepenuhnya Responsif:** Tata letak yang dioptimalkan untuk desktop, tablet, dan perangkat seluler.
  * **Validasi Formulir:** Validasi bidang yang wajib diisi dengan pesan kesalahan yang mudah dipahami.
  * **Dialog Konfirmasi:** Mencegah penghapusan yang tidak disengaja dengan konfirmasi.
  * **Penanganan *Empty State*:** Pesan bermanfaat saat tidak ada tugas atau filter tidak menemukan hasil.
  * **UI Interaktif:** Transisi yang mulus, efek *hover*, dan hierarki visual yang bersih.

-----

## 🛠️ Teknologi & Peralatan yang Digunakan

| Kategori | Teknologi |
| :--- | :--- |
| **Framework & Library** | React 18 (Hooks: `useState`, `useEffect`), Vite |
| **Styling** | Tailwind CSS, Lucide React (Icons) |
| **Manajemen Data** | SessionStorage API, React Hooks |
| **Perangkat Pengembangan** | Node.js, npm, ESLint, VS Code |
| **Version Control** | Git & GitHub |
| **Platform Deployment** | Netlify, Vercel, GitHub Pages |

-----

## ⚙️ Memulai

Untuk mendapatkan salinan lokal dan menjalankannya, ikuti langkah-langkah sederhana ini.

### Prasyarat

Pastikan Anda telah menginstal [Node.js](https://nodejs.org/) (yang menyertakan npm) di mesin Anda.

### Instalasi

1.  **Clone repositori:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2.  **Masuk ke direktori proyek:**
    ```bash
    cd your-repo-name
    ```
3.  **Instal paket NPM:**
    ```bash
    npm install
    ```
4.  **Jalankan server pengembangan (Vite):**
    ```bash
    npm run dev
    ```
5.  Buka [http://localhost:5173](https://www.google.com/search?q=http://localhost:5173) (atau port yang ditentukan di konsol Anda) untuk melihatnya di browser.

-----

## 🌍 Deployment

Aplikasi ini dibuat sebagai situs statis dan dapat dengan mudah di-*deploy* ke layanan hosting situs statis apa pun seperti:

  * Netlify
  * Vercel
  * GitHub Pages

-----

## 📜 Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat file `LICENSE` untuk informasi lebih lanjut.
