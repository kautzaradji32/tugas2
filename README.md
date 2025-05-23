# Portofolio kautzar

File `index.html` ini adalah halaman web portofolio pribadi yang menampilkan informasi tentang Adji Pramudya Kautzar, seorang guru dengan fokus pada pembentukan moral dan pengetahuan komputer siswa. Halaman ini dirancang responsif dan memiliki beberapa bagian utama:

## Struktur Halaman

Halaman ini terdiri dari beberapa bagian (section) yang disusun secara berurutan:

1.  **Header:**
    * Berisi logo "Portofolio" di kiri atas.
    * Menu navigasi di kanan atas yang terdiri dari tautan ke bagian-bagian lain halaman: "Home", "About", "Project", "Skills", dan "Contact". Menu ini dibuat agar tetap berada di atas saat pengguna menggulir halaman (fixed).

2.  **Intro Section (Home):**
    * Bagian perkenalan utama dengan latar belakang gambar dan frame bergerak berwarna kuning sebagai latar belakang visual.
    * Menampilkan teks "Halo, It's Me", nama "ADJI PRAMUDYA KAUTZAR", dan deskripsi singkat tentang profesi dan fokusnya sebagai guru.
    * Ikon-ikon media sosial untuk Instagram, Facebook, Twitter, dan LinkedIn.
    * Tombol "Download CV" yang mengarah ke file CV.
    * Gambar profil di sebelah kanan teks perkenalan.

3.  **Hero Section (Project):**
    * Judul "My Project" dan deskripsi singkat tentang kumpulan proyek yang ditampilkan.

4.  **About Section:**
    * Judul "Tentang Saya".
    * Area untuk menambahkan informasi lebih lanjut mengenai diri dan latar belakang.

5.  **Projects Container:**
    * Bagian yang menampilkan daftar proyek dalam bentuk grid.
    * Setiap proyek ditampilkan dalam "project-card" yang berisi gambar proyek dan judul.
    * Contoh proyek yang ditampilkan: Desainer, Microsoft Office, Instal Ulang, Mikrotik.

6.  **Skills Container:**
    * Judul "Skill Yang Saya Kuasai".
    * Menampilkan daftar kemampuan teknis dalam bentuk grid "skill-card".
    * Setiap skill memiliki gambar ikon dan nama skill.
    * Contoh skill yang ditampilkan: HTML, CSS, JavaScript, Install Ulang, Mikrotik.

7.  **Contact Section:**
    * Judul "Kontak".
    * Menampilkan informasi kontak, dalam hal ini nomor telepon.
    * Area untuk menambahkan ikon kontak lainnya jika diperlukan.

8.  **Footer:**
    * Bagian paling bawah halaman (saat ini kosong).
    * Dapat digunakan untuk menambahkan informasi hak cipta atau tautan tambahan.

## Teknologi yang Digunakan

* **HTML:** Sebagai bahasa markup utama untuk struktur konten web.
* **CSS:** Untuk styling dan tata letak visual halaman, termasuk desain responsif, animasi frame bergerak, dan efek hover.
* **Font Awesome:** Untuk ikon-ikon media sosial.
* **JavaScript:** Meskipun tidak ada kode JavaScript eksplisit dalam file ini, kemungkinan akan digunakan untuk interaktivitas lebih lanjut jika dikembangkan.

## Fitur Utama

* **Desain Responsif:** Tata letak dirancang untuk beradaptasi dengan berbagai ukuran layar.
* **Header Fixed:** Menu navigasi tetap terlihat di bagian atas saat menggulir.
* **Frame Bergerak sebagai Latar Belakang:** Elemen visual dinamis pada bagian perkenalan.
* **Tampilan Proyek dan Skill dalam Grid:** Penyajian informasi yang terstruktur dan mudah dibaca.
* **Efek Hover:** Interaksi visual saat pengguna mengarahkan kursor ke elemen tertentu (misalnya, proyek dan skill card, tautan navigasi).

## Cara Penggunaan

Untuk melihat portofolio ini, cukup buka file `index.html` di peramban web (browser) Anda. Pastikan file gambar yang direferensikan (seperti `background-city.jpg` dan gambar-gambar skill serta proyek) berada di lokasi yang tepat relatif terhadap file `index.html` agar dapat ditampilkan dengan benar. Jika gambar-gambar tersebut tidak ada secara lokal, Anda perlu mengganti `url()` dan `src` dengan path atau URL gambar yang valid.

## Pengembangan Lebih Lanjut

Portofolio ini dapat dikembangkan lebih lanjut dengan menambahkan:

* Informasi lebih detail pada bagian "Tentang Saya".
* Deskripsi lebih lengkap untuk setiap proyek.
* Formulir kontak yang berfungsi.
* Animasi atau transisi yang lebih halus.
* Penggunaan JavaScript untuk interaktivitas yang lebih kompleks.
* Optimasi gambar untuk performa yang lebih baik.