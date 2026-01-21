# 📝 To-Do List (HTML & CSS Only)

Proyek ini merupakan **To-Do List sederhana** yang dibuat **hanya menggunakan HTML dan CSS**, tanpa JavaScript.  
Tujuan utama proyek ini adalah melatih **struktur HTML**, **styling CSS**, serta **layout dan interaksi visual dasar**.

Proyek ini dikerjakan sebagai bagian dari pembelajaran di **roadmap.sh**.

---

## ✨ Fitur

- Tampilan daftar tugas (To-Do List)
- Setiap tugas memiliki:
  - Nama tugas
  - Tanggal target pengerjaan
- Tombol **Tambah** (nonaktif / `disabled`)
- Tombol **Hapus (X)** pada setiap tugas (visual saja)
- Efek hover pada:
  - Tombol
  - Item tugas
- Desain sederhana dan rapi

> ⚠️ Catatan:  
> Proyek ini **belum memiliki fungsi tambah dan hapus secara dinamis** karena **tidak menggunakan JavaScript**.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**
- **CSS3**

---

## 📂 Struktur File

📦 to-do-list

├── index.html

├── style.css

└── README.md


---

## 🎨 Penjelasan Singkat Struktur

### HTML
- `<ul>` dan `<li>` digunakan untuk daftar tugas
- `<span>` digunakan untuk memisahkan:
  - Nama tugas
  - Tanggal tugas
- Tombol **Tambah** menggunakan atribut `disabled` untuk menandakan belum aktif
- Tombol **Hapus** hanya bersifat tampilan (belum berfungsi)

### CSS
- `flexbox` untuk layout input dan item tugas
- `hover`, `transform`, dan `transition` untuk efek interaksi
- `:disabled` untuk styling elemen yang tidak aktif
- `translateY()` untuk efek mengangkat item saat di-hover

---

## 🚀 Tujuan Pembelajaran

- Memahami struktur HTML yang rapi dan semantik
- Mengatur layout menggunakan Flexbox
- Menggunakan efek hover dan animasi sederhana
- Memahami konsep `disabled` pada elemen form
- Mempersiapkan struktur sebelum masuk ke JavaScript

---

## 📌 Rencana Pengembangan (Opsional)

- Menambahkan JavaScript untuk:
  - Menambah tugas
  - Menghapus tugas
  - Validasi input
- Menyimpan data tugas ke Local Storage
- Menambahkan status tugas (selesai / belum)

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan **belajar** dan bebas digunakan atau dikembangkan lebih lanjut.

## link URL project
 https://davadidat.github.io/list-html-css/

## link roadmap.sh
https://roadmap.sh/projects/changelog-component
