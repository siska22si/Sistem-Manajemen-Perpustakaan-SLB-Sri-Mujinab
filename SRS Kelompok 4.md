<html>
<body>
<div align="center"><h1> Software Requirements Spesification</h1></div>

<p align="center">1 November 2023</b>
<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png" width="250" height="250"/ >
</p>

<p align="center"><b>Manajemen Perpustakaan SLB Sri Mujinab<br>
</b>
<p align="center">Kelompok 4 <br>
 Siska Limarga            (2257301127)<br>
 Afifah Aulia Amri    (2257301006)<br>
 Nisa Khotimah       (2257301106)<br><br><br>

<p align="center"><b>Program Studi Sistem Informasi</b><br>
<p align="center"><b>Jurusan Teknologi Informasi</b><br>
<p align="center"><b>Politeknik Caltex Riau</b>
<p align="center"><b>2018</b>
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
Sistem Manajemen Perpustakaan ini merupakan aplikasi yang kami bangun untuk mempermudah pustakawan, siswa dan tamu dalam melihat perkembangan data perpustakaan yaitu perkembangan judul buku, penerbit, tahun, jumlah buku, dan perkembangan kategori buku.
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
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari .dalam studi kasus Proyek II ini kami menganalisis kebutuhan suatu desa di daerah Indramayu tepatnya di desa Lohbener Kecamatan Lohbener .kasus yang kami peroleh pembuatan laporan kependudukan di desa Lohbener ini. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan pemerintah desa dengan menerapkan manajemen administrasi data kependudukan desa Lohbener. Sehingga memudahkan admin dalam menginputkan data-data kependudukan. Software yang kami buat ini berbasis website dimana website sebagai admin, sekdes dan kepala desa. Sistem yang kami buat di dalamnya terdapat angka kelahiran, angka kematian, pekerjaan, agama, laporan ( untuk admin/sekdes ), grafik dan laporan ( untuk kepala desa ). Berikut akan kami jelaskan  sistem software kami,  admin fungsi utama yaitu :
   - Input Judul 
   - Input ISBN
   - Input Penerbit
   - Input Tahun
   - Input Jumlah 
   - Input Kategori
   - Input Tanggal Pinjam
   - Input Tanggal Kembali
   
   Berikut ini fungsi user dalam bentuk grafik :
   - View Judul
   - View ISBN
   - View Penerbit
   - View Tahun
   - View Jumlah 
   - View Kategori
   - View Tanggal Pinjam
   - View Tanggal Kembali
2.1   Perspektif produk
----------
Manajemen Perpustakaan SLB Sri Mujinab adalah sebuah sistem Perpustakaan yang diaplikasikan pada website. Terdapat 1 jenis admin, yaitu Pustakawan. Pengelolaan data dikelola oleh Pustakawan ada website dan Siswa & Tamu dapat mencari buku pada website.

Pada sistem manajemen perpustakaan ini akan menampilkan buku yang sudah diinputkan oleh admin
**2.1.1 Antarmuka sistem**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/antarmuka%20sistem1.png)

Sistem Manajemen Perpustakaan SLB Sri Mujinab memiliki 2 user, yaitu Siswa atau Tamu dan Pustakawan. Pustakawan bertugas untuk mengelola data, agar bisa diakses oleh Siswa atau Tamu. Sedangkan, Siswa atau Tamu yang akan mengakses data di Sistem ini.
**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/86bc2686530b154be24145f1b34402e5fb12a11b/Img/1%20Home%20User.jpg) Pada halaman login admin diminta untuk mengisi username dan password.| ![enter image description here](https://github.com/siska22si/Sistem-Manajemen-Perpustakaan-SLB-Sri-Mujinab/blob/86bc2686530b154be24145f1b34402e5fb12a11b/Img/2%20Hasil%20Pencarian.jpg) Pada Dashboard admin terdapat panel-panel seperti penduduk, pendidikan, agama, pekerjaan, laporan dan ucapan selamat datang.|
| ![enter image description here]() Pada halaman dashboard ada navigation bar kependudukan yang berisi dropdown angka kelahiran dan angka kematian| ![enter image description here]() Pada Halaman agama dapat menginputkan data agama penduduk|
| ![enter image description here]() Pada Halaman pekerjaan dapat menginputkan data pekerjaan penduduk| ![enter image description here]() Pada Halaman warga dapat menginputkan data warga|
| ![enter image description here]() Pada Halaman pendidikan dapat menginputkan data pendidikan penduduk| ![enter image description here]() Pada Halaman kelahiran dapat menginputkan data kelahiran penduduk|
| ![enter image description here]() Pada Halaman kematian dapat menginputkan data kematian penduduk| ![enter image description here]() Pada Halaman grafik kelahiran dapat melihat data angka kelahiran|
| ![enter image description here]() Pada Halaman grafik kematian dapat melihat data angka kematian| ![enter image description here]() Pada Halaman laporan dapat melihat dan mendownload laporan penduduk|
 
**2.1.3 Antarmuka perangkat keras**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/antarmuka%20perangkat%20keras%202.png)

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
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Use%20Case1.png)
   
**2.2.1 Siswa & Tamu melihat status**

Use Case: Melihat Status

Diagram : 
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20login%20kepdes.png)

Deskripsi Singkat 
Siswa & Tamu  dapat melihat buku yang tersedia pada aplikasi perpustakaan SLB Sri Mujinab. Deskripsi Langkah-langkah

1. Siswa & Tamu mencari judul buku yang diinginkan
2. Sistem akan menampilkan hasil pencarian
3. Siswa & tamu menekan buku yang dicari dan akan muncul status buku yang diinginkan tersedia atau tidak

Xref: Bagian 3.2.1 Melihat status

**2.2.2 Siswa & Tamu mencari buku**

Use Case: Pencarian Buku

Diagram: 
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20kepdes%20generate%20laporan.png)

Deskripsi Singkat 
Siswa & Tamu dapat melakukan pencarian buku pada halaman aplikasi tanpa melakukan login. Deskripsi Langkah-langkah

1. Siswa & Tamu membuka halaman web
2. Siswa & Tamu mengklik tombol search
3. Siswa & Tamu Mengetikkan judul buku yang ingin dicari
4. Sistem menampilkan buku yang dicari oleh Siswa & Tamu

Xref: Bagian 3.2.2 Pencarian buku

**2.2.3 Pustakawan login**

Use Case: Pustakawan Login

Diagram :
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20login.png)

Deskripsi Singkat 
Pustakawan melakukan login dengan memasukkan username password. Deskripsi Langkah-langkah

1. Pustakawan melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Jika Username dan Password benar maka akan masuk ke sistem

Xref: Bagian 3.2.3, Pustakawan Login
      
**2.2.4 Pustakawan mengelola data buku**

Use Case: Mengelola data buku

Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20admin%20kelola%20data2.png)
      
Deskripsi Singkat 
Pustakawan melakukan pengelolaan data buku dengan menginputkan data tahun, data kategori, data nomor buku, data judul, dan data penerbit. Deskripsi Langkah-langkah

1. Pustakawan melakukan input data, tahun, kategori, nomor buku, judul, dan penerbit.
2. Pustakawan mengklik tombol simpan
3. Sistem menyimpan data buku

Xref: Bagian 3.2.4, Mengelola data buku

**2.2.5 Pustakawan mengelola data peminjaman buku**

Use Case: Mengelola data peminjaman buku

Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20lihat%20data%20kependudukan.png)

Deskripsi Singkat 
Mengelola data peminjaman buku dengan menginputkan data peminjaman buku dan sistem menyimpan data pada database. Deskripsi Langkah-langkah

1. Pustakawan melakukan input data buku pinjaman, tanggal peminjaman,nama peminjam, dan kelas peminjam
2. Pustakawan mengklik tombol simpan
3. Sistem menyimpan data peminjaman buku

Xref: Bagian 3.2.5, Mengelola data peminjaman buku
   
**2.2.6 Pustakawan mengelola data pengembalian buku**

Use Case: Mengelola data pengembalian buku

Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20admin%20generate%20laporan.png)

Deskripsi Singkat 
Pustakawan mengelola data pengembalian buku dengan melakukan input data tanggal pengembalian dan menyimpan pada database. Deskripsi Langkah-langkah

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
   | 2 | Perangkat Lunak dapat dipakai di semua platofrm  OS ( Admin, sekdes dan kepala desa ) 
 
2.4   Karakteristik pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10,11). 
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6   Asumsi-asumsi
----------
Maksimal penginputan id atau memasukkan kode pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan"Anda telah melebihi batas maksimum".

2.7   Kebutuhan Penyeimbang
----------
Tidak ada


BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Cara mengakses web ini yaitu dengan siswa & tamu  membuka website Perpustakaan SLB Sri Mujinab, kemudian dapat secara langsung mencari buku yang diinginkan, dan dapat melakukan peminjaman buku dan pengembalian buku kepada pustakawan, sedangkan pustakawan melakukan login terlebih dahulu dengan mencantumkan username dan password kemudian sistem mencocokkan username  dan password pustakawan. Setelah login berhasil pustakawan dapat mengelola data buku,data peminjaman buku, dan data pengembalian buku di website tersebut.      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1 Melihat status**

|  |  |
|--|--|
| Nama Fungsi | Melihat status |
| Xref | Bagian 2.2.1, Melihat Status |
| Trigger | Membuka website Manajemen Perpustakaan SLB Sri Mujinab |
| Precondition | Halaman detail buku |
| Basic Path | 1. Siswa & tamu mencari judul yang diinginkan <br> 2. Siswa & tamu menekan buku yang dipilih <br> 3. Sistem akan menampilkan detail buku beserta status ketersediaan buku |
| Alternative | Tidak ada |
| Post Condition | Siswa & Tamu dapat melihat status ketersediaan buku pada website Perpustakaan SLB Sri Mujinab |
| Exception Push | Tidak ada koneksi |
      
**3.2.2 Siswa & tamu mencari buku**

|  |  |
|--|--|
| Nama Fungsi | Pencarian buku |
| Xref | Bagian 2.2.2, Pencarian buku |
| Trigger | Membuka website Manajemen Perpustakaan SLB Sri Mujinab |
| Precondition | Halaman awal |
| Basic Path | 1. Mengisi judul yang ingin dicari di kolom pencarian <br> 2. Sistem akan menampilkan hasuk pencarian |
| Alternative | Tidak ada |
| Post Condition | Kepala desa melihat laporan kependudukan |
| Exception Push | Tidak ada judul yang terkait |
   
**3.2.3 Pustakwan login**

|  |  |
|--|--|
| Nama Fungsi | Pustakawan login |
| Xref | Bagian 2.2.3, Pustakawan login |
| Trigger | Membuka website Manajemen Perpustakaan SLB Sri Mujinab |
| Precondition | Halaman login pustakawan |
| Basic Path | 1. Admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin berhasil login dan mengakses website manajemen perpustakaan SLB Sri Mujinab |
| Exception Push | Username dan password salah |
   
**3.2.4 Pustakawan mmengelola data buku**

|  |  |
|--|--|
| Nama Fungsi | Mengelola data buku |
| Xref | Bagian 2.2.4, Mengelola data buku |
| Trigger | Membuka website Manajemen Perpustakaan SLB Sri Mujinab |
| Precondition | Halaman data buku |
| Basic Path | 1. Admin dapat menambah dan <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menyimpan data kependudukan <br> 4. Bila data sudah ada sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data kependudukan |
| Exception Push | Tidak ada koneksi |
   
**3.2.5 Admin melihat data kependudukan**

|  |  |
|--|--|
| Nama Fungsi | View data kependudukan |
| Xref | Bagian 2.2.5, View data kependudukan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman form input data |
| Basic Path | 1. Sistem akan menampilkan data kependudukan desa Lohbener. <br> 2. Admin melihat data dan dapat mengedit atau menghapusnya. <br> 3. Sistem menampilkan edit data kependudukan <br>4. Admin  mengedit data kependudukan yang baru atau yang sudah ada<br>5. Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan|
| Alternative | Tidak ada |
| Post Condition | Halaman data kependudukan |
| Exception Push | Tidak ada koneksi |
   
