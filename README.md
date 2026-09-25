# 🌐 Tugas Rutin 1 — Landing Page Pribadi

Repositori ini memuat implementasi **Tugas Rutin 1: Landing Page Pribadi** untuk mata kuliah **Pemrograman Web** (Universitas Negeri Medan). Proyek ini berfokus pada penyusunan tata letak semantik **HTML5**, penerapan standar aksesibilitas web (A11y), susunan heading hierarkis, formulir interaktif dengan validasi bawaan, kelengkapan metadata SEO & Open Graph, serta validasi standar W3C.

---

## 🔗 Live Demo & Pratinjau

- **Demo Halaman (GitHub Pages):** 
https://rnglich.github.io/TugasWeb-Pertemuan1-Portofolio/
- **Validator Markup W3C:** 
https://validator.w3.org/nu/?doc=https%3A%2F%2Frnglich.github.io%2FTugasWeb-Pertemuan1-Portofolio%2F

---

## 📌 Fitur & Pemenuhan Kriteria Penilaian

Proyek ini telah mengimplementasikan seluruh kriteria penilaian yang ditetapkan:

### 1. Struktur Semantik HTML5 (25%)
Penyusunan tata letak dokumen mengutamakan tag semantik HTML5 murni tanpa ketergantungan `<div>` yang berlebih:
- `<header>`: Memuat identitas landing page, judul utama (`<h1>`), dan navigasi.
- `<nav>`: Menu navigasi ramah pembaca layar (*screen reader*) dengan tautan anchor (*smooth jumping*).
- `<main>`: Konten inti dokumen yang membagi topik secara logis.
- `<section>`: Pengelompokan bagian utama (Profil/Tentang Saya, Portofolio/Keahlian, dan Kontak).
- `<article>`: Bagian konten independen (misal: deskripsi proyek unggulan atau rangkuman artikel).
- `<aside>`: Informasi pendukung pelengkap (misal: fakta singkat, riwayat hobi, atau tautan sosial).
- `<footer>`: Informasi hak cipta (*copyright*), tautan cepat, dan penanda waktu rilis.

### 2. Formulir Interaktif & Validasi Input (20%)
Formulir kontak dibangun menggunakan elemen form standar dengan validasi bawaan (*HTML5 constraint validation*):
- Setiap kontrol input dipasangkan secara eksplisit dengan elemen `<label>` melalui atribut `for` dan `id`.
- Dilengkapi atribut validasi: `required`, `pattern`, `minlength`, `maxlength`, dan `placeholder`.
- Tombol aksi: `<button type="submit">Kirim Pesan</button>` dan `<button type="reset">Reset Form</button>`.
- **Implementasi Bonus:** Menyediakan input tipe khusus:
  - `type="date"` (pemilihan tanggal pertemuan/acara).
  - `type="color"` (pemilihan aksen warna pesan).
  - `type="range"` (skala urgensi/penilaian).

### 3. Media Elements & Aksesibilitas (15%)
- Gambar profil dan ilustrasi dibungkus dengan semantik `<figure>` dan `<figcaption>`.
- Seluruh gambar wajib memiliki atribut `alt` yang deskriptif dan kontekstual guna mendukung aksesibilitas pengguna pembaca layar.

### 4. Heading Hierarkis (15%)
Struktur penjudulan disusun berjenjang dan logis tanpa melompati tingkatan:
- `<h1>`: Judul utama halaman (satu per dokumen).
- `<h2>`: Sub-bab untuk setiap area utama (`<section>`, `<article>`, `<aside>`).
- `<h3>`: Rincian topik kecil atau judul kartu item portofolio di dalam sub-bab.

### 5. SEO & Open Graph Meta Tags (15%)
Pemberian metadata head yang komprehensif:
- `<!DOCTYPE html>` dan atribut `<html lang="id">`.
- Karakter set `<meta charset="UTF-8">` dan responsivitas `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.
- Tag SEO: `<title>` informatif dan `<meta name="description">` padat deskriptif.
- **Implementasi Bonus:** *Open Graph Protocol* (`og:title`, `og:description`, `og:image`, `og:url`, `og:type`) untuk tampilan pratinjau kartu media sosial.

### 6. Validasi W3C (10%)
Markup dokumen 100% valid dan lolos uji validasi pada **W3C Nu HTML Checker** tanpa *error* maupun *warning*.

---

## ✅ Checklist Tugas & Poin Bonus

| No | Komponen Checklist Wajib | Status | Keterangan Implementasi |
|:--:|:---|:------:|:------------------------|
| 1 | Deklarasi `<!DOCTYPE html>` & atribut `lang` | ✅ Terpenuhi | Menggunakan `<!DOCTYPE html>` dan `<html lang="id">` |
| 2 | Charset UTF-8 & meta viewport | ✅ Terpenuhi | `<meta charset="UTF-8">` dan viewport responsif |
| 3 | Elemen `<title>` & `<meta name="description">` | ✅ Terpenuhi | Memuat judul unik dan deskripsi ringkas halaman |
| 4 | Minimal 1 gambar dengan `alt` deskriptif | ✅ Terpenuhi | Gambar profil/portofolio dengan teks alternatif informatif |
| 5 | Form dengan `<label>`, `<input>`, `<button>` | ✅ Terpenuhi | Formulir kontak lengkap dengan label dan tombol aksi |
| 6 | Navigasi dengan tautan anchor (`#id`) | ✅ Terpenuhi | Navigasi menu melompat ke section terkait (`href="#tentang"`, dsb.) |
| 7 | Footer dengan informasi hak cipta (*copyright*) | ✅ Terpenuhi | Teks hak cipta tahun berjalan |
| 8 | Validasi W3C lulus | ✅ Terpenuhi | Validasi tanpa galat (*zero error/warning*) |
| ⭐ | **Bonus 1:** Tag `<figure>` dan `<figcaption>` | ✅ Terpenuhi | Digunakan pada foto profil & preview media |
| ⭐ | **Bonus 2:** Tag `<time>` untuk penanggalan | ✅ Terpenuhi | Digunakan pada tanggal rilis/pembaruan dengan atribut `datetime` |
| ⭐ | **Bonus 3:** Tag Open Graph (`og:*`) | ✅ Terpenuhi | Pratinjau sosial media lengkap (WhatsApp/Twitter/LinkedIn) |
| ⭐ | **Bonus 4:** Input type khusus (`date`, `color`, `range`) | ✅ Terpenuhi | Variasi input modern pada formulir interaktif |

---
