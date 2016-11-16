

**BAB I**

**PENDAHULUAN**

1.
  1. 1 **Latar Belakang Masalah**

Politeknik Pos Indonesia adalah sebuah kampusyang mempunyai 9 prodi salah satu di antaranya yaitu D4 Teknik Informatika. DIV Teknik Informatika Politeknik Pos Indonesia adalah sebuah program studi yang bergerak dalam IT yang di dalamnya terdapat 3 kelas untuk tingkat I, 4 kelas untuk tingkat II, 4 kelas untuk tingkat III dan 2 kelas untuk tingkat IV yang sedang menjalankan Internship (praktek kerja di perusahaan). Total mahasiswa DIV Teknik Informatika Politeknik Pos Indonesia yang aktif mengikuti perkuliahan di kampus kecuali mahasiswa tingkat IV mencapai kurang lebih 350 mahasiswa.

Dari jumlah mahasiswa DIV Teknik Informatika Politeknik Pos Indonesia tersebut dalam kegiatan absensi perkuliahan masih memanfaatkan kertas dan pena sebagai sarana absensi. Kertas absensi diestafetkan dari mahasiswa yang satu ke mahasiswa yang lainnya tanpa terjamin absensi yang diisikan sesuai dengan kenyataan atau ada yang memanipulasi absensi tersebut.

Dalam kegiatan absensi mahasiswa tentu harus diadakannya pengawasan yang ketat baik itu dari pihak kampus seperti dosen, prodi atau dari luar kampus seperti orang tua mahasiswa itu sendiri.  Sehingga ketiga pihak tersebut bisa mengontrol anak didiknya dalam kehadiran perkuliahan, sehingga jika mahasiswa banyak yang tidak hadir tanpa adanya keterangan, sakit atau ijin mereka semua bisa tahu bahkan bisa mengetahui anak didiknya jika mendapatkan SP (Surat Peringatan) 1, SP 2, SP 3 atau DO (_drop out)_.

Data absensi ini menjadi perhatian serius mengingat kehadiran mahasiswa menjadi salah satu tolak ukur aktivitas mahasiswa dalam proses perkuliahan. Kesulitan yang sering ditemui adalah pada saat akan melakukan rekapitulasi data. Berkas/dokumen absensi harus dikumpulkan kemudian dikalkulasi. Hal ini sangat merepotkan mengingat banyaknya mahasiswa yang terdistribusi dalam setiap kelas.

Berdasarkan data dan fakta yang diuraikan di atas, maka diperlukan suatu sistem yang dapat memberikan solusi pada permasalahan tersebut yaitu dengan membangun suatu aplikasi yaitu &quot;Sistem Pengelolaan Data dan Monitoring Absensi pada Program Studi DIV Teknik Informatika Politeknik Pos Indonesia  Menggunakan Framework Code Igniter&quot;.

1.
  1. 2 **Identifikasi Masalah**

Berdasarkan latar belakang di atas maka permasalahan yang di hadapi pada kegiatan absensi mahasiswa program studi DIV Teknik Informatika Politeknik Pos Indonesia diantaranya yaitu kegiatan absensi mahasiswa masih manual dengan diestafetkannya kertas absensi sehingga kurang terjaminnya keaslian data. Selain itu, informasi tentang kehadiran mahasiswa selama perkuliahan tidak sampai kepada orang tua sehingga orang tua tidak tahu apakah anaknya masuk kuliah atau tidak. Disamping itu pengelolaan data absensi masih merasa kesulitan dalam perekapitulasian data absensi.

1.
  1. 3 **Tujuan**

Tujuan yang ingin dicapai pada pembuatan aplikasi ini adalah untuk mengelola data absensi mahasiswa secara terkomputerisasi yang diinputkan langsung oleh dosen ke dalam sistem sehingga terjamin keaslian datanya. Selain itu informasi kehadiran perkuliahan mahasiswa bersifat terbuka untuk orang tua, prodi, dosen yang mempunyai hak untuk itu.

1.
  1. 4 **Ruang Lingkup**

Adapun batasan masalah yang menjadi ruang lingkup pada pembuatan sistem ini antara lain :

1. Aplikasi ini berbasis _website_ menggunakan _framework codeigniter_ pada _backend_ (halaman admin) maupun _frontend_ (halaman user).
2. Untuk menjembatani antara _backend_ dan _frontend_, sistem ini menggunakan _web service_ dan dilengkapi keamanan berupa _login_ untuk admin, dosen, prodi, orangtua/mahasiswa.
3. Aplikasi ini hanya memuat absensi untuk mahasiswa DIV Teknik Informatika, tidak untuk pegawai Politeknik Pos Indonesia.
4. Untuk pengelolaan data absensi pada halaman admin terdapat data master yang meliputi data mahasiswa, data mata kuliah, data dosen, data kelas serta proses untuk melakukan absensi. Untuk user, prodi dan orang tua/mahasiswa, mereka hanya bisa melihat absensi.
5. Aplikasi ini digunakan oleh 4 macam _user_. Pertama yaitu admin yang mengelola sistem  dan yang kedua yaitu dosen, lalu yang ketiga yaitu prodi dan yang terakhir yaitu orangtua/mahasiswa.
6. Database yang digunakan adalah _Mysql_.
7. Untuk memonitoring absensi, orang tua bisa mengeceknya pada website yang telah disediakan dengan memasukan NPM dan password anaknya.

**1.5 Sistematika Penulisan**

Gambaran secara garis besar mengenai hal-hal yang akan dibahas dalam laporan Proyek I ini terdiri dari 5 bab, yaitu sebagai berikut:

Bab 1 Pendahuluan, pada bab ini pembahasannya meliputi latar belakang masalah yang membahas objek yang diteliti; proses apa saja yang ada didalamnya; masalah yang ada di objek; akibat dan solusi yang ditimbulkan masalah, identifikasi masalah yang membahas masalah apa saja yang ada, tujuan merupakan jawaban dari identifikasi masalah, ruang lingkup merupakan batasan masalah yang akan dibahas, dan sistematika penulisan merupakan struktur penulisan pada laporan.

Bab 2 Landasan Teori, pada bab ini pembahasannya meliputi konsep pendukung penjelasan mengenai sistem informasi penjualan mobil yang akan dibuat dan isi dari sistem informasi tersebut.

Bab 3 Analisis dan Perancangan, pada bab ini pembahasannya meliputi struktur menu yang membahas tentang penjelasan dari setiap menu dan sub menu sistem informasi ini. Gambar suatu rancangan menjelaskan proses sistem informasi manajemen data ini dari awal sampai akhir. Serta perangkat pendukung dalam pembuatan sistem informasi ini. Dalam analisis menggunakan Flow Map untuk penjelasan, sedangkan dalam perancangan menggunakan UML (_Unified Modeling Language_) untuk penjelasan perancangan sistem informasi ini.

Bab 4 Implementasi dan Pengujian, pada bab ini meliputi tampilan-tampilan interface pada sistem informasi yang dibuat mulai dari awal sampai akhir. Serta penjelasan mengenai isi dari sistem informasi ini.

Bab 5 Kesimpulan dan Saran, pada bab ini berisikan kesimpulan dari rancangan yang dibuat serta saran pengembangan selanjutnya berdasarkan kesimpulan yang belum dicapai.

