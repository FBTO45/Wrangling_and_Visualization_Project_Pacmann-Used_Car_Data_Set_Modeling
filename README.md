--------

# <center><summary><strong>Hi there :wave: , I'm Goo!</strong></summary>

--------

# <center>**Analisis Pasar Mobil Bekas di Ebay Kleinanzeigen: Tren, Preferensi Pengguna, dan Peluang Bisnis**

## A. Latar Belakang
  <p>Dengan kemajuan teknologi dan penetrasi internet yang semakin luas, platform online jual-beli semakin populer sebagai cara yang efisien untuk membeli dan menjual barang bekas atau layanan. Ebay Kleinanzeigen merupakan platform online yang populer untuk jual-beli barang bekas dan layanan di Jerman. Platform ini digunakan oleh pengguna untuk menawarkan berbagai kategori produk, seperti kendaraan, perumahan, barang elektronik, dan lainnya.</p>
  <p>Platform Ebay Kleinanzeigen menyediakan beragam data yang dapat digunakan untuk analisis, termasuk informasi tentang produk yang dijual (deskripsi, kategori, harga), informasi geografis (lokasi penjual/pembeli), serta data temporal (tanggal posting, durasi penjualan).</p>
  <p>Dari latar belakang diatas, analisis data yang akan dilakukan adalah mengambil data dari penjualan iklan mobil bekas di platform Ebay Kleinanzsigen.</p>


## B. Objective
  1. Meneliti variasi nama mobil yang tersedia dalam data untuk mengidentifikasi model mobil yang paling sering ditawarkan dan memahami preferensi pengguna dalam pemilihan nama mobil.
  2. Mengidentifikasi distribusi penjual (seller) untuk mengetahui apakah ada penjual dominan atau apakah penjualan lebih tersebar merata di antara berbagai penjual.
  3. Memeriksa distribusi harga (price) mobil yang ditawarkan untuk menentukan kisaran harga yang umum dan memahami distribusi harga di pasar mobil bekas.


## C. Goals/Tujuan
  1. Mengidentifikasi preferensi pengguna dalam hal nama mobil, tipe kendaraan, jenis transmisi, kekuatan mobil, dan fitur lainnya berdasarkan data abtest, untuk menyediakan wawasan yang berharga kepada penjual dan pembeli dalam membuat keputusan.
  2. Menentukan kisaran harga yang umum dari mobil yang ditawarkan, serta memahami apakah ada faktor-faktor tertentu yang mempengaruhi penentuan harga, seperti tahun registrasi, kekuatan mobil, atau jenis transmisi.
  3. Menemukan peluang bisnis potensial bagi penjual atau dealer mobil untuk menyesuaikan penawaran mereka dengan preferensi pasar yang ditemukan dalam analisis, serta mengidentifikasi segmen pasar yang mungkin belum dieksplorasi sepenuhnya.
  4. meningkatkan layanan iklan dan kepuasan pengguna dalam jual beli kendaraan mobil di platform e-Bay.


## D. Dataset
* <p>Dataset yang akan digunakan diambil dari website Data World. Berikut link dataset yang digunakan https://data.world/data-society/used-cars-data</p>
#### Deskripsi Dataset
  * `dateCrawled` ----> saat iklan ini pertama kali diunggah, semua nilai bidang diambil dari tanggal ini
  * `name` ----> nama mobil
  * `seller` ----> penjual
  * `offerType` ----> tipe penawaran
  * `price` ----> harga
  * `abtest` ----> untuk membandingkan dua versi dari fitur atau spesifikasi yang berbeda untuk melihat mana yang lebih efektif atau diminati oleh konsumen.
  * `vehicleType` ----> tipe kendaraan
  * `yearOfRegistration` ----> pada tahun berapa mobil pertama kali didaftarkan
  * `gearbox` ----> jenis transmisi mobil
  * `powerPS` ----> kekuatan mobil di PS (Horse Power)
  * `model` ----> model kendaraan
  * `kilometer` ----> berapa kilometer yang telah ditempuh oleh mobil
  * `monthOfRegistration` ----> pada bulan berapa mobil pertama kali didaftarkan
  * `fuelType` ----> jenis bahan bakar yang digunakan
  * `brand` ----> merek kendaraan
  * `notRepairedDamage` ----> jika mobil mengalami kerusakan yang belum diperbaiki
  * `dateCreated` ----> tanggal pembuatan iklan di ebay
  * `nrOfPictures` ----> jumlah gambar dalam iklan
  * `postalCode` ----> kode pos
  * `lastSeen` ----> kapan crawler melihat iklan ini terakhir kali online

