# Lab2Web - HTML Lanjutan

**Nama:** Bagas Tresna Afandi  
**NIM:** 312510486  
**Kelas:** I252A  
**Mata Kuliah:** Pemrograman Web  

---

## Deskripsi Tugas
Praktikum ini membahas penerapan HTML Lanjutan yang meliputi penggunaan Tabel, Form & Input Types, Validasi Form Dasar, Semantic HTML, serta pengintegrasian Elemen Multimedia.

## Langkah Penyelesaian
1. Membuat folder kerja `Lab2Web` beserta struktur file yang dibutuhkan.
2. Menyusun file `index.html` yang berisi latihan tabel, form, validasi, semantic HTML, dan multimedia.
3. Menyusun file `biodata.html` sebagai proyek mini yang menggabungkan seluruh konsep.
4. Menjalankan file di browser dan mengambil screenshot pengujian form/tabel/multimedia.

## Hasil Tampilan
*(Tambahkan gambar screenshot hasil pengujian browser Anda di sini)*
- **Tabel & Form:** `![Screenshot Tabel](screenshot1.png)`
- **Validasi Input:** `![Screenshot Validasi](screenshot2.png)`

## Jawaban Pertanyaan Praktikum
1. **Fungsi `<table>`, `<tr>`, `<th>`, `<td>`**: 
<table>: Elemen utama untuk mendefinisikan wadah/struktur tabel.

<tr> (table row): Elemen untuk membuat baris pada tabel.

<th> (table header): Elemen untuk membuat sel judul/header kolom atau baris.

<td> (table data): Elemen untuk mengisi sel data biasa di dalam tabel.

2. **Perbedaan `<th>` dan `<td>`**: 
<th> mendefinisikan sel sebagai header (secara default teks dicetak tebal dan rata tengah).

<td> mendefinisikan sel sebagai data standar (secara default teks berbentuk regular dan rata kiri).

3. **Fungsi `colspan`**:
 Atribut colspan digunakan untuk menggabungkan beberapa kolom menjadi satu sel secara horizontal.

4. **Fungsi `<form>`**: 
Elemen <form> berfungsi sebagai kontainer untuk menampung elemen-elemen input (seperti teks, radio button, checkbox, tombol) yang digunakan untuk mengumpulkan data dari pengguna dan mengirimkannya ke server.

5. **Perbedaan Radio Button & Checkbox**:
 Radio button (type="radio"): Memungkinkan pengguna memilih hanya satu dari beberapa pilihan yang ada.

Checkbox (type="checkbox"): Memungkinkan pengguna memilih satu, beberapa, atau tidak sama sekali pilihan yang tersedia

6. **Fungsi `label for`**: 
Atribut for menghubungkan label ke input secara langsung. Hal ini meningkatkan aksesibilitas (mendukung screen reader) dan kenyamanan pengguna, karena klik pada teks label akan otomatis memfokuskan atau mengaktifkan elemen input terkait.

7. **Perbedaan `<textarea>` & `input text`**: 
input type="text" hanya mendukung pengisian satu baris teks pendek.

<textarea> mendukung pengisian banyak baris teks (multi-line) seperti uraian alamat, komentar, atau deskripsi.

8. **Fungsi Semantic HTML**: Menyediakan struktur halaman yang bermakna bagi browser, mesin pencari (SEO), dan screen reader:

<header>: Kepala bagian/header halaman.

<nav>: Bagian tautan navigasi utama.

<main>: Tempat konten utama yang unik pada halaman.

<section>: Kelompok/blok konten bertema.

<article>: Konten mandiri yang berdiri sendiri.

<aside>: Konten pelengkap/sampingan.

<footer>: Catatan kaki/bagian bawah halaman

9. **Fungsi Atribut Validasi (`required`, `min`, `max`, `minlength`)**:
 required: Menandai bahwa elemen input wajib diisi sebelum form dikirim.

min: Menentukan nilai angka/tanggal minimum yang diizinkan.

max: Menentukan nilai angka/tanggal maksimum yang diizinkan.

minlength: Menentukan jumlah karakter teks minimal yang harus dimasukkan.

10. **Perbedaan `<audio>` & `<video>`**: 
<audio>: Elemen untuk memutar berkas suara/suara latar tanpa tampilan visual video.

<video>: Elemen untuk menampilkan dan memutar berkas video lengkap dengan proyeksi gambar visual dan suara.