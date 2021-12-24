# Werehouse
## Halaman Utama Aplikasi

![Home](https://user-images.githubusercontent.com/61826116/147366302-ea7e92d2-0d90-4f6b-b250-0a8f088a5226.PNG)

## Deskripsi Aplikasi
Merupakan sebuah aplikasi berbasis web yang berfungsi untuk melakukan pendataan barang yang ada pada sebuah gudang. Diharapkan aplikasi werehouse nantinya akan membantudalam proses pendataan agar penyimpanan barang dapat tersusun dengan rapih juga mengetahui jumlah dari masing - masing barang.

## Sitemap / Hierarki Aplikasi & Penjelasan 

## Teknologi yang digunakan

## Cara Penggunaan Aplikasi 

## Fitur Aplikasi 

# Penjelasan Kode Program
## Model

## View

## Controller 
### Cetak.php

### Login.php

### Overview.php

![img 1](https://user-images.githubusercontent.com/61826116/147367127-034d8d66-4046-49d9-96aa-825608dc8cfb.jpg)

Code controller class Overview diatas berfungsi untuk menghubungkan model “user_model” dengan view “admin/overview”. 

•	Line 4- 9 pada fungsi __construct, controller akan me load model user_model, dibawahnya terdapat kondisi yaitu jika user belum melaukukan log in ( pada program dilakukan dengan
memanggil fungsi isNotLogin() pada model “user_model” ), maka user akan diarahkan pada halaman log in, jika tidak maka proses akan dilanjutkan.

•	Line 11 – 16 pada fungsi index, controller akan me load view overview dan akan menampilkan hasilnya pada website.


### Products.php

![img 2](https://user-images.githubusercontent.com/61826116/147367143-8d50209a-cbdb-41c3-bc9a-fe9756b0baf2.jpg)

Code controller class Products diatas berfungsi untuk menghubungkan model “user_model”, “product_model”, dan “pagination_model” dengan view “admin/products” .  

•	Line 5 -19 pada fungsi __construct, program akan me load model user_model, product_model, dan pagination_model. Selain itu juga library “form_validation” dibawahnya terdapat kondisi yaitu jika user belum melaukukan log in ( pada program dilakukan dengan memanggil fungsi isNotLogin() pada model “user_model” ), maka user akan diarahkan pada halaman log in, jika tidak maka proses akan dilanjutkan.

![img 3](https://user-images.githubusercontent.com/61826116/147367164-17543fca-857d-47df-820e-92126024fcf4.jpg)

Pada line 17 – 26 adalah bagian dari fungsi index, yang berfungsi untuk menampilkan data product pada view admin/products/list. Dimana akan digunakan pagination untuk membatasi jumlah data yang akan tampil per page. 

•	Line 21 controller akan me load library pagination, karena disini akan digunakan class pagination yang sudah ada di dokumentasi CodeIgniter 3. 

•	Line 24 proses config untuk base_url atau url awal adalah dengan menggunakan alamat http://localhost/werehouse/admin/products/index.

•	Line 25 proses config untuk total_rows atau jumlah seluruh baris data akan menggunakan fungsi jumlah_data yang ada di model pagination_model dengan mengembalikan hasil dari fungsi tersebut.

•	Line 26 proses config untuk per_page atau banyaknya data yang akan ditampilkan per halaman ditentukan sebanyak 2 baris data.

![img 4](https://user-images.githubusercontent.com/61826116/147367178-ca015533-71cb-4ec2-80c2-611ea0e4a7b8.jpg)

Line 28 – 52 adalah proses styling dari link pagination dengan menggunakan bantuan class pagination yang ada di Boostrap.

•	Line 32 – 34 adalah kustomisasi untuk First Link atau link halaman pertama.

•	Line 36 – 38 adalah kustomisasi untuk Last Link atau link halaman akhir.

•	Line 40 – 42 adalah kustomisasi untuk next link atau link halaman selanjutnya dengan menggunakan kode HTML &raquo atau tanda “ >> “.

•	Line 40 – 42 adalah kustomisasi untuk prev link atau link halaman sebelumnya dengan menggunakan kode HTML &laquo atau tanda “ << “.

•	Line 48 – 49 adalah kustomisasi untuk current page atau halaman saat ini dengan style nya dibedakan yaitu terdapat highlight warna biru pada tombonya.

•	Line 51 – 52 adalah kustomisasi untuk angka yang ada di tombol pagination.

![img 5](https://user-images.githubusercontent.com/61826116/147367188-2f936b9c-a1b7-47a6-8399-86350b7534dc.jpg)

•	Line 55 adalah kode program untuk melakukan konfigurasi atribut dengan memanggil class page-link yang ada di boostrap

![img 6](https://user-images.githubusercontent.com/61826116/147367198-73da573d-0934-4308-91b2-5dee20195051.jpg)

•	Line 59 adalah kode program untuk melakukan inisialisasi pagination dengan menggunakan parameter config.

•	Line 61 adalah kode program untuk menetapkan baris data awal pada tiap halaman, dimana program akan mengambil dari urutan uri segment ke 4.

•	Line 62 adalah kode program untuk menampilkan data pada halaman website dengan memanggil fungsi dataproduct yang ada di model “pagination_model” dengan parameter data per halaman menggunakan variable $config[‘per_page’] dan data awal per halaman menggunakan variable $data[‘start’].

•	Line 64 adalah kode program untuk menampilkan header website.

•	Line 65 adalah kode program untuk menampilkan list data product yang sudah menggunakan pagination.

•	Line 66 adalah kode program untuk menampilkan footer website.

![img 7](https://user-images.githubusercontent.com/61826116/147367214-92e3df43-da30-4c92-b25e-f894ac84436f.jpg)

Fungsi add () diatas digunakan saat user akan menambahkan data produk baru ke dalam database.

•	Line 71 untuk variable $product akan memanggil model “product_model”.

•	Line 72 untuk variable &validation akan menggunakan library form_validation yang ada di CodeIgniter 3. 

•	Line 73 variable &validation akan di set rule nya dengan memanggil fungsi rules yang ada di model “product_model”.

•	Line 75 adalah kondisi method run() mengembalikan TRUE dari variable $validation jika method tersebut berhasil menerapkan rules tanpa error.

•	Line 76 data pada variable $product akan disimpan ke dalam database.

•	Line 77 adalah kode program untuk menampilkan pesan sukses Ketika data berhasil disimpan .

•	Line 80 adalah kode program jika terjadi kondisi data tidak berhasil disimpan, maka pogram akan me load kembali tampilan view “admin/product/edit_form”.

![img 8](https://user-images.githubusercontent.com/61826116/147367223-09e5892f-d520-47b5-8422-e4739d8272b5.jpg)

Fungsi edit () diatas digunakan saat user akan melakukan update data produk ke dalam database dengan parameter variable $id.

•	Line 85 terdapat kondisi untuk mengecek jika variable $id belum ada maka user akan diarahkan ke “admin/products”.

•	Line 87 untuk variable $product akan memanggil model “product_model”.

•	Line 88 untuk variable &validation akan menggunakan library form_validation yang ada di CodeIgniter 3. 

•	Line 89 variable &validation akan di set rule nya dengan memanggil fungsi rules yang ada di model “product_model”.

•	Line 91 adalah kondisi method run() mengembalikan TRUE dari variable $validation jika method tersebut berhasil menerapkan rules tanpa error.

•	Line 92 hasil dari update data pada variable $product akan disimpan ke dalam database

•	Line 93 adalah kode program untuk menampilkan pesan sukses Ketika data berhasil disimpan 

•	Line 96 adalah kode program untuk menampilkan informasi data [“products”] dengan memanggil fungsi getById yang ada di model “product_model”.

•	Line 97 adalah kondisi jika informasi data tidak ditemukan maka akan tampil view error show_404().

•	Line 99 adalah kode program untuk me load view “admin/product/edit_form”.

![img 9](https://user-images.githubusercontent.com/61826116/147367227-5837f55e-61af-4652-9a94-a3c33d21c57e.jpg)

Fungsi delete () diatas digunakan saat user akan melakukan hapus data produk dari database dengan parameter variable $id.

•	Line 104 adalah kondisi untuk mengecek jika variable $id belum ada maka akan tampil view error show_404().

•	Line 106 adalah kode program untuk memanggil fungsi delete di model “product_model” dengan parameter variable $id.

•	Line 107 adalah kondisi jika proses delete berhasil maka user akan diarahkan ke url “admin/products”.
