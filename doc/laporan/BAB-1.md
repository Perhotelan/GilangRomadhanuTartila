**BAB I**

**PENDAHULUAN**

**1. 1. Latar Belakang**
<p align="justify">
Seiring dengan kemajuan dan perkembangan teknologi, kebutuhan manusia pada teknologi menjadi kebutuhan yang sangat bermanfaat[1]. Banyak teknologi – teknologi baru untuk dikembangkan sebagai sistem komputerisasi untuk mendukung sistem kerja pada perusahaan. Pemanfaatan teknologi hampir dibutuhkan dalam semua aspek baik di bidang ekonomi, pendidikan, kesehatan, sosial dan budaya.
</p>
<p align="justify">
Pada saat ini, teknologi juga dapat digunakan untuk memudahkan pelayanan di dalam sebuah hotel[2], misalnya teknologi yang dapat memudahkan para konsumen hotel dalam melakukan pemesanan kamar hotel.Saat ini banyak tempat – tempat wisata terutama di kota Bandung. Hal ini menyebabkan meningkatnya permintaan masyarakat terutama wisatawan untuk mencari tempat menginap atau hotel yang nyaman, sehingga para pemilik hotel memberikan pelayanan – pelayanan yang bagus dan menarik agar para wisatawan mau menginap.
</p>
<p align="justify">
Pada Proyek IT 1 telah dibangun sebuah aplikasi pelayanan perhotelan yang proses bisnisnya terdiri dari penambahan layanan yang dilakukan oleh tamu hotel yang telah _check-in_ dan diolah oleh aplikasi[10].
</p>
<p align="justify">
Penulis menyimpulkan dari proses bisnis Proyek IT 1 yang telah dipaparkan terdapat masalah, proses yang harus dilakukan terlebih dahulu sebelum melakukan penambahan layanan yaitu pemesanan kamar hotel secara online. Pemesanan kamar hotel yang terdapat pada Proyek IT 1 tidak ada sehingga perlu ditambahkan untuk mendukung proses pembayaran pemesanan kamar hotel. Proses pembayaran akan dilakukan dengan menggunakan via pembayaran online, sehingga memberikan kemudahan dalam memesan kamar hotel yang dilakukan tamu hotel. Kemudian informasi dari pemesanan kamar (harga kamar, fasilitas, lokasi) yang sudah dibayar melalui via online akan diinformasikan secara _up-to-date_ kepada tamu hotel.
</p>
<p align="justify">
Sehingga untuk mengatasi masalah dan solusi yang dipaparkan diatas maka perlu dilakukan pengembangan pada Proyek IT 1. Pengembangan yang dilakukan masih menitik beratkan dengan bahasa pemrograman Yii2 Framework yang bersifat web based, tetapi untuk implementasi penyimpanan datanya menggunakan database Oracle 11g dikarenakan DBMS pada sebelumnya yaitu MySql memiliki banyak kekurangan.
</p>
<p align="justify">
Dengan demikian penulis menyimpulkan untuk judul Proyek IT 2 adalah Pengembangan Aplikasi Perhotelan Berbasis Yii2 Framework Dengan Sub Modul Pemesanan Kamar Hotel.
</p>
**1. 2. Identifikasi Masalah**
<p align="justify">
Dari latar belakang di atas, masalah yang teridentifikasi antara lain :
</p>
<p align="justify">
1. Belum adanya pemesanan kamar hotel secara online.
</p>
<p align="justify">
2. Belum adanya transaksi pembayaran secara online.
</p>
<p align="justify">
3. Belum adanya informasi secara _up-to-date_ yang terdiri dari nama hotel, harga hotel, lokasi, fasilitas dan titik – titik terdekat objek wisata dengan lokasi hotel.
</p>
**1. 3 Tujuan**

Tujuan dalam pembuatan website ini adalah sebagai berikut:
<p align="justify">
1. Dibangun sebuah proses pemesanan kamar hotel secara online dengan menggunakan Yii2 Framework berbasis web based.
</p>
<p align="justify">
2. Dibangun sebuah proses transaksi pembayaran pada saat pemesanan online telah ditentukan dengan menggunakan Yii2 Framework berbasis web based.
</p>
<p align="justify">
3. Dibangun sebuah proses pencarian lokasi hotel dengan menggunakan teknologi Marker Cluster dan mencakup informasi dari hotel (nama hotel, harga hotel, fasilitas, lokasi dan titik – titik terdekat wisata dengan hotel.
</p>
**1. 4 Ruang Lingkup**

Dalam pembuatan website ini terdapat beberapa pembatasan yaitu:
<p align="justify">
1. Menyediakan informasi mengenai profil hotel, fasilitas hotel.
</p>
<p align="justify">
2. Menyediakan sistem pemesanan secara online.
</p>
<p align="justify">
3. Di dalam pembuatan aplikasi dibutuhkan software seperti: XAMPP, Sublime Text, Oracle, Yii2 Framework,dan Windows 10 Pro sebagai Sistem Operasi
</p>
**1. 5 Sistematika Penulisan**
<p align="justify">
Laporan ini secara keseluruhan terdiri dari lima bab, dimana secara garis besar masing – masing bab membahas hal – hal sebagai berikut:
</p>
<p align="justify">
Bab I. Pendahuluan, berisi tentang latar belakang, identifikasi masalah, tujuan, ruang lingkup, sistematika penulisan. Latar belakang berisi ulasan ringkas mengenai keadaan/kondisi yang ada dan kekurangan dari sistem yang diamati sehingga muncul topik yang diambil, Identifikasi masalah berisi berbagai masalah yang sudah dikenali dan akan diberikan solusinya melalui fungsi dari sistem/aplikasi/alat yang akan dibuat, Tujuan berisi tujuan untuk apa sistem/aplikasi/alat itu dibuat, Ruang lingkup berisi batasan – batasan proyek atau cakupan aplikasi yang akan dibangun, dan Sistematika penulisan menjelaskan isi yang ada di laporan proyek.
</p>
<p align="justify">
Bab II. Landasan Teori, berisi teori – teori mengenai perangkat lunak yang digunakan dalam pembuatan proyek, antara lain teori hotel, pelayanan, aplikasi, _website_, _Unified Modeling Language (UML)_, Kamus Data, Basis Data, PHP, HTML, Yii Framework, XAMPP, Sublime Text, Apache, dan Pengujian, Metode Penelitian, Jurnal Penelitian
</p>
<p align="justify">
Bab III. Analisis dan Perancangan, berisi mengenai analisis dan perancangan. Analisis terdiri dari analisis sistem yang sedang berjalan, analisis prosedur / Flow Map yang berjalan, analisis sistem yang akan dibangun, analisis kebutuhan aplikasi serta analisis kebutuhan perangkat lunak dan perangkat keras. Perancangan menggunakan _object oriented_ terdiri dari use case diagram, class diagram, interaction diagram, sequence diagram, callaboration diagram, actifity diagram, state chart diagram, component diagram, deployment diagram, objek diagram.
</p>
<p align="justify">
Bab IV. Implementasi dan Pengujian, yaitu membahas tentang implementasi sebuah aplikasi yang meliputi lingkungan aplikasi, tampilan antar muka, pengujian, dan petunjuk pemakaian
</p>
<p align="justify">
Bab V. Kesimpulan dan Saran, merupakan bagian akhir dari laporan yang berisi kesimpulan dan saran dari proyek yang telah dibuat sehingga dapat menjadi acuan dalam pengembangan proyek lebih lanjut.
</p>