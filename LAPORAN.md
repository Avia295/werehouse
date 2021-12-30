# Werehouse
## Halaman Utama Aplikasi

![Home](https://user-images.githubusercontent.com/61826116/147366302-ea7e92d2-0d90-4f6b-b250-0a8f088a5226.PNG)

## Deskripsi Aplikasi
Merupakan sebuah aplikasi berbasis web yang berfungsi untuk melakukan pendataan barang yang ada pada sebuah gudang. Diharapkan aplikasi werehouse nantinya akan membantudalam proses pendataan agar penyimpanan barang dapat tersusun dengan rapih juga mengetahui jumlah dari masing - masing barang.

## Sitemap / Hierarki Aplikasi & Penjelasan 

![Hirarki App Werehouse](https://user-images.githubusercontent.com/61826116/147567792-4200d471-c37f-4efb-a695-790ffadb9cee.png)

Dalam aplikasi werehouse memiliki 4 page utama yaitu halaman log in, halaman beranda, halaman products dan halaman log out.
Pada halaman product terbagi menjadi 2 sub halaman yaitu halaman list barang dan halaman tambah barang. 
Kemudian pada halaman list barang terdapat beberapa fitur selain tampilan list barang yang ada, yaitu fitur print untuk melakukan print semua list data barang, fitur edit data untuk melakukan perubahan terkait informasi data barang dan akan diarahkan ke halaman edit,
fitur hapus untuk meghapus data barang dari database. Selain itu terdapat fitur tambah barang yang nantinya akan diarahkan ke halaman tambah barang

## Teknologi yang digunakan

Teknologi yang digunakan dalam program yaitu framework Codeigniter 3. Codeigniter 3 merupakan salah satu framework PHP yang sangat populer dengan konsep MVC dan sudah sering digunakan  oleh komunitas di seluruh dunia.  Keunggulan Codeigniter meliputi:
- Performa yang cepat, Codeigniter merupakan framework yang paling cepat dibandingkan framework lainna. Hal ini dipengaruhi oleh tidak ada penggunaan template engine dan ORM yang membuat proses menjadi lambat.
-  Konfigurasi yang minim,  dalam penyesuaian database serta keleluasan routing masih diizinkan melakukan konfigurasi dengan mengubah beberapa file konfigurasi, namun pada penggunaan Codeigniter dengan setting standar sudah dapat mengubah sedikit saja pada file dalam folder coding.
-  Banyak komunitas, komunitas Codeigniter di Indonesia cukup banyak sehingga dapat mencari tutoria penggunaan framework ini dengan mudah
-  Mudah dipelajari, untuk pemula, Codeigniter sangat mudah dipelajari karena tidak terlalu bergantung pada tool tambahan.
## Cara Penggunaan Aplikasi

1. Masuk ke dalam aplikasi dengan memasukkan username/email dan kata sandi.
![login](https://user-images.githubusercontent.com/71740342/147615804-8feb9a5d-df88-4004-9b6e-b5127936b2fb.jpg)

2. Setelah masuk aplikasi, aplikasi akan menampilkan beranda. Untuk memilih menu aplikasi, pengguna dapat memilihnya pada bagian kiri halaman, yaitu beranda, product dan keluar.
![beranda](https://user-images.githubusercontent.com/71740342/147615816-e7a184b5-d7a2-4654-b0b5-f54321a7ee73.jpg)

3. Pada menu product, pengguna dapat memilih antara tambah barang dan daftar barang.
![product_menu](https://user-images.githubusercontent.com/71740342/147615898-161aecb5-d1df-41af-b68f-69e29404420e.png)
![product1](https://user-images.githubusercontent.com/71740342/147615959-e471a818-00d7-4337-b939-ff3b8f9537d3.jpg)

4. Untuk pilihan tambah barang, pengguna dapat menambahkan barang meliputi nama barang, kuantitas barang, gambar barang dan keterangan barang.
![tambah_menu](https://user-images.githubusercontent.com/71740342/147615985-5980768d-9402-4ad9-843b-a6a8658b667e.png)
![tambah_barang](https://user-images.githubusercontent.com/71740342/147615923-e5a33e45-5f0a-4f27-8a05-68066cb4d93d.jpg)
![tambah_berhasil](https://user-images.githubusercontent.com/71740342/147624199-bf2574a2-ba88-4697-b9ee-b7a16e9f771d.jpg)

5. Untuk pilihan daftar barang, pengguna dapat melihat daftar barang serta dapat pergi ke halaman selanjutnya untuk melihat daftar barang lainnya dengan menekan button pagination di bawah.
![daftar_menu](https://user-images.githubusercontent.com/71740342/147615995-45a0908d-2e31-401b-9856-02ce2bf437ff.png)
![pagination_fitur](https://user-images.githubusercontent.com/71740342/147616019-a90f34af-a224-4ac7-95ef-f386b8d3572a.png)
![pagination2](https://user-images.githubusercontent.com/71740342/147616044-69cc398e-c6c5-4608-9827-05a68ac2987d.png)

6. Jika pengguna(admin) mencetak daftar barang maka dapat memilih fitur cetak. Dan halaman akan mengantarkan pengguna untuk mencetaknya. Dan jika pengguna ingin menambahkan data barang dari halaman daftar barang dapat menekan fitur 'Tambah Data' yang terletak di samping fitur 'Mencetak'.
![ceetak](https://user-images.githubusercontent.com/71740342/147616052-b0d71567-ed8f-4323-b321-30a0d2944474.png)
![cetak](https://user-images.githubusercontent.com/71740342/147616058-597ddc69-6e1b-48e4-aa29-c4eb80a74c95.jpg)

7. Lalu untuk mengubah isi dari record data barang pada tabel dapat memilih fitur sunting. Pada fitur tersebut, pengguna(admin) dapat mengubah nama barang, kuantitas barang, gambar barang dan keterangan barang.
![sunting](https://user-images.githubusercontent.com/71740342/147616076-435bec0c-83ed-4cd7-8e0f-759168091202.png)
![update](https://user-images.githubusercontent.com/71740342/147616086-72b3a88e-c329-4e81-a507-47bd2f0d7977.jpg)
 
8. Lalu untuk menghapus record data yang tidak diinginkan pada daftar barang dapat menekan fitur hapus.Setelah itu akn kembali pada halaman pertama daftar barang dan data yang dipilih tadi sudah terhapus.
![hapus](https://user-images.githubusercontent.com/71740342/147616113-5d2dd866-064f-4146-a0da-942abe1cc9e9.png)
![hapus](https://user-images.githubusercontent.com/71740342/147616121-e53fe7f0-7a45-459c-aa4f-27f8e0212d6e.jpg)

9 Pengguna(admin) dapat meninggalkan/keluar dari aplikasi dengan mengklik menu keluar.
![keluar_menu](https://user-images.githubusercontent.com/71740342/147616228-ead0c817-369e-44a9-9642-4c6112f6d263.png)
![keluar](https://user-images.githubusercontent.com/71740342/147616129-64d0ae98-b04b-4054-b079-e4947d943b74.jpg)

## Fitur Aplikasi 

1. Login
![login](https://user-images.githubusercontent.com/71740342/147612914-efae5178-aad8-42c2-8c64-780c0ca19cfd.jpg)
Fitur login dibutuhkan untuk memudahkan pengguna/admin untuk masuk ke dalam aplikasi karena tidak perlu repot memasukkan data pribadi seperti no.hp, alamat, tanggal lahir  saat ingin masuk ke dalam aplikasi.

2. CRUD
- Create
![tambah](https://user-images.githubusercontent.com/71740342/147613262-b5da06e6-6e87-44fb-b1e3-e2c4942d4166.jpg)
![tambah_berhasil](https://user-images.githubusercontent.com/71740342/147624199-bf2574a2-ba88-4697-b9ee-b7a16e9f771d.jpg)
Create berguna untuk membuat record baru pada sistem data. Create sering disebut dengan istilah insert. 
Pada aplikasi ini fitur create meliputi nama barang, kuantitas barang, gambar barang dan keterangan barang yang akan ditambahkan.

- Read 
![tampilkan](https://user-images.githubusercontent.com/71740342/147613244-70cddab8-c318-4513-a497-5b3f8677b929.jpg)
Read berguna untuk menampilkan dan membaca tabel data yang telah sesuai serta informasi data akan ditampilkan pada fitur ini.

- Update
![update](https://user-images.githubusercontent.com/71740342/147613350-f8f6cc31-cc26-4f5d-8140-6ab04683e751.jpg)
Update berguna untuk memperbaharui suatu tabel sesuai kata kunci utama (primary key) yang telah ditentukan pada sebuah record. 
Dalam aplikasi fitur ini dapat digunakan untuk mengubah nama barang, kuantitas barang, gambar barang dan keterangan barang.

- Delete
![hapus](https://user-images.githubusercontent.com/71740342/147613357-7e8c3a92-6c14-4f5f-b3ef-539333df28de.jpg)
Delete berguna untuk menghapus data yang tidak diinginkan pada tabel.

3. Pagination
![pagination](https://user-images.githubusercontent.com/71740342/147613643-03c33986-d262-414d-8969-c4cf8d8ed7cf.jpg)
Pagination merupakan fitur web yang digunakan untuk membatasi tampilan data agar terliat lebih rapi dan tidak terlalu panjang sehingga tidak perlu menggulir halaman tersebut. 
Pada aplikasi digunakan untuk menampilkan daftar penyimpanan barang pada sebuah gudang.

4. Cetak
![cetak](https://user-images.githubusercontent.com/71740342/147613740-c02b2788-b0cc-4b13-aea2-397ec055134f.jpg)
Fitur cetak atau print pada aplikasi ini berguna untuk mencetak daftar barang yang telah dibuat pada gudang.

5. Keluar
![keluar](https://user-images.githubusercontent.com/71740342/147613840-af421aac-85ae-483c-aa61-c26a840754a9.jpg)
Fitur keluar atau exit berguna untuk memudahkan pengguna(admin) untuk keluar dari aplikasi. 
# Penjelasan Kode Program
## Model
### Pagination_model

![Screenshot (16)](https://user-images.githubusercontent.com/61825704/147484664-91ff97f9-b868-4dac-b946-ed7a4d77e4d4.png)

kode Pagination_model diatas berfungsi untuk membuat pagination pada website. 

 - Line 6 - 8 pada fungction dataProduct berfungsi untuk mengambil data pada tabel products.
 - Line 11 - 13 pada function jumlah_data berfungsi untuk mengambil berapa banyak data yang ada pada tabel products saat ini.
 
### Product_model

 ![Screenshot (17)](https://user-images.githubusercontent.com/61825704/147714822-da943ffc-0dfc-4ccf-9bd6-cfd45bc4c5be.png)

kode Product_model berfungsi untuk proses CRUD pada produk yang akan ditampilkan dalam website.
 
 - Line 5 - 11 membuat variabel $_table, $product_id, $image, $name, $quantity, $description yang berfungsi untuk menampung data form yang diinput client.

![Screenshot (18)](https://user-images.githubusercontent.com/61825704/147714766-a9ce2972-490c-4f34-8d45-8764c2c9a22b.png)

 - Line 40 - 48 pada function save berfungsi untuk menyimpan inputan form yang dikirim melalui method POST dan menyimpannya ke dalam tabel product sebagai data produk baru. 
 - Line 42 data inputan disimpan kedalam **$post**.
 - Line 43 - 46 hasil inputan akan disimpan kedalam variabel $product_id, image, name, quantity, description.
 - Line 47 menginput data produk baru ke dalam tabel product.
 - Line 50 - 66 pada function update berfungsi untuk mengupdate isi tabel product dengan id tertentu .
 - Line 52 data inputan disimpan kedalam **$post**.
 - Line 53 - 64 hasil inputan akan disimpan kedalam variabel $product_id, image, name, quantity, description.
 - Line 65 mengupdate data produk yang baru untuk menggantikan data produk lama yang memiliki id = '$id'.
 
 ![Screenshot (19)](https://user-images.githubusercontent.com/61825704/147487407-e9726f29-b88a-47c6-8edd-91fe610002b0.png)
 
 - Line 68 - 72 pada function delete berfungsi untuk menghapus data produk dengan id = '$id' pada tabel products.
 - Line 70 memanggil fungsi _deleteImage untuk menghapus image.
 - Line 71 menghapus data produk dengan id = 'id'.
 - Line 74 - 91 pada function _uploadImage berfungsi untuk mengupload image dengan ketentuan tertentu.
 - Line 76 - 80 mengkonfigurasi image yang akan diupoad seperti lokasi, tipe file image, nama file, ukuran file, dll.
 - Line 84 memanggil library upload .
 - Line 86 - 88 melakukan uploading image dan id image.
 - Line 90 mengembalikan nilai "default.jpg yang berfungsi bila tidak ada file image yang diupload".
 -  Line 93 - 100 pada function _deleteImage berfungsi untuk menghapus gambar dengan id = '$id'.
 - Line 93 mengambil data product yang memiliki id = '$id'.
 - Line 96 - 99 melakukan penghapusan image apabila image tidak bernilai "default.jpg".
 
### User_model

 ![Screenshot (20)](https://user-images.githubusercontent.com/61825704/147489978-db3222b2-c6f2-41e4-bf51-4112173e159f.png)
 
kode User_model berfungsi untuk proses Login, Logout dan pengelolaan akun pada website.
 
 - Line 5 - 11 membuat variabel $_tabel, $user_id, $full_name, $password, $email, $role yang berfungsi untuk menampung data form yang diinput client.
 - Line 13- 28 pada function rules berfungsi untuk inisialisasi form validation dengan menyiapkan array assosiatif yang berisi data form yang akan divalidasi seperti field, label dan rules pada form yang akan divalidasi.

 ![Screenshot (22)](https://user-images.githubusercontent.com/61825704/147490248-ec67b1dd-3181-48b1-8492-75f3b9d0c45a.png)
	
 - Line 60 - 77 pada function doLogin berfungsi untukverifikasi login apakah username dan password benar jika benar maka akan diarahkan kedalam dashboard jika salah maka akan dikembalikan di laman login.
 - Line 61 data inputan disimpan kedalam **$post**
 - Line 63 - 65 mengambil data pada tabel user yang memiliki email = email input dan username = username input.
 - Line 67 - 75 berfungsi untuk memverifikasi password input dan role admin. jika benar maka user akan diberikan akses login dan data updatelastlogin akan disimpan.
 - Line 79 - 81 berfungsi untuk memeriksa apakan akun sudah login atau belum.
 - Line 83 - 86 berfungsi untuk mengupdate riwayat user login kedalam tabel user.
## View
### breadcrumb.php
![image](https://user-images.githubusercontent.com/76147557/147533456-16c6f13e-dea1-4f04-b094-b8ff7a86f8de.png)

kode breadcrumb.php berfungsi untuk menampilkan sistem navigasi sekunder yang menunjukkan lokasi pengguna di situs web.

-  Line 2 berfungsi untuk me-load class "breadcrumb" dari bootstrap.
-  Line 3 - 18 menggunakan perulangan foreach, berfungsi untuk mengambil data dalam bentuk array yang akan ditampilkan berupa URI.
- Line 10 - 15 menggunakan percabangan if untuk menampilkan URI yang sudah diidentifikasi dan mampu mendirect ke site URL.

### footer.php
![image](https://user-images.githubusercontent.com/76147557/147534948-3b8e25ea-8a8e-4ad8-87c5-5c334687cc7d.png)

kode footer.php berfungsi untuk menampilkan catatan atau tulisan yang berada di bagian bagian bawah website.

- Line 2 - 8 me-load css. lalu menampilkan tulisan Copyright Werehouse dan tahun menggunakan tag span.

### head.php
![image](https://user-images.githubusercontent.com/76147557/147535524-58284a47-49d2-4b84-b8be-a05d215fbc9b.png)

Kode head.php berfungsi untuk menampilkan tulisan yang berada di bagian atas website sekaligus untuk me-load file css.

- Line 5 berfungsi untuk menampilkan tulisan Werehouse.
- Line 8 berfungsi untuk meload bootstrap.min.css yang di dalamnya berisi inti utama css bootstrap.
- Line 11 berfungsi untuk meload all.min.css yang di dalamnya berisi custom font.
- Line 14 berfungsi untuk meload dataTables.bootstrap4.css yang digunakan sebagai pagination. Fungsi ini tidak digunakan namun tetap disimpan karena beralih menggunakan fungsi pagination yang tersedia di codeigniter 3.
- Line 17 berfungsi untuk meload sb-admin.css yang digunakan sebagai template style.

### js.php
![image](https://user-images.githubusercontent.com/76147557/147536395-b37335ae-5f1c-40a1-b95a-6e43f0bd84fc.png)

kode js.php berfungsi untuk meload file JavaScript.

- Line 2 - 3 berfungsi untuk meload inti JavaScript Bootstrap.
- Line 6 berfungsi untuk meload inti masukkan JavaScript.
- Line 8 - 10 berfungsi untuk meload fungsi pagination. Fungsi ini tidak digunakan namun tetap disimpan karena beralih menggunakan fungsi pagination yang tersedia di codeigniter 3.
- Line 12 berfungsi untuk meload JavaScript template.
- Line 14 - 15 berfungsi untuk meload skrip demo.

### modal.php
![1](https://user-images.githubusercontent.com/75412705/147575248-be89d191-e4ca-49d0-9530-b8e4976b1a1f.png)

Kode modal.php berfungsi untuk menampilkan dialog atau yang biasa kita sebut dengan popup.
- Line 2 berfungsi untuk memberikan efek fade atau efek memudar pada saat pemunculan dan penutupan modal.
- Line 3 - 4 berfungsi sebagai container.
- Line 5 - 10 digunakan sebagai header.
- Line 11 digunakan sebagai body dan akan menampilkan dialog.
- Line 12 - 15 berfungsi sebagai footer.
- Line 22 berfungsi untuk memberikan efek fade atau efek memudar pada saat pemunculan dan penutupan modal.
- Line 23 -24 berfungsi sebagai container.
- Line 25 - 30 digunakan sebagai header.
- Line 31 digunakan sebagai body dan akan menampilkan dialog.
- Line 32 - 35 berfungsi sebagai footer.

### navbar.php
![2](https://user-images.githubusercontent.com/75412705/147575420-62ef1800-4684-4500-9069-c383790759c7.png)

Kode navbar.php merupakan komponen berupa menu yang terletak pada website.
- Line 1 digunakan untuk membuat navigation bar dengan model yang sudah ditentukan.
- Line 3 digunakan untuk mendefinisikan judul website.
- Line 5 - 7 digunakan untuk membuat tombol.
- Line 10 - 20 digunakan untuk membuat menu dropdown.

### scrolltop.php
![image](https://user-images.githubusercontent.com/76147557/147570972-f688b5e2-2bb8-45cd-9dcd-c7cb7dd6abb1.png)

kode scrolltop.php digunakan untuk direct ke #page-top, dimana #pagetop ini sendiri akan digunakan di head.php.

- Line 2 - 4 berfungsi untuk men-direct ke #page-top.

### sidebar.php
![image](https://user-images.githubusercontent.com/76147557/147571224-4d675126-9ddf-4be3-9f7e-1631285a206f.png)

kode sidebar.php digunakan untuk menampilkan icon atau tulisan di area samping website.

- Line 2 digunakan untuk mengatur letak dan warna sidebar menggunakan template bootstrap.
- Line 3 - 8 digunakan untuk menampilkan tulisan "Beranda" dan jika ditekan maka akan mendirectnya ke halaman overview.
- Line 9 - 13 digunakan untuk menampilkan tulisan "Products" dan jika ditekan akan dropdown menu lain.
- Line 15 - 18 berupa hasil dropdown tulisan "Products". Menu dropdown berupa "Tambah Barang" yang akan mendirect ke halaman products/add dan "List Barang" yang akan mendirect ke halaman products.
- Line 20 - 22 digunakan untuk menampilkan tulisan "Logout" dan jika ditekan maka akan muncul box logout.

### login_page.php
![3](https://user-images.githubusercontent.com/75412705/147575465-a5f1ed19-c6ae-4d3e-bf1b-08632cd91e6f.png)

Kode login_page.php berfungsi untuk login bagi admin / pengguna.
- Line 2 digunakan untuk mengubah bahasa file tersebut.
- Line 5 - 8 adalah judul yang muncul di halaman pencarian.
- Line 11 digunakan untuk memanggil bootstrap.
- Line 16 - 22 digunakan untuk menampilkan judul halaman.
- Line 23 - 50 digunakan untuk menampilkan form dari login.

### overview.php
![4](https://user-images.githubusercontent.com/75412705/147575507-63ab3e31-150d-4008-bb75-0372c8b2c0ce.png)

Kode overview.php berfungsi untuk tampilan beranda atau halaman setelah melakukan login.
- Line 2 digunakan untuk mengubah bahasa file tersebut.
- Line 4 digunakan untuk memanggil view bernama head.php.
- Line 8 digunakan untuk memanggil view bernama navbar.php.
- Line 12 digunakan untuk memanggil view bernama sidebar.php.
- Line 18 digunakan untuk memanggil view bernama breadcrumb.php.
- Line 20 untuk menampilkan judul halaman.
- Line 23 digunakan untuk memanggil view bernama footer.php.
- Line 32 digunakan untuk memanggil view bernama scrolltop.php.
- Line 33 digunakan untuk memanggil view bernama modal.php.
- Line 34 digunakan untuk memanggil view bernama js.php.

### print.php
![5](https://user-images.githubusercontent.com/75412705/147575552-4c0e26b5-3be3-4af5-8b37-ee3e7279d3d6.png)

Kode print.php berfungsi untuk mencetak tampilan pada list barang.
- Line 4 digunakan untuk menamai halaman.
- Line 7 - 14 digunakan untuk membuat tabel.
- Line 22 digunakan untuk menampilkan isi variabel dari id.
- Line 23 digunakan untuk menampilkan isi variabel dari name.
- Line 24 digunakan untuk menampilkan isi variabel dari quantity.
- Line 25 digunakan untuk menampilkan isi variabel dari image.
- Line 26 digunakan untuk menampilkan isi variabel dari description.
- Line 32 - 34 digunakan untuk menampilkan jendela print.

## Controller 
### Cetak.php

![cetak_c](https://user-images.githubusercontent.com/71740342/147619831-247dd959-0951-4977-abfa-ab6133ac11a0.jpg)
Code controller class Cetak berfungsi untuk menghubungkan "product_model" dan "user_model" dengan view yang bernama "print.php".
- Line 4-10 terdapat fungsi_construct dimana dalam fungsi tersebut memuat model "product_model" dan "user_model". Pada line 9 terdapat kondisi dimana jika user belum melakukan login maka akan diarahkan ke halaman login terlebih dahulu tetapi jika user telah melakukan login maka proses akan berlanjut.
- Line 11-17 terdapat fungsi index dimana dalam fungsi tersebut yang terletak pada line 12 ada kode program untuk menampilkan data dengan memanggil fungsi getAll yang terdapat dalam model "product_model". Lalu pada line 13, meload view yang bernama "print.php".
### Login.php

![login_c](https://user-images.githubusercontent.com/71740342/147622167-293cb565-2503-417a-9419-3e6e66d3a601.jpg)controller class Login berguna untuk menghubungkan model "user_model" dan library "form_validation" dengan view bernama "login_page.php".
- Line 5-11 terdapat fungsi_construct yang memuat model "user_model" dan library "form_validation".
- Line 13-19 terdapat fungsi index, dalam fungsi tersebut terdapat kondisi dimana jika user telah melakukan login maka akan diarahkan ke halaman overview, sedangkan jika belum melakukan login maka akan me load view yang bernama "login_page.php".

![login_c2](https://user-images.githubusercontent.com/71740342/147622178-ad4bb70b-d00e-45d4-8e21-32297fd8aed2.jpg)
- Line 21-25 terdapat fungsi logout() terdapat fungsi logout, fungsi ini berguna untuk menghapus sesi yang dimiliki user. Lalu setelah itu akan mengarahkan user ke halaman login untuk keluar dari aplikasi.
- Line 27-33 terdapat fungsi test, fungsi ini berguna untuk mengeset media type pada halaman sehingga dapat menyajikan data JSON, JPEG, XML dengan mudah.

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
