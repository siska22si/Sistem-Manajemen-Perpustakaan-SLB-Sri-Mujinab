<html>
<body>

<p align="center">
<img src="https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/c8d3b3bf3ceef6afc20160a84ac68ccfda32fe5a/Img/Cover.jpg"/ >
</p>

</body>
</html>
 

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Specification (SRS) ini  merupakan sebuah  dokumen spesifikasi perangkat lunak yang berguna untuk membangun “Sistem Manajemen Perpustakaan SLB Sri Mujinab”. Dokumen ini berguna untuk memudahkan serta dapat mengelola semua aspek perpustakaan dengan efisien dan efektif. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak “Sistem Manajemen Perpustakaan SLB Sri Mujinab”. 

1.2   Lingkup
----------
Sistem Manajemen Perpustakaan ini merupakan aplikasi yang kami bangun untuk mempermudah admin, siswa dan tamu dalam melihat perkembangan data perpustakaan yaitu perkembangan judul buku, penerbit, tahun, jumlah buku, dan perkembangan kategori buku.

1.3    Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses aplikasi |
| Software Requirement Specification | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| Use Case | situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4   Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
- https://opac.lib.pcr.ac.id/

1.5   Overview
----------

Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada aplikasi ini. Menjelaskan bagaimana gambaran umum dari aplikasi, sistem interface aplikasi dan bagaimana alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari-hari. Dalam studi kasus proyek ini kami menganalisis suatu kebutuhan SLB di Pekanbaru tepatnya di Jl. Dr. Sutomo, Kecamatan Sail. Kasus yang kami peroleh adalah Pembuatan Sistem Manajemen Perpustakaan SLB Sri Mujinab. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan SLB dengan menerapkan manajemen perpustakaan SLB Sri Mujinab. Sehingga memudahkan admin dalam mengelola data buku. Software yang kami buat ini berbasis website dimana website sebagai admin, siswa atau tamu. Sistem yang kami buat di dalamnya terdapat:

2.1   Perspektif produk
----------
Manajemen Perpustakaan SLB Sri Mujinab adalah sebuah sistem Perpustakaan yang diaplikasikan pada website. Terdapat 1 jenis admin, yaitu admin. Pengelolaan data dikelola oleh admin ada website dan Siswa & Tamu dapat mencari buku pada website.

Pada sistem manajemen perpustakaan ini akan menampilkan buku yang sudah diinputkan oleh admin

**2.1.1 Antarmuka sistem**

![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/463ec166f8895e6fcabb885ad35a3657785e2488/Img/Sistem%20Manajemen%20Perpustakaan.png)

Sistem Manajemen Perpustakaan SLB Sri Mujinab memiliki 2 user, yaitu Siswa atau Tamu dan admin. admin bertugas untuk mengelola data, agar bisa diakses oleh Siswa atau Tamu. Sedangkan, Siswa atau Tamu yang akan mengakses data di Sistem ini.

