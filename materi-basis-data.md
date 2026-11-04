# Belajar Basis Data

## Agenda
- Basis Data
- Sistem Basis Data
- Basis Data Relational
- Model Data
- Model Data Relational
- Normalisasi Data
- Denormalisasi Data
- Aplikasi Sistem Basis Data

# BASIS DATA
## Pendahuluan
- Basis data (database) bisa diibaratkan seperti lemari arsip.
- Seandainya kita bertugas mengelolanya, tentu kita akan merapikan data arsip dilemari tersebut, dari mulai memberi tanda, mengelompokkan arsipnya, dan lain-lain.
- Tujuannya adalah, agar ketika kita ingin mencari arsip, kita bisa dengan mudah mencarinya, karena sudah mengatur tata letak arsip di lemari tersebut.

## Diagram Arsip

Lemari dengan beberapa laci, disebelahnya terdapat beberapa folder arsip Pegawai, Pelanggan, Penjualan, Pembelian

## Apa itu Basis Data?
- Basis Data terdiri dari dua kata, Basis dan Data
- Basis bisa diartikan, tempat, gudang atau tempat menyimpan
- Data adalah representasi fakta dari dunia nyata, yang mewakili suatu objek, seperti manusia (karyawan, pelajar, mahasiswa, guru, dan lain-lain), barang, hewan, peristiwa, dan lain-lain. Data biasanya disimpan dalam bentuk angka, huruf, simbol, teks, gambar, dan lain-lain
- Basis Data biasanya disimpan didalam media penyimpanan berbasis disk (seperti hardisk, flahdisk), hal ini agar data disimpan secara permanen
- Tapi ingat, tidak semua yang disimpan di disk itu bisa dibilang Basis Data, karena tujuan utama dalam Basis Data adalah pengaturan, pemilihan, pengelompokan dan pengorganisasian data yang baik

## Diagram Basis Data
Disk disebelahnya terdapat beberapa folder arsip Pegawai, Pelanggan, Penjualan, Pembelian

## Operasi Basis Data
- Di dalam disk, basis data bisa dibuat atau juga dihapus atau juga diubah. Dan biasanya kita akan buat basis data dalam file berbeda tergantung jenis datanya, misal file pegawai, pelanggan, penjualan dan lain-lain
- Dalam basis data, operasi basis data dikenal dengan operasi CRUD (Create, Read, Update dan Delete)
- Create, untuk membuat data baru
- Read, untuk membaca / mencari data
- Update, untuk mengubah data yang sudah ada
- Delete, untuk menghapus data

## Tujuan Basis Data

- Speed, kecepatan dalam mengambil / mencari data
- Space, efisiensi dalam ruang penyimpanan
- Accuracy, data yang akurat 
- Availability, ketersediaan data
- Completeness, kelengkapan data
- Security, keamanan data
- Shareability, kemudahan berbagi data

## Contoh Penerapan Basis Data
- Bank, dalam mengelola data nasabah, tabungan, transaksi, dan lain-lain
- Rumah sakit, dalam mengelola data pasien, history rawat, dokter dan lain-lain
- Sekolah, dalam mengelola data guru, pelajar, mata pelajaran, nilai ujian, dan lain-lain
- Toko Online, dalam mengelola data pelanggan, penjualan, barang, pembelian, pengiriman, dan lain-lain


# SISTEM BASIS DATA

## Pendahuluan
- Sistem Basis Data
- Basis data (database) perlu ada yang melakukan pengolahan datanya
- Pengelola basis data adalah program / aplikasi (software / perangkat lunak)
- Gabungan aplikasi pengelola dan basis datanya, kita sebut dengan nama sistem basis data (database management system)

## Diagram Sistem Basis Data
Gambar komputer yang sedang membuka aplikasi yang didalamnya beberapa database yang didalamnya terdapat data/file.

## Komponen Sistem Basis Data
- Hardware (perangkat keras), komputer, laptop, server dan lain-lain
- Sistem Operasi, seperti Windows, Mac OS, Linux, dan lain-lain
- Aplikasi Basis Data, seperti MySQL, PostgreSQL, SQL Server, dan lain-lain
- User, pengguna seperti programmer, database admin, end user dan lain-lain
- Aplikasi lain, yang menggunakan basis data, seperti web, desktop, dan lain-lain

## Komponen Sistem Basis Data
Gambar komputer yang sedang membuka aplikasi yang didalamnya beberapa database yang didalamnya terdapat data/file, kemudian diluar komputer tedapat gambar end user, programer, dan web

## Bahasa Basis Data
- Sistem basis data merupakan perantara antara basis data dan pengguna (orang ataupun aplikasi lain)
- Biasanya untuk mengelola basis data, kita akan menggunakan bahasa basis data, sesuai dengan sistem basis data yang kita gunakan
- Secara garis besar, dalam bahasa basis data terdapat dua jenis perintah :
- DDL (Data Definition Language), dan 
- DML (Data Manipulation Language)

## Data Definition Language
- DDL merupakan perintah-perintah dalam bahasa basis data untuk membuat struktur bentuk dari basis data yang akan kita buat
- Misalnya perintah untuk membuat, mengubah atau menghapus basis data (arsip), tempat menyimpan tabel (file)
- Perintah untuk membuat, mengubah, menghapus table (tempat menyimpan data)
- Selain itu, dalam DDL kita juga perlu menentukan kamus data dari tiap table yang kita buat, seperti nama-nama kolom di tabel nya dan tipe data untuk kolom di tabel nya

## Data Manipulation Language
- DML merupakan perintah-perintah dalam bahasa basis data untuk memanipulasi data setelah kita buat struktur basis datanya menggunakan DDL
- Misalnya menambah, mengubah, menghapus, mencari data di tabel

## Diagram Bahasa Basis Data
Programer melakukan perintah bahasa basis data ke sistem basis data yang terdapat basis data.