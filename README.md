**SOFTWARE REQUIREMENTS SPECIFICATION**



**Disusun Oleh:**

Dimas Adrian (2355301053)

Nur Muhammad Maulanal Hakim (2355301166)

Syafrisar Putri Cadasteria (2355301193)

**PROGRAM STUDI TEKNIK INFORMATIKA**

**POLITEKNIK CALTEX RIAU**

**TA 2024/2025**

# BAB I Pendahuluan  {#bab-i-pendahuluan}

## 1.1 Tujuan {#tujuan}

Dokumen Software Requirement Specification (SRS) merupakan dokumen
spesifikasi perangkat lunak untuk membangun "Website Profile Company
UMKM kantin Afwah". Dokumen ini dibangun untuk memudahkan public untuk
mengenal UMKM kantin afwah dan memudahkan pemilik kantin dalam
mempromosikan usahanya ke public. Sehingga dokumen ini dapat dijadikan
acuan teknis untuk membangun perangkat lunak "Website Profile Company
UMKM kantin Afwah".

## 

## 1.2 Lingkup {#lingkup}

Website Profile Company UMKM kantin Afwah Merupakan website Untuk
mempermudah pemilik usaha kantin afwah untuk mempromosikan usahanya
serta memberi informasi ke public tentang usahanya melalui Website
Profile Company UMKM kantin Afwah.

## 1.3 Akronim, singkatan, definisi {#akronim-singkatan-definisi}

| Istilah                            | Definisi                                                                                     |
|------------------------------------|----------------------------------------------------------------------------------------------|
| SRS                                | Software Requirement Specification                                                           |
| Login                              | Digunakan untuk mengakses website halaman admin                                              |
| Software Requirement Specification | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| Use Case                           | situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

## 1.4 Referensi {#referensi}

Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah:

