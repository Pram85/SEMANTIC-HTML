# Nama       : Pramudya Sigit Bachtiar
# NIM/ KELAS : 2205101085 / TIF 5D

# SEMANTIC-HTML 
Latihan Praktikum Semantic HTML.

## Semantic HTML Project ##
Project ini berfokus pada penerapan struktur HTML Semantic.

## Penjelasan struktur dari HTML dan CSS ##

## Analisis Code HTML ##
1. ## Struktur HTML ##
   Secara Keseluruhan code HTML sudah mengikuti standart HTML5. `<!DOCTYPE html>`, `<html>`,`<head>`,`<body>`, dan elemen-elemen utama seperti `<header>`,`<nav>`,`<section>`, dan `<footer>` sudah digunakan dengan benar.
2. ## Elemen Semantic ##
   Penggunaan elemen-elemen seperti `<header>`,`nav`,`section`, dan `footer` sudah sesuai dengan HTML5 dan meningkatkan aksebilitas dan keterbacaan code.
3. ## Kekurangan ##
   * `<section>`, Bagian `<section>` hanya berisi teks tanpa elemen tambahan. Sebaiknya diisi dengan HTML seperti paragraf atau heading agar lebih informatif.
   * Teks Copyright, Dalam `<footer>`, sebaiknya gunakan entitas HTML `&copy;` untuk simbol hak cipta, sehingga lebih standart.
  
## Analisis Code CSS ##
1. ## `<display: grid;>` ##
   Ini telah diterapkan pada elemen `body` untuk membuat tata letak grid. Penggunaan `grid-template-areas` dan pembagian grid area (`header`, `nav`, `section`, dan `footer`) sudah tepat untuk mengatur struktur layout.
2. ## `grid-template-rows` dan `grid-template-columns` ##
   Properti ini telah digunakan untuk menentukan tinggi dan lebar masing-masing baris dan kolom dalam grid.
3. ## Kekurangan ##
   * Responsivitas, Pengaturan grid tidak akan terlihat optimal pada layar yang lebih kecil. Disarankan menggunakan media queries agar layout dapat beradaptasi dengan ukuran layar yang lebih kecil, seperti di perangkat mobile.
   * Warna Latar Belakang untuk `section`, Warna latar belakang `#ababab` pada elemen `section` dapat ditinjau agar memiliki kontras yang lebih tinggi dengan warna teks agar lebih mudah dibaca.
   * `font-size` pada `footer`, Pemilihan `font-size: small;` mungkin akan menghasilkan teks yang terlalu kecil pada beberapa layar. Disarankan untuk memastikan ukuran font tetap terbaca pada layar kecil
   * Grid pada `<body>`, Pengaturan `height: 100vh` pada elemen `body` akan membuatnya memiliki tinggi penuh viewport, yang dapat menyebabkan masalah scroll pada layar kecil. Ini bisa diganti dengan `min-height: 100vh` untuk memastikan elemen tidak memotong pada layar kecil atau tinggi bervariasi.
  
## Kesimpulan ##
* Struktur dan penggunaan elemen: Sudah baik.
* Responsivitas: Perlu ditingkatkan.
* Aksebilitas dan keterbacaan:  Bisa diperbaiki dengan menyesuaikan warna latar belakang dan ukuran teks.
