# Praktikum 1: HTML Dasar
~~~
Ridho Prasetya
311910621
TI.19.A2
~~~
## Langkah 1
### Buka VSCode dan buat file HTML baru. Setelah itu buat struktur dasar HTML
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
~~~
![1](https://user-images.githubusercontent.com/56241745/112866464-0671da00-90e4-11eb-97ed-f8a122a35814.png)
## LANGKAH 2
### Membuat 2 buah paragraf dan atur atribut paragraf (Rata Kiri / Rata Kanan / Rata Tengah / Sama Rata)
~~~
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
~~~
![2](https://user-images.githubusercontent.com/56241745/112866958-91eb6b00-90e4-11eb-9f0e-4441cbaf01b3.png)
## LANGKAH 3
### Menambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
~~~
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
~~~
![3](https://user-images.githubusercontent.com/56241745/112868030-cc093c80-90e5-11eb-9cf5-8aefa532d495.png)
## LANGKAH 4
### Memformat Teks menggunakan format-format teks yang ada seperti `<b>`, `<strong>`, `<i>`, `<em>`, `<mark>`, `<small>`, `<dell>`, `<ins>`, `<sub>`, dan `<sup>`.
~~~
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
~~~
![4](https://user-images.githubusercontent.com/56241745/112868065-d592a480-90e5-11eb-8ba9-d485c29d36f0.png)
## LANGKAH 5
### Menyisipkan Gambar dan mengatur ukuran gambar. Sebelum menyisipkan gambar, file HTML yg sudah dibuat dijadikan satu bersama dengan gambar yg akan disisipkan.
![5](https://user-images.githubusercontent.com/56241745/112868085-dcb9b280-90e5-11eb-8a38-479ed07c42fd.png)
~~~
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="Logo_UPB.png" width="200" title="Logo Univeritas Pelita Bangsa">
~~~
![6](https://user-images.githubusercontent.com/56241745/112868123-e4795700-90e5-11eb-8ab6-3c52a1388b2c.png)
## LANGKAH 6
### Menambahkan Hyperlink. Tambahkan hyperlink pada dokumen sebelum heading 1.
~~~
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
~~~
![7](https://user-images.githubusercontent.com/56241745/112868160-f0651900-90e5-11eb-8b75-44d0767bfd1c.png)
## LANGKAH 7
### Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakan Hyperlink.
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

<h1>Halaman Ke 2</h1>

<p align="justify">Kami sedang belajar.</p>

</body>
</html>
~~~
![8](https://user-images.githubusercontent.com/56241745/112868212-feb33500-90e5-11eb-9602-99fbd75328f6.png)
## Jawab Pertanyaan Berikut
1. Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
~~~
Ada error ketika saya salah penulisan Heading <h1> tidak ditutup dengan </h1> jadi tidak terjadi perubahan.
~~~
2. Apa perbedaan dari tag `<p>` dengan tag `<br>` berikan penjelasannya!
~~~
Dari hasil praktek saya sendiri, perbedaan  tag <br> jarak enter nya lebih jauh 1 line dibandingkan
dengan tag <p> yg jarak enter nya tidak terlalu jauh.
~~~
3. Apa perbedaan atribut title dan alt pada tag `<img>`, berikan penjelasannya!
~~~
atribut tittle pada tag <img> digunakan untuk memberi judul pada gambar yg disisipkan, sedangkan
atribut alt pada tag <img> digunakan untuk memberi deskripsi pada gambar yg disisipkan
~~~
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
~~~
Untuk mempertahankan proporsi gambar, namun tetap membuat gambar menjadi besar/kecil, cantumkan
hanya salah satu atribut saja (width saja atau height saja, namun tidak keduanya). Misalkan
jika kita menetapkan atribut width=200px (tanpa mencantumkan height), maka web browser akan
menampilkan gambar dengan lebar 200px, dan menghitung secara otomatis tinggi gambar agar gambar
tetap proporsional.
~~~
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai antribut tersebut?
~~~
Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
~~~