## E. Dashboard Visualisasi

<center> **Visualisasi yang dibuat menggunakan Tableau** </center>
  
<p align='center'>
<a href="https://public.tableau.com/views/visualisationproject_17119371757720/DashboardAnalisisIklanPenjualanMobilBekas?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link">
    <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white"/>
</a>&nbsp;&nbsp;
</p>

## F. Analisis
* Analisis 1
  trend tahun registrasi pada jenis kendaraan
  grafik garis menunjukkan seberapa banyak jenis kendaraan yang dijual dan diiklankan berdasarkan tahun registrasi. Kendaran yang memiliki tahun registrasi dari tahun 1910-1995 hanya memiliki sedikit saja dari jumlah jenis kendaraan yang dijual.
  Jenis kendaraan yang tahun registrasinya pada tahun 2000, tercatat ada 6.760 jenis kendaraan yang dijual secara online di platfrom e-Bay.
  Lalu jenis kendaraan yang tahun registrasinya dari tahun 2001-2005 tercatat mengalami penurunan jumlah jenis kendaraan, dan mengalami kenaikan jumlah jenis kendaraan yang tahun registrasinya tahun 2016 sebesar 1293 kendaraan.


* Analisis 2
  Total Ketersediaan jenis kendaraan
  Dari visualisasi tersebut tercatat bahwa total ketersediaan jenis kendaaraan terbanyak dimiliki oleh jenis kendaraan bertipe limousine, yaitu dengan total 26.061 unit. Terendah adalah andere, yaitu 615 unit.

* Analisis 3
  Sedangkan jika dilihat berdasarkan brand, terbanyak dimiliki oleh brand bmw dengan 16.698 unit, dan terendah dimiliki oleh brand porsche dengan 119 unit

* Analisis 4
  Dari visualiasi tersebut, rata-rata harga kendaraan berdasarkan jenis kendaraan dan gearbox, tertinggi diperoleh jenis kendaraan bertipe suv sebesar 4.037 Euro, dengan gearbox automatic. Dapat dilihat bawah harga kendaraan dengan gearbox automatic lebih dominan mahal dibandingkan gearbox manual.

* Analisis 5
  Rata-rata harga kendaraan berdasarkan tipe bahan bakar, harga tertinggi diperoleh jenis kendaraan bertipe hybrid sebesar 3.261 Euro. untuk jenis gearbox-nya juga lebih dominan dengan tipe automatic.

* Analisis 6
  Total rata-rata power kendaraan berdasarkan tipe kendaraan dan gearbox yaitu tertinggi dimiliki oleh jenis kendaraan bertipe andere dengan gearbox not-exit atau tidak diketahui jenisnya sebesar 207.2 PS. dan powerPS dengan gearbox automatic lebih dominan kekuatannya dibandingkan yang lainnya, lalu diikuti dengan gearbox jenis manual.

* Analisis 7
  Rata-rata harga kendaraan berdasarkan jenis kendaraan dan brand, tertinggi dimiliki oleh jenis kendaraan bertipe cabrio dengan brand lada sebesar 5.000 Euro. dan yang terendah dimiliki oleh jenis kendaraan yang bertipe other dengan brand hyundai sebesar 550 Euro.