**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here]() Pada halaman ini menampilkan Rekomendasi buku dan Buku popular, kemudian juga terdapat tempat pencarian buku| ![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/86bc2686530b154be24145f1b34402e5fb12a11b/Img/2%20Hasil%20Pencarian.jpg) Pada halaman ini adalah hasil pencarian jika anda melakukan pencarian buku.|
| ![enter image description here]() Halaman ini menampilkan detail dari buku yang anda pilih.| ![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/703e15dbd463b5369e735c107cfd05c9513f343e/Img/4%20Login%20admin.jpg) Halaman ini meminta admin untuk memasukkan username dan passwordnya untuk masuk ke halaman utama admin.|
| ![enter image description here]() Pada halaman utama admin, terdapat Total Buku, Telah Dipinjam, Sedang Dipinjam, dan Tersedia.| ![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/703e15dbd463b5369e735c107cfd05c9513f343e/Img/6%20Data%20Buku.jpg) Pada Halaman Total buku, terdapat seluruh judul buku beserta detailnya.|
| ![enter image description here]() Pada halaman ini, admin dapat memodifikasi detail buku yang ingin diubah.| ![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/703e15dbd463b5369e735c107cfd05c9513f343e/Img/8%20Tambah%20Buku.jpg) Pada halaman ini, admin dapat menambahkan judul buku.|
| ![enter image description here]() Pada halaman ini, menampilkan seluruh siswa yang sedang meminjam buku.| ![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/703e15dbd463b5369e735c107cfd05c9513f343e/Img/10%20Detail%20Data%20Peminjaman.jpg) Pada halaman ini, admin dapat memodifikasi dan juga mengubah status peminjaman buku.|
| ![enter image description here]() Pada halaman ini, Terdapat daftar buku yang dipinjam dan tempat mendaftarkan siswa yang ingin meminjam buku.| ![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/703e15dbd463b5369e735c107cfd05c9513f343e/Img/12%20Pinjam%20Buku.jpg) Pada halaman ini, admin memasukkan data peminjam.|
| ![enter image description here]() Halaman ini menampilkan riwayat peminjaman buku.|
 
**2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/5bb4ecc6232f08978c0335aae76b28f370b12bed/Img/interface%20hardware.drawio.png)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Manajemen Perpustakaan SLB Sri Mujinab antara lain :
1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka perangkat lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Manajemen Administrasi Data Kependudukan Desa Lohbener antara lain :
1. Kabel Lan UTP RJ45
2. Modem
3. wifi

**2.1.6 Batasan memori**

Tidak ada

**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses aplikasi |
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |

**2.1.8 Kebutuhan adaptasi**

Tidak ada
   
2.2 Spesifikasi Kebutuhan fungsional
----------
![](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/6fbe8cf2d3a2dcfef30faae1345b9b60e3cde405/Img/UseCaseDiagram1.png)
   
**2.2.1 Siswa & Tamu melihat status**

Use Case: Melihat Status

Diagram : 
![](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/62bad9503c2595589a11082f98dc311c96d3ac09/Img/MelihatStatus.png)

Deskripsi Singkat

Siswa & Tamu  dapat melihat buku yang tersedia pada aplikasi perpustakaan SLB Sri Mujinab. Deskripsi Langkah-langkah

1. Siswa & Tamu mencari judul buku yang diinginkan
2. Sistem akan menampilkan hasil pencarian
3. Siswa & tamu menekan buku yang dicari dan akan muncul status buku yang diinginkan tersedia atau tidak

Xref: Bagian 3.2.1 Melihat status

**2.2.2 Siswa & Tamu mencari buku**

Use Case: Pencarian Buku

Diagram: 
![](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/62bad9503c2595589a11082f98dc311c96d3ac09/Img/MencariBuku.png)

Deskripsi Singkat

Siswa & Tamu dapat melakukan pencarian buku pada halaman aplikasi tanpa melakukan login. Deskripsi Langkah-langkah

1. Siswa & Tamu membuka halaman web
2. Siswa & Tamu mengklik tombol search
3. Siswa & Tamu Mengetikkan judul buku yang ingin dicari
4. Sistem menampilkan buku yang dicari oleh Siswa & Tamu

Xref: Bagian 3.2.2 Pencarian buku

**2.2.3 admin login**

Use Case: admin Login

Diagram :
![](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/235f7a8395d6ed741a09df19da5a579c51f2d06e/Img/Login.png)

Deskripsi Singkat

admin melakukan login dengan memasukkan username password. Deskripsi Langkah-langkah

1. admin melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Jika Username dan Password benar maka akan masuk ke sistem

Xref: Bagian 3.2.3, admin Login
      
**2.2.4 admin mengelola data buku**

Use Case: Mengelola data buku

Diagram:
![](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/62bad9503c2595589a11082f98dc311c96d3ac09/Img/Mengelola%20Data%20Buku.png)
      
Deskripsi Singkat