**3.2.6 Cetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.6, Cetak Laporan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | halaman utama admin |
| Basic Path | 1. Admin mengklik tombol laporan <br> 2. Sistem menampilkan laporan kependudukan <br> 3. Admin memilih combobox tersebut dan klik tombol lihat <br>4. Sistem akan menampilkan hasil laporan. <br>5. Admin mencetak laporan  |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.7  Admin mengelola user**

|  |  |
|--|--|
| Nama Fungsi | Mengelola user |
| Xref | Bagian 2.2.7, Mengelola user |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener | 
| Precondition | halaman utama admin |
| Basic Path | 1. Sistem menampilkan form.<br>2. Admin mengisi form user dengan jabatan, tanggal mulai, tanggal berakhir, dll kemudian klik tombol simpan.<br>3. Sistem akan menyimpan data user ke database.  |
| Post Condition | Halaman user |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/erd_proyek2.png)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| int | Nomer auto increment Id_user|
| Username | varchar | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |
| level | varchar | untuk membedakan level saat login antara admin dan user

**Tabel Warga**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| NIK | varchar | nomer kependudukan|
| Nama | varchar | nomer kependudukan|
| jns_kelamin | varchar | Identifikasi jenis kelamin|
| Tgl_lahir | date | tanggal lahir peserta |
| Agama | varchar | Identifikasi agama |

**Tabel Pegawai**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pegawai| int | Nomer auto increment Id_bioadmin|
| Id_user| int | untuk mengambil username dan password admin pada tabel user|
| nik| varchar | nik admin|
| jabatan | varchar | mendefinisikan level user |
| tgl_masuk | date | awal jabatan|
| tgl_keluar | date | akhir jabatan|

**Tabel Kelahiran**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kelahiran| int | Nomer auto increment Id_kelahiran|
| Id_warga| int | foreignt key tabel warga |
| tgl_lahir| date | tanggal lahir anak |
| jns_kelamin| varchar | jenis kelamin anak|
| ayah | varchar | nama ayah|
| ibu | varchar | nama ibu|
| tmp_lahir| varchar | tempat lahir anak |
| rt | int | nomor rt|
| rw | int | nomor rw|

**Tabel Kematian**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kematian| int | Nomer auto increment Id_kematian|
| Id_warga| int | foreignt key tabel warga |
| tmp_kematian| varchar | tempat lahir anak |
| tgl_kematian| date | tanggal lahir anak |
| rt | int | nomor rt|
| rw | int | nomor rw|

**Tabel Pekerjaan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pekerjaan| int | Nomer auto increment Id_pekerjaan|
| Id_warga| int | foreignt key tabel warga |
| pekerjaan| varchar | pekerjaan masyarakat  |
| tgl_input | date | tanggal input pekerjaan |

**Tabel Pendidikan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pendidikan| int | Nomer auto increment Id_pendidikan|
| Id_warga| int | foreignt key tabel warga |
| pendidikan| varchar | pendidikan masyarakat  |
| tgl_masuk | date | tanggal masuk pendidikan |

**Tabel ktp**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_ktp| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_ktp| varchar | Identifikasi memiliki atau belum memiliki ktp |
| masa_berlaku | date | tanggal berlaku ktp |

**Tabel kk**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kk| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| kepala_keluarga| varchar | nama kepala keluarga |
| no_kk | varchar | nomor kk |

**Tabel pindah**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pindah| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| tgl_pindah | date | tanggal akan pindah |
| ket | varchar | alamat pindah |

**Tabel datang**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_datang| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| tgl_datang | date | tanggal kedatangan |
| ket | varchar | alamat sebelum datang |

**Tabel pilih**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pilih| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_pilih | varchar | hak pilih |

**Tabel kawin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kawin| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_kawin | varchar | status warga |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| int | Nomer auto increment Id_laporan|
| Id_warga| int | foreignt key tabel warga |
| laporan | varchar | berisi laporan kependudukan |

**Tabel Agama**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_agama| int | Nomer auto increment Id_laporan|
| Id_warga| int | foreignt key tabel warga |
| agama| varchar | berisi agama penduduk |