* Analisis 8
  Dari visualisasi tersebut, dapat dilihat distribusi jumlah hari iklan kendaraan yang dipasang untuk dijual, sebelum kendaraan tersebut terjual.
  dimana analisis yang dipilih berdasarkan brand.

## G. Kesimpulan

Tahun 2000 merupakan puncak penjualan kendaraan, jenis kendaraan limousine dan brand BMW memiliki ketersediaan terbanyak, SUV dengan gearbox automatic memiliki harga rata-rata tertinggi, dan kendaraan hybrid memiliki harga rata-rata tertinggi berdasarkan tipe bahan bakar. Jenis kendaraan andere dengan gearbox not-exit memiliki total rata-rata power tertinggi. Kendaraan bertipe cabrio dengan brand Lada memiliki harga rata-rata tertinggi, sementara tipe other dengan brand Hyundai memiliki harga rata-rata terendah.

## H. Rekomendasi

Rekomendasi yang tepat untuk manajer tim pemasaran berdasarkan temuan bahwa jenis kendaraan berdasarkan merek yang terjual cepat secara online adalah sebagai berikut:

1. Penekanan pada Iklan Berbasis Merek: Dalam strategi pemasaran online, fokuskan upaya iklan lebih pada merek-merek kendaraan yang telah terbukti terjual dengan cepat. Ini dapat mencakup peningkatan anggaran iklan, peningkatan frekuensi, atau peningkatan kreativitas dalam iklan untuk merek-merek ini.

2. Optimasi Situs Web dan Platform Online: Pastikan bahwa situs web dan platform online Anda dioptimalkan untuk meningkatkan visibilitas dan konversi kendaraan merek yang terjual cepat. Ini mungkin melibatkan peningkatan SEO, tampilan yang lebih menarik, dan navigasi yang intuitif.

3. Analisis Data Lanjutan: Terus pantau dan analisis data penjualan untuk memahami tren lebih lanjut tentang merek-merek kendaraan yang terjual cepat. Ini akan membantu dalam penyesuaian strategi pemasaran secara real-time.

Kolaborasi dengan Pihak Eksternal: bisa melalui kemitraan iklan atau kampanye gabungan lainnya.

4. Personalisasi Konten: Lebih lanjut personalisasikan konten pemasaran untuk target audiens yang cenderung membeli merek kendaraan tertentu. Ini bisa melibatkan penggunaan data pelanggan untuk menyesuaikan pesan iklan.

Dengan menerapkan rekomendasi ini, manajer tim pemasaran dapat memanfaatkan temuan tentang merek kendaraan yang terjual cepat secara online untuk meningkatkan kinerja keseluruhan kampanye pemasaran mereka.


## I. Stakeholder
Manajer Tim Marketing e-Bay Kleinanzeigen

## J. Link
<p align='center'>

<a href="https://youtu.be/p4JRzTve51Y">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/febrianto-078f/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://medium.com/@febrianto078/analisis-pasar-mobil-bekas-di-ebay-kleinanzeigen-tren-preferensi-pengguna-dan-7b009b2da7eb">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://github.com/FBTO45/Wrangling_and_Visualization_Project_Pacmann-Used_Car_Data_Set_Modeling">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</a>&nbsp;&nbsp;
</p>

*****
### <center> **Referensi**
*****
#### <center> **Dataset**

<p align='center'>
<a href="https://www.kaggle.com/">
  <img src="https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://data.world/data-society/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/data.world-080842?style=for-the-badge&logo=data.world&logoColor=white" alt="data.world Badge"/>
</a>&nbsp;&nbsp;
<a href="https://archive.ics.uci.edu/ml/index.php">
  <img src="https://img.shields.io/badge/UC Irvine Machine Learning Repository-035a7d?style=for-the-badge&logo=UC Irvine Machine Learning Repository&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://www.bps.go.id/id" target="_blank" rel="nofollow noopener noreferrer">
  <img src="https://img.shields.io/badge/Badan Pusat Statistik-007bff?style=for-the-badge&logo=/_next/image?url=%2Fassets%2Flogo-bps.png&w=1080&q=75 1x, /_next/image?url=%2Fassets%2Flogo-bps.png&w=3840&q=75 2x&logoColor=white" alt="BPS Badge"/>
</a>&nbsp;&nbsp;
<a href="https://data.go.id/home">
  <img src="https://img.shields.io/badge/Satu Data Indonesia-FFFFFF?style=for-the-badge&logo=logo192.png&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://data.jakarta.go.id/">
<img src="https://img.shields.io/badge/Satu Data Jakarta-FFFFFF?style=for-the-badge&logo=Satu-Data-Jakarta&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://opendata.jabarprov.go.id/">
<img src="https://img.shields.io/badge/open data jabar-16a75c?style=for-the-badge&logo=src=open-data-jawa-barat-navbar.svg&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://opendata.surabaya.go.id/">
<img src="https://img.shields.io/badge/Satu Data Surabaya-000080?style=for-the-badge&logo=/images/SatuData.png&logoColor=white"/>
</a>&nbsp;&nbsp;
</p>

#### <p><center> **Catatan**
<h7><center>Anda dapat menggunakan kombinasi beberapa dataset apabila dibutuhkan</h7></center>
<h7><center>Anda dapat menggunakan dataset kantor/perusahaan sendiri, namun pastikan Anda memiliki izin untuk mempublikasikan dataset tersebut.</h7></center>
</p>

*****

#### <center> **Tools**

<p align='center'>
<a href="https://lookerstudio.google.com/">
  <img src="https://img.shields.io/badge/LookerStudio-0088ff?style=for-the-badge&logo=google&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://colab.research.google.com/">
  <img src="https://img.shields.io/badge/Google%20Colab-FF5733?style=for-the-badge&logo=google-colab&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://public.tableau.com/">
    <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white"/>
</a>&nbsp;&nbsp;
</p>

----
<p align='center'>
<a href="https://www.mckinsey.com/~/media/mckinsey/featured%20insights/mckinsey%20global%20surveys/mckinsey-global-surveys-2021-a-year-in-review.pdf">
    <img src="https://img.shields.io/badge/capstoneresearch/-2F4F4F?style=for-the-badge&logo=capstoneresearch&logoColor=white)"/>
</a>&nbsp;&nbsp;
<!-- <a href="https://www.stat.cmu.edu/capstoneresearch/315files_s22/team1.html">
  <img src="https://img.shields.io/badge//media/mckinsey/featured%20insights/mckinsey%20global%20surveys/mckinsey-global-surveys-2021-a-year-in-review1-2F4F4F?style=for-the-badge&logo=capstoneresearch/315files_s22&logoColor=white"/>
</a>&nbsp;&nbsp; -->
<a href="https://www.stat.cmu.edu/capstoneresearch/">
  <img src="https://img.shields.io/badge/capstoneresearch/-2F4F4F?style=for-the-badge&logo=capstoneresearch&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://public.tableau.com/app/discover">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white"/>
</a>&nbsp;&nbsp;
<a href="https://pacmann.io/course/class-detail/1055">
  <img src="https://img.shields.io/badge/Pacmann%20Course-004263?style=for-the-badge&logo=pacmann&logoColor=white"/>
</a>&nbsp;&nbsp;
<!-- <a href="https://www.data-to-viz.com/">
<img src="https://img.shields.io/badge/data-to-viz.com-004263?style=for-the-badge&logo=data-to-viz&logoColor=white"/>
</a>&nbsp;&nbsp; -->
<a href="https://clauswilke.com/dataviz/introduction.html#ugly-bad-and-wrong-figures">
<img src="https://img.shields.io/badge/dataviz/introduction-004263?style=for-the-badge&logo=dataviz&logoColor=white"/>
</a>&nbsp;&nbsp;
</p>