admin melakukan pengelolaan data buku dengan menginputkan data tahun, data kategori, data nomor buku, data judul, dan data penerbit. Deskripsi Langkah-langkah

1. admin melakukan input data, tahun, kategori, nomor buku, judul, dan penerbit.
2. admin mengklik tombol simpan
3. Sistem menyimpan data buku

Xref: Bagian 3.2.4, Mengelola data buku

**2.2.5 admin mengelola data peminjaman buku**

Use Case: Mengelola data peminjaman buku

Diagram:
![](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/62bad9503c2595589a11082f98dc311c96d3ac09/Img/Mengelola%20data%20peminjaman%20buku.png)

Deskripsi Singkat

Mengelola data peminjaman buku dengan menginputkan data peminjaman buku dan sistem menyimpan data pada database. Deskripsi Langkah-langkah

1. admin melakukan input data buku pinjaman, tanggal peminjaman,nama peminjam, dan kelas peminjam
2. admin mengklik tombol simpan
3. Sistem menyimpan data peminjaman buku

Xref: Bagian 3.2.5, Mengelola data peminjaman buku
   
**2.2.6 admin mengelola data pengembalian buku**

Use Case: Mengelola data pengembalian buku

Diagram:
![](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/62bad9503c2595589a11082f98dc311c96d3ac09/Img/Mengelola%20Data%20Pengembalian%20Buku.png)

Deskripsi Singkat

admin mengelola data pengembalian buku dengan melakukan input data tanggal pengembalian dan menyimpan pada database. Deskripsi Langkah-langkah

1. Admin akan mencari data peminjaman buku yang ingin dikembalikan
2. Admin akan menekan detail peminjaman
3. Admin akan menekan button “selesai”
4. Sistem akan memindahkan ke bagian history (Sudah Dipinjam) dan auto fill tanggal

Xref: Bagian 3.2.6, Mengelola data pengembalian buku

2.3   Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platform OS (admin, siswa dan tamu) |
 
2.4   Karakteristik pengguna
----------
Karakteristik pengguna dari perangkat lunak dari perangkat ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7, 8, 10, 11)
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan

2.6   Asumsi-asumsi
----------
Maksimal penginputan id atau memasukkan kode pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan “Anda telah melebihi batas maksimum”.

2.7   Kebutuhan Penyeimbang
----------
Tidak ada


BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Cara mengakses web ini yaitu dengan siswa & tamu  membuka website Perpustakaan SLB Sri Mujinab, kemudian dapat secara langsung mencari buku yang diinginkan, dan dapat melakukan peminjaman buku dan pengembalian buku kepada admin, sedangkan admin melakukan login terlebih dahulu dengan mencantumkan username dan password kemudian sistem mencocokkan username  dan password admin. Setelah login berhasil admin dapat mengelola data buku,data peminjaman buku, dan data pengembalian buku di website tersebut.
    
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1 Siswa & Tamu melihat status**

|  |  |
|--|--|
| Nama Fungsi | Melihat status |
| Xref | Halaman detail buku |
| Trigger | Membuka halaman web Perpustakaan Sri Mujinab |
| Precondition | Halaman data buku |
| Basic Path | 1.Siswa & tamu mengklik tombol search <br> 2. Siswa & Tamu mengetikkan judul buku yang ingin dibaca atau dipinjam <br> 3.Sistem menampilkan buku yang dicari dan status buku yang tersedia |
| Alternative | Tidak ada |
| Post Condition | Siswa & Tamu dapat melihat status buku pada web Perpustakaan SLB Sri Mujinab |
| Exception Push | Tidak ada koneksi |
      
**3.2.2 Siswa & tamu mencari buku**

|  |  |
|--|--|
| Nama Fungsi | Pencarian buku |
| Xref | Bagian 2.2.2, Pencarian buku |
| Trigger | Membuka halaman web Perpustakaan Sri Mujinab |
| Precondition | Halaman pencarian buku |
| Basic Path | 1. Siswa & Tamu mengklik tombol search <br> 2. Sistem menampilkan papan ketik <br>3. Siswa & Tamu mengetikkan buku yang diinginkan <br> 4.Sistem menampilkan buku yang diketikkan |
| Alternative | Mencari judul buku lain |
| Post Condition | Siswa & Tamu menemukan buku yang diinginkan pada aplikasi Perpustakaan SLB Sri Mujinab |
| Exception Push | Salah mengetikkan judul buku |
   
**3.2.3 admin melakukan login**

|  |  |
|--|--|
| Nama Fungsi | admin login |
| Xref | Bagian 2.2.3, admin login |
| Trigger | Membuka halaman web Perpustakaan Sri Mujinab |
| Precondition | Halaman login admin |
| Basic Path | 1.admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. sistem akan mengarahkan halaman beranda peradmin |
| Alternative | Tidak ada |
| Post Condition | admin dapat login dan dapat mengelola Aplikasi SLB Sri Mujinab |
| Exception Push | Username dan password salah |
   
**3.2.4 admin mmengelola data buku**

|  |  |
|--|--|
| Nama Fungsi | Mengelola data buku |
| Xref | Bagian 2.2.4, Mengelola data buku |
| Trigger | Membuka website Manajemen Perpustakaan SLB Sri Mujinab |
| Precondition | Halaman data buku |
| Basic Path | - Tambah buku: <br> 1. admin membuka halaman data buku <br> 2. admin menekan ikon tambah <br> 3.Sistem akan menampilkan form penambahan <br> 4.admin mengisi form dan menekan button “simpan” untuk menyimpan <br> <br> - Hapus Buku: <br> 1. admin membuka halaman data buku <br> 2. admin memilih buku yang ingin dihapus dan menekan ikon detail <br> 3. Sistem akan memunculkan detail buku <br> 4.admin menekan tombol “hapus” <br><br> - Edit Buku: <br> 1. admin membuka halaman data buku <br> 2. admin memilih buku yang ingin diedit dan menekan ikon detail <br> 3. admin dapat mengedit data buku <br> 4. admin menekan button “simpan: untuk menyimpan|
| Alternative | Tidak ada |
| Post Condition | Halaman data buku |
| Exception Push | Tidak ada koneksi |
   
**3.2.5 admin mengelola data peminjaman buku**

|  |  |
|--|--|
| Nama Fungsi | Mengelola data peminjaman buku |
| Xref | Bagian 2.2.5, Mengelola data peminjaman buku |
| Trigger | Membuka website Manajemen Perpustakaan SLB Sri Mujinab |
| Precondition | Halaman peminjaman buku |
| Basic Path | 1. admin menekan menu “peminjaman buku” <br> 2. Sistem akan menampilkan data buku yang sedang dipinjam <br> 3. admin menekan ikon tambah <br> 4. admin melakukan input data buku pinjaman, tanggal peminjaman,nama peminjam, dan jumlah buku yang dipinjam <br> 5. admin menekan button “simpan” untuk menyimpan <br> 6. Sistem menyimpan data peminjaman buku|
| Alternative | Tidak ada |
| Post Condition | Halaman data peminjaman buku |
| Exception Push | Tidak ada koneksi |
   
**3.2.6 Admin mengelola data Rak buku**

|  |  |
|--|--|
| Nama Fungsi | Mengelola data Rak buku |
| Xref | Bagian 2.2.6, Mengelola data Rak buku |
| Trigger | Membuka website Manajemen Perpustakaan SLB Sri Mujinab |
| Precondition | Halaman Peminjaman buku |
| Basic Path | 1. Admin menekan menu “Rak buku” <br> 2.  Sistem akan menampilkan data ke rak buku <br> 3.  Admin mencari judul buku yang dicari <br> 4. Admin menekan ikon “detail’ <br> 5. Sistem akan menampilkan detail rak buku <br> 6. Admin menekan button “selesai” |
| Alternative | Tidak ada |
| Post Condition | Halaman data Rak buku |
| Exception Push | Tidak ada koneksi |

3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/64c123cd274ac48a9f8764a0ec8d49194feba9a4/Img/FRAMEWORK-Page-2.drawio%20(3).png)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id | int | Nomor auto increment id_admin|
| Username | varchar | berisikan username untuk akses admin |
| Password | varchar | berisikan password untuk akses admin |

**Tabel Buku**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_buku | int | Nomor auto increment id_buku|
| judul | varchar | Judul buku|
| ISBN | int | Nomor ISBN buku|
| penerbit | varchar | Penerbit buku |
| Kategori | varchar | Kategori buku |
| jumlah | int | Jumlah buku |
| tahun | int | Tahun terbit buku |
| status | varchar | Status ketersediaan buku |
| sampul | varchar | Sampul buku |

**Tabel Peminjaman**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_pinjam | int | Nomor auto increment id_pinjam|
| id_buku | int | Untuk mengambil data buku dari tabel buku|
| nama_peminjam | varchar | Nama peminjam buku|
| tanggal_pinjam | date | Tanggal buku dipinjam |
| tanggal_kembali | date | Tanggal buku dikembalikan |

**Tabel Rak**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_kembali | int | Nomor auto increment id_pengembalian |
| id_pinjam | int | Untuk mengambil data peminjaman dari tabel peminjaman |
| tanggal_pengembalian | date | Tanggal buku dikembalikan |

**Tabel Kategori**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_kategori | int | Nomor auto increment id_kategori |
| nama_kategori | varchar | Nama Kategori Buku |

**Pembagian Jobdesc**
----------

BAB 1 Pendahuluan <br>
1.1 Tujuan : Nisa Khotimah <br>
1.2 Lingkup : Nisa Khotimah <br>
1.3 Akronim, singkatan, definisi : Nisa Khotimah <br>
1.4 Referensi : Nisa Khotimah <br>
1.5 Overview : Nisa Khotimah <br>
BAB 2 Gambaran Umum <br>
2.1 Perspektif Produk : Nisa Khotimah <br>
2.1.1 Antarmuka Sistem : Siska Limarga <br>
2.1.2 Antarmuka pengguna : M. Defri Lubis <br>
2.1.3 Antarmuka perangkat keras : Siska Limarga <br>
2.1.4 Antarmuka perangkat lunak : Siska Limarga <br>
2.1.5 Antarmuka Komunikasi : Siska Limarga <br>
2.1.6 Batasan memori : Siska Limarga <br>
2.1.7 Operasi-operas : Siska Limarga <br>
2.1.8 Kebutuhan adaptasi : Siska Limarga <br>
2.2 Spesifikasi Kebutuhan fungsional : Siska Limarga <br>
2.2.1 Siswa & tamu melihat status : Afifah Aulia Amri <br>
2.2.2 Siswa & Tamu mencari buku : Afifah Aulia Amri <br>
2.2.3 admin login : Afifah Aulia Amri <br>
2.2.4 admin mengelola data buku : Afifah Aulia Amri <br>
2.2.5 admin mengelola data peminjaman buku : Afifah Aulia Amri <br>
2.2.6 admin mengelola data rak buku : Nisa Khotimah <br>
2.3 Spesifikasi Kebutuhan non-fungsional : Siska Limarga <br>
2.4 Karakteristik pengguna : Siska Limarga <br>
2.5 Batasan-batasan : Siska Limarga <br>
2.6 Asumsi-asumsi : Siska Limarga <br>
2.7 Kebutuhan Penyeimbang : Siska Limarga <br>
BAB III Requirement specification <br>
3.1 Persyaratan Antarmuka Eksternal : Afifah Aulia Amri <br>
3.2 Functional Requirement : Afifah Aulia Amri <br>
3.3 Struktur Detail Kebutuhan Non-Fungsional : Siska Limarga <br>
FIGMA : M. Defri Lubis <br>
