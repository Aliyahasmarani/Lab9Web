# Lab9Web

# Praktikum 9: PHP Modular

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab9_php_modular pada docroot webserver
(htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.


## Langkah-langkah Praktikum

Buat file baru dengan nama header.php

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet"
    media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
        </nav>
```

Buat file baru dengan nama footer.php

```
<footer>
    <p>&copy; 2023, Informatika, Universitas Pelita Bangsa</p>
</footer>
</div>
</body>
</html>
```

Buat file baru dengan nama home.php

```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```

Buat file baru dengan nama about.php

```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

## Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang
database, sehingga setiap halamannya memiliki template tampilan yang sama. Laporan Praktikum

## Hasil

![image](https://github.com/Aliyahasmarani/Lab9Web/assets/115197672/40fd2f78-3afc-4506-b685-8d04feb9fd5f)

![image](https://github.com/Aliyahasmarani/Lab9Web/assets/115197672/0eca8656-535a-4dbf-9c6f-604ea5d4ad23)

![image](https://github.com/Aliyahasmarani/Lab9Web/assets/115197672/872b3020-a397-4464-97a6-2c09f50e9966)