[[https://www.mcdonalds.co.id/]{.underline}](https://www.mcdonalds.co.id/)

## 1.5 Overview {#overview}

Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada website.
Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan
alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang
digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari
aplikasi yang akan diterapkan pada website yang dibuat.

# BAB II Gambaran Umum

Kantin Afwah merupakan suatu UMKM yang bergerak pada bidang makanan dan
minuman.Dalam project ini,kami merancang website company profile dari
Kantin Afwah yang bertujuan untuk menampilkan informasi - informasi dari
Kantin ini.Selain itu,pada website ini juga menyediakan berbagai fitur
lainya seperti menu,kontak,lokasi,dan juga customer dapat menyampaikan
pesan beserta sarannya.Berikut adalah penjelasan dari fitur - fitur yang
kami sediakan,

Customer fungsi utama yaitu:

- View Menu

- Input Pesan Saran

- View Promo

- View Gallery

- View About Us

- View Kutipan

- View Slider

Berikut Fungsi admin:

- Login

- Input Pesan Saran

- Input Promo

- Input Gallery

- Input About Us

- Input Kutipan

- Input Slider

- Edit Pesan Saran

- EditPromo

- EditGallery

- Edit About Us

- Edit Kutipan

- Edit Slider

- Delete Pesan Saran

- Delete Promo

- Delete Gallery

- Delete Kutipan

- Delete Slider

## 2.1 Perspektif produk {#perspektif-produk}

Sistem Kantin Afwah adalah sebuah sistem yang menyediakan informasi
Kantin Afwah yang diaplikasikan pada website. Terdapat 2 aktor yaitu
admin dan pengunjung. Data informasi pada website dikelola oleh admin
dan pengunjung hanya dapat melihat informasi tersebut pada websit

###  **2.1.1 Antarmuka Sistem** {#antarmuka-sistem}

![](media/image21.png){width="5.28125in" height="6.364583333333333in"}

Sistem Kantin Afwah memiliki 2 pengguna yaitu admin dan pengunjung.
Admin berfungsi mengelola data informasi dan Pengunjung bisa melihat
informasi serta memberi pesan dan saran.

###  2.1.2 Antarmuka Pengguna {#antarmuka-pengguna}

Halaman Admin

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.1%20Admin%20Login.png"
style="width:3.10417in;height:1.47222in" /></p>
<p>Halaman login, admin diminta untuk memasukkan username dan
password</p></th>
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/dashboardadmin.png"
style="width:3.10417in;height:1.43056in" /></p>
<p>Setelah login, admin akan masuk ke Dashboard admin</p></th>
</tr>
<tr class="odd">
<th><p><img src="public/home.png"
style="width:3.10417in;height:1.43056in" /></p>
<p>Pada halaman ini juga terdapat halaman untuk admin mengelola data
menu, bukan hanya menu tetapi admin juga dapat mengelola data about us,
kutipan, slider, promo, galeri, pesan saran pada halaman ini</p></th>
<th><p><img src="media/image20.png"
style="width:3.10417in;height:1.44444in" /></p>
<p>Pada halaman menu, admin dapat menambah daftar menu baru. Begitu juga
pada pengelolaan data lain nya</p></th>
</tr>
<tr class="header">
<th><p><img src="media/image10.png"
style="width:3.10417in;height:1.47222in" /></p>
<p>Pada halaman menu juga terdapat aksi untuk mengedit daftar
menu</p></th>
<th><p><img src="media/image9.png"
style="width:3.10417in;height:3.88889in" /></p>
<p>Pada halaman menu, selain untuk menambahkan dan mengedit, admin juga
dapat menghapus data menu</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

Halaman User

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><img src="media/image22.png"
style="width:3.10417in;height:1.22222in" /></p>
<p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/home.png"
style="width:3.10417in;height:1.44444in" /></p>
<p>Pada halaman pengunjung terdapat sebuah beranda yang berisi tampilan
scrolling yang berisi konten seperti slider, promo, kutipan dan
menu</p></th>
<th><p><img src="media/image27.png"
style="width:3.10417in;height:1.45833in" /></p>
<p>Pada halaman pengunjung terdapat Menu yang berisi nama makanan,
harga, gambar dan deskripsi harga serta daftar menu makanan dan minuman
dipisah</p></th>
</tr>
<tr class="odd">
<th><p><img src="media/image26.png"
style="width:3.10417in;height:1.48611in" /></p>
<p>Pada halaman pengunjung juga terdapat halaman promo yang berisikan
informasi promo promo yang ada</p></th>
<th><p><img src="media/image19.png"
style="width:3.10417in;height:1.44444in" /></p>
<p>Pada halaman pengunjung terdapat Galery yang menampilkan foto foto
seputar UMKM</p></th>
</tr>
<tr class="header">
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/aboutus.png"
style="width:3.10417in;height:1.45833in" /></p>
<p>Pada halaman pengunjung terdapat halaman About Us yang berisi
informasi pengelola dan UMKM</p></th>
<th><p><img src="media/image8.png"
style="width:3.10417in;height:1.47222in" /></p>
<p>Pada halaman pengunjung terdapat halaman Pesan Saran yang berisi
informasi Pesan saran dari pengunjung</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

###  2.1.3 Antarmuka perangkat keras {#antarmuka-perangkat-keras}

![](media/image23.png){width="5.630208880139983in"
height="4.791090332458443in"}

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat
Lunak Sistem kantin Afwah yaitu :

PC / laptop Untuk Menjalankan Aplikasi

###  2.1.4 Antarmuka Perangkat lunak {#antarmuka-perangkat-lunak}

Tidak ada

###  2.1.5 Antarmuka Komunikasi {#antarmuka-komunikasi}

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak
Sistem kantin Afwah yaitu :

- PC

- Jaringan/Wifi

###  2.1.6 Batasan Memory {#batasan-memory}

Tidak ada

###  2.1.7 Operasi-operasi {#operasi-operasi}

| Operasi    | Fungsi                             |
|------------|------------------------------------|
| Login      | Digunakan untuk mengakses aplikasi |
| Input Data | DIgunakan untuk memasukkan data    |
| Hapus      | Digunakan untuk menghapus data     |
| Edit       | Digunakan untuk mengubah data      |
| View       | Digunakan untuk menampilkan data   |
| Simpan     | Digunakan untuk menyimpan data     |

### 

###  2.1.8 Kebutuhan Adaptasi {#kebutuhan-adaptasi}

Tidak ada

## 

## 2.2 Spesifikasi kebutuhan fungsional {#spesifikasi-kebutuhan-fungsional}

![](media/image5.png){width="4.075166229221347in"
height="7.658162729658793in"}

### 2.2.1 Admin Login {#admin-login}

Use Case: Login

Diagram:

![](media/image4.png){width="5.541666666666667in"
height="1.7604166666666667in"}

Deskripsi Singkat

Admin melakukan login terlebih dahulu sebelum masuk ke tampilan home
admin, apabila gagal login akan muncul pesan alert error login.

Deskripsi Langkah-Langkah

1.  Admin melakukan login dengan username dan password.

2.  Sistem melakukan validasi login.

3.  Bila sukses sistem akan mengarahkan ke home admin.

4.  Bila gagal sistem akan menampilkan peringatan.

Xref: Bagian 3.2.1, Login Admin

### 

### 2.2.2 Admin input Menu {#admin-input-menu}

Deskripsi Singkat  
Sistem dapat menampilkan halaman input menu dan Admin menginputkan menu.

![](media/image18.png){width="4.5517475940507435in"
height="2.713542213473316in"}

Deskripsi Langkah- langkah:

1.  Sistem akan menampilkan tampilan daftar menu.

2.  Admin dapat melihat,menambahkan, dan mengupload gambar menu.

3.  Sistem akan menyimpan ke database.

Xref: Bagian 3.2.2, Input data Menu

### 2.2.3 Admin input Slide {#admin-input-slide}

Deskripsi Singkat  
Sistem dapat menampilkan halaman input slide dan Admin menginputkan
slide.

![](media/image12.png){width="4.859375546806649in"
height="1.2990409011373578in"}

Deskripsi Langkah- langkah:

4.  Sistem akan menampilkan tampilan daftar slide.

5.  Admin dapat melihat,menambahkan, dan mengupload gambar slide.

6.  Sistem akan menyimpan ke database.

7.  sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.3, Input data slide

### 2.2.4 Admin input about us {#admin-input-about-us}

Deskripsi Singkat  
Sistem dapat menampilkan halaman input about dan Admin menginputkan
about.

![](media/image3.png){width="4.895833333333333in"
height="3.1399770341207347in"}

Deskripsi Langkah- langkah:

8.  Sistem akan menampilkan tampilan daftar about.

9.  Admin dapat melihat,menambahkan, dan mengupload gambar about.

10. Sistem akan menyimpan ke database.

Xref: Bagian 3.2.4, Input data about

### 2.2.5 Admin input galery {#admin-input-galery}

Deskripsi Singkat  
Sistem dapat menampilkan halaman input galery dan Admin menginputkan
galery..

![](media/image13.png){width="4.619792213473316in"
height="2.454961723534558in"}

Deskripsi Langkah- langkah:

11. Sistem akan menampilkan tampilan daftar galery.

12. Admin dapat melihat,menambahkan, dan mengupload gambar galery.

13. Sistem akan menyimpan ke database.

14. sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.5, Input data galery

### 2.2.6 Admin input Promo {#admin-input-promo}

Deskripsi Singkat Sistem dapat menampilkan halaman input promo dan Admin
menginputkan promo.

![](media/image2.png){width="4.182292213473316in"
height="3.5367639982502186in"}

Deskripsi Langkah- langkah:

15. Sistem akan menampilkan tampilan daftar promo.

16. Admin dapat melihat,menambahkan, dan mengupload gambar promo.

17. Sistem akan menyimpan ke database.

18. sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.6, Input data promo

### 2.2.7 Admin input Kutipan {#admin-input-kutipan}

Deskripsi Singkat Sistem dapat menampilkan halaman input kutipan dan
Admin menginputkan kutipan.

![](media/image6.png){width="4.171875546806649in"
height="2.0270122484689415in"}

Deskripsi Langkah- langkah:

19. Sistem akan menampilkan tampilan daftar kutipan.

20. Admin dapat melihat,menambahkan, dan mengupload gambar kutipan.

21. Sistem akan menyimpan ke database.

Xref: Bagian 3.2.7, Input data kutipan

### 2.2.8 Admin Mengelola Pesan Saran {#admin-mengelola-pesan-saran}

Deskripsi Singkat Sistem dapat menampilkan halaman mengelola pesan saran
dan Admin menginputkan pesan saran.

![](media/image15.png){width="3.4591688538932632in"
height="1.97001968503937in"}

Deskripsi Langkah- langkah:

22. Sistem akan menampilkan tampilan daftar pesan saran.

23. Admin dapat melihat,membalas pesan saran..

24. Sistem akan menyimpan ke database.

25. sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.8, Input data pesan saran

### 2.2.9 Pengunjung mengunjungi website {#pengunjung-mengunjungi-website}

![](media/image14.png){width="4.015625546806649in"
height="2.227354549431321in"}

Deskripsi Singkat

pengunjung mengunjungi website dan melihat informasi yang ada pada
website seperti informasi seputar menu makanan, pengunjung juga dapat
memberikan pesan saran.

Deskripsi Langkah-Langkah

- Sistem akan menampilkan halaman-halaman konten.

- pengunjung melihat melihat informasi yang ada pada website seperti
  > informasi seputar menu makanan, pengunjung juga dapat memberikan
  > pesan saran..

## 

## 2.3 Spesifikasi Kebutuhan non Fungsional {#spesifikasi-kebutuhan-non-fungsional}

- Table Kebutuhan non fungsional

| no  | Deskripsi                                                                |
|-----|--------------------------------------------------------------------------|
| 1   | Semua interface dan fungsi menggunakan Bahasa Indonesia                  |
| 2   | Perangkat Lunak dapat dipakai di semua platform OS ( Admin, pengunjung ) |

## 2.4 Karakteristik Pengguna {#karakteristik-pengguna}

Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung
berinteraksi dengan website, dan login untuk admin.

## 2.5 Batasan-batasan {#batasan-batasan}

Tidak ada

## 2.6 Asumsi-asumsi {#asumsi-asumsi}

Tidak ada

## 2.7 Kebutuhan Penyeimbang {#kebutuhan-penyeimbang}

Tidak ada

# 

# BAB III Requirement Specification

## 3.1 Persyaratan Antarmuka Eksternal {#persyaratan-antarmuka-eksternal}

Untuk admin yang akan mengakses website ini diperlukan registrasi
terlebih dahulu, kemudian akan login dengan memasukkan username dan
password, lalu sistem akan validasi login. Setelah login berhasil Admin
dapat melihat tampilan admin yang ada di website tersebut. Untuk
pengunjung hanya perlu membuka halaman website, kemudian pengunjung
dapat melihat konten yang ada di website tersebut.

## 3.2 Functional Requirement {#functional-requirement}

## 3.2.1 Admin Login {#admin-login-1}

<table>
<colgroup>
<col style="width: 23%" />
<col style="width: 76%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Login</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.1 Admin Login</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin Membuka Website Kantin Afwah</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Halaman Login</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Admin melakukan login dengan username dan password</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Sistem memvalidasi login</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Jika berhasil, sistem akan mengarahkan ke home admin</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Jika gagal, sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat login dan mengakses website Kantin Afwah</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Username dan password salah</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.2 Admin Input Menu {#admin-input-menu-1}

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Menu</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.2 Admin Input Menu</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan menu</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan menu Kantin Afwah ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan menu Kantin Afwah</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, mengedit dan menghapus menu</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="header">
<th>Post Condition</th>
<th>Admin dapat menginputkan menu makanan Kantin Afwah seperti nama
makanan, harga, deskripsi dan gambar makanan</th>
</tr>
<tr class="odd">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 

## 3.2.3 Admin Input Slide {#admin-input-slide-1}

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Slide</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.3 Admin Input Slide</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan slide</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan slide ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan slide</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, mengedit dan menghapus slide</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat menginputkan slide berupa foto</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

> 3.2.4 Admin Input About Us

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input About Us</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.4 Admin Input About Us</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan about us</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan about us ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan about us</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, dan mengedit about us</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="header">
<th>Post Condition</th>
<th>Admin dapat menginputkan about us seperti foto kantin, deskripsi
kantin, foto pemilik, deskripsi pemilik, email, alamat dan kontak</th>
</tr>
<tr class="odd">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.5 Admin Input Galery {#admin-input-galery-1}

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Galery</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.5 Admin Input Galery</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan galery</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan galery ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan galery</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan dan mengupload galery</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat menginputkan galery seperti judul galeri, tanggal,
deskripsi dan gambar</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.6 Admin input Promo {#admin-input-promo-1}

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Promo</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.6 Admin Input Promo</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan promo</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan promo ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan about us</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, mengedit dan menghapus promo</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat menginputkan promo seperti judul, tanggal awal, tanggal
akhir, deskripsi, syarat ketentuan, dan gambar</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.7 Admin Input Kutipan {#admin-input-kutipan-1}

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Kutipan</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.7 Admin Input Kutipan</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan kutipan</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan kutipan ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan kutipan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, mengedit dan menghapus kutipan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="header">
<th>Post Condition</th>
<th>Admin dapat menginputkan kutipan seperti judul, isi kutipan dan
gambar</th>
</tr>
<tr class="odd">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.8 Admin Mengelola Pesan Saran {#admin-mengelola-pesan-saran-1}

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Admin Mengelola Pesan Saran</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.8 Admin Mengelola Pesan Saran</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat mengelola pesan saran pada website</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin melihat pesan saran</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan pesan saran</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menghapus dan membalas pesan saran dari
pengunjung</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat membalas dan menghapus pesan saran dari pengunjung</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.9 Pengunjung Mengunjungi Website {#pengunjung-mengunjungi-website-1}

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Pengunjung Mengunjungi Website</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.8 Pengunjung Mengunjungi Website</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Pengunjung dapat mengunjungi website dan melihat informasi yang ada
pada website Kantin Afwah yang telah disediakan</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Pengunjung Mengunjungi Website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan halaman halaman konten</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Pengunjung melihat informasi yang ada pada website dan juga dapat
memberikan pesan saran pada website yang tersedia</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Pengunjung mengunjungi website dan melihat informasi yang tersedia
pada website</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.3 Struktur Detail Kebutuhan Non - Fungsional {#struktur-detail-kebutuhan-non---fungsional}

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/erd.png){width="6.5in" height="2.125in"}

3.3.1 Logika Struktur Data

Struktur data logika pada sistem Kantin Afwah terdapat struktur Database
yang dijelaskan menggunakan ERD

**Tabel Users**

| **Data Item**     | **Tipe Data** | **Deskripsi**                                         |
|-------------------|---------------|-------------------------------------------------------|
| id                | bigint        | Auto increment dari id untuk admin                    |
| name              | varchar(255)  | Berisikan name dari admin untuk mengakses sistem      |
| email             | varchar(255)  | Berisikan email admin untuk mengakses sistem          |
| password          | varchar(255)  | Berisikan password admin untuk mengakses sistem       |
| email_verified_at | timestamp     | Berisikan email admin yang terverifikasi              |
| remember_konten   | varchar(255)  | Berisikan remerber token admin untuk mengakses sistem |
| created_at        | timestamp     | Berisikan kapan akun admin dibuat                     |
| updated_at        | timestamp     | Berisikan kapan akun admin diperbarui                 |

**Tabel About**

| **Data Item**     | **Tipe Data** | **Deskripsi**                                     |
|-------------------|---------------|---------------------------------------------------|
| id                | int           | Auto increment dari id untuk About                |
| email             | varchar(255)  | Berisi email dalam sistem Kantin Afwah            |
| alamat            | varchar(255)  | Berisi alamat dalam sistem Kantin Afwah           |
| kontak            | varchar(255)  | Berisi kontak dalam sistem Kantin Afwah           |
| gambar_kantin     | text          | Berisi gambar kantin dalam sistem Kantin Afwah    |
| deskripsi_kantin  | text          | Berisi deskripsi kantin dalam sistem Kantin Afwah |
| gambar_pemilik    | text          | Berisi gambar pemilik dalam sistem Kantin Afwah   |
| deskripsi_pemilik | text          | Berisi deskripsi pemilik dalam sistemKantin Afwah |

**Tabel Galery**

| **Data Item** | **Tipe Data** | **Deskripsi**                                |
|---------------|---------------|----------------------------------------------|
| id_galery     | int           | Auto increment dari id_galery                |
| judul_galery  | varchar(255)  | Berisi judul galery dalam sistemKantin Afwah |
| deskripsi     | varchar(255)  | Berisi deskripsi dalam sistem Kantin Afwah   |
| foto          | varchar(255)  | Berisi foto dalam sistem Kantin Afwah        |
| tanggal       | date          | Berisi tanggal dalam sistem Kantin Afwah     |

**Tabel Kutipan**

| **Data Item** | **Tipe Data** | **Deskripsi**                                |
|---------------|---------------|----------------------------------------------|
| id            | int           | Auto increment dari id untuk kutipan         |
| judul         | varchar(255)  | Berisi judul dalam sistem Kantin Afwah       |
| isi_kutipan   | varchar(255)  | Berisi isi kutipan dalam sistem Kantin Afwah |
| gambar        | text          | Berisi gambar dalam sistem Kantin Afwah      |

**Tabel Menu**

| **Data Item** | **Tipe Data** | **Deskripsi**                               |
|---------------|---------------|---------------------------------------------|
| id            | int           | Auto increment dari id untuk menu           |
| nama_menu     | varchar(255)  | Berisi nama menu dalam sistem Kantin Afwah  |
| dekripsi      | varchar(255)  | Berisi deskripsi dalam sistem Kantin Afwah  |
| harga         | int           | Berisi harga dalam sistem Kantin Afwah      |
| gambar        | text          | Berisi gambar dalam sistem Kantin Afwah     |
| jenis_menu    | varchar(255)  | Berisi jenis menu dalam sistem Kantin Afwah |

**Tabel Promo**

| **Data Item**        | **Tipe Data** | **Deskripsi**                                         |
|----------------------|---------------|-------------------------------------------------------|
| id_promo             | int           | Auto increment dari id_promo                          |
| judul                | varchar(255)  | Berisi judul dalam sistem Kantin Afwah                |
| deskripsi            | text          | Berisi deskripsi dalam sistem Kantin Afwah            |
| gambar               | varchar(255)  | Berisi gambar dalam sistem Kantin Afwah               |
| tanggal_awal_promo   | date          | Berisi tangga awal promo dalam sistem Kantin Afwah    |
| tanggal_akhir_promo  | date          | Berisi tanggal akhir promo dalam sistem Kantin Afwah  |
| syarat_dan_ketentuan | text          | Berisi syarat dan ketentuan dalam sistem Kantin Afwah |

**Tabel Sliders**

| **Data Item** | **Tipe Data** | **Deskripsi**                                  |
|---------------|---------------|------------------------------------------------|
| id            | bigint        | Auto increment dari id_promo                   |
| created_at    | timestamp     | Berisi kapan ditambahkan slidernya             |
| updated_at    | timestamp     | Berisi kapan sliderny diperbarui               |
| gambar_slider | varchar(255)  | Berisi gambar slider dalam sistem Kantin Afwah |

**Pembagian Tugas Laporan**

BAB 1 -\> Dimas

BAB 2 -\> Kibran

2.1 -\> Syafrisar

2.2 -\> Dimas

2.3 - 2.4 -\> Dimas

BAB 3

3.1 -\> Syafrisar

3.2 -\> Syafrisar

3.3 -\> Kibran

**Pembagian Kerja Projek**

Syafrisar :

> CRUD Menu
>
> CRUD About Us
>
> CRUD Kutipan
>
> Halaman About Us
>
> Halaman Menu

Dimas :

> CRUD galery
>
> CRUD Promosi
>
> Halaman Promosi
>
> Halaman Pesan Saran

Kibran :

> CRUD slider
>
> CRUD pesan saran
>
> Halaman home
>
> Halaman Galery
