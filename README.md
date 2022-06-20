# UAS-VISDAT-SARAH-MUTIA

<h1 align="center"> Visualisasi Data Provinsi di Indonesia Berdasarkan Indikator Sosial Kependudukan </h1>
<p align="center">(Analisis Hunian Layak Huni)</p>
<p align="justify">Indonesia merupakan urutan keempat Negara dengan penduduk terbanyak di dunia. Dengan banyaknya jumlah penduduk di Indonesia, timbul pertanyaan mengenai keadaan dan kondisi masyarakat Indonesia. Apakah semua rakyat Indonesia sudah memiliki kehidupan layak atau belum. Kehidupan yang layak dapat dilihat dari pemenuhan kebutuhan masyarakat. Kebutuhan primer manusia terdiri dari tiga yaitu Sandang, Papan dan Pangan. tujuan dari penelitian ini adalah untuk memvisualisasikan hasil dari pengelompokkan beberapa indikator sosial kependudukan berdasarkan provinsi. Pengelompokkan ini dilakukan untuk melihat bagaimana persebaran penduduk Indonesia berdasarkan indikator tersebut yang selanjutnya diharapkan dapat membantu pemerintah dalam pengambilan kebijakan sesuai dengan hasil pengelompokkan. Data yang digunakan dalam penelitian ini adalah data sekunder yang bersumber dari Badan Pusat Statistik yaitu data Persentase Rumah Tangga menurut Provinsi dan Sumber Penerangan Listrik PLN 1993 – 2020, Persentase Rumah Tangga menurut Provinsi dan Sumber Air Minum Layak 1993 – 2020, Persentase Rumah Tangga menurut Provinsi dan Memiliki Akses terhadap Sanitasi Layak, Persentase Rumah Tangga menurut Provinsi dan Status Kepemilikan Rumah Kontrak/sewa, dan Persentase Rumah Tangga yang memiliki Akses Terhadap Hunian Yang Layak dan Terjangkau menurut Provinsi. </p>
<h2 align="justify">Data yang digunakan</h2>
<p align="justify">Data yang digunakan pada penelitian ini adalah data hasil Susenas yang dilakukan oleh Badan Pusat Statistik.</p> 
Variabel bebas yang digunakan:
<p align="justify">- Persentase Rumah Tangga menurut Provinsi dan Sumber Penerangan Listrik PLN 1993 – 2020</p>
<p align="justify">- Persentase Rumah Tangga menurut Provinsi dan Sumber Air Minum Layak 1993 – 2020</p>
<p align="justify">- Persentase Rumah Tangga menurut Provinsi dan Memiliki Akses terhadap Sanitasi Layak</p>
<p align="justify">- Persentase Rumah Tangga menurut Provinsi dan Status Kepemilikan Rumah Kontrak/sewa</p>
<p align="justify">- Persentase Rumah Tangga yang memiliki Akses Terhadap Hunian Yang Layak dan Terjangkau menurut Provinsi</p>
<br></br>
<h2>Analisis Data</h2>
<h3>Preprocessing</h3>
<p align="justify"> Data yang digunakan pada penelitian ini dikumpulkan secara kumulatif. Sebelum dilakukan proses lebih lanjut, akan dilakukan preprocessing data untuk mengubah data mentah menjadi informasi yang lebih bersih untuk pengolahan </p>
<p align="center">
<img src = "https://github.com/UmiMaisyuroh/UASVisDat/blob/main/data%20visualisasi%20uas.png" width="300" height="450" />
</p>
<br></br>

<h3>Analisis Deskriptif</h3>

<p align="center">
<img src = "https://github.com/UmiMaisyuroh/UASVisDat/blob/main/2.png" width="400" height="250" />
</p>
<p align="justify">Berdasarkan hasil ringkasan data variabel penelitian menggunakan software R di atas diketahui bahwa untuk variabel Listrik PLN mempunyai nilai minimum sebesar 43,14% dan nilai maksimum sebesar 99,99% dengan nilai rata-rata sebesar 93,28%. Untuk variabel Air Minum Layak mempunyai nilai minimum sebesar 62,47% dan nilai maksimum sebesar 99,84 % dengan nilai rata-rata sebesar 85,41%. Untuk variabel Sanitasi Layak memiliki nilai minimum sebesar 40,31% dan nilai maksimum sebesar 96,96% dengan nilai ratarata sebesar 79,81%. Untuk variabel Kontrak/Sewa memiliki nilai minimum sebesar 2,15% dan nilai
maksimum sebesar 37,71 dengan nilai rata-rata
9,644%. Terakhir untuk variabel Hunian Layak dan
Terjangkau menurut Provinsi memiliki nilai minimum
sebesar 28,56% dan nilai maksimum sebesar 86,19%
dengan nilai rata-rata sebesar 58,02%. </p>
<br></br>
<h2> Clustering</h2>
 <p align="justify"> Berdasarkan hasil clustering dengan metode k-means didapatkan 3 klaster.Klaster pertama adalah kumpulan provinsi yang persentase kesediaan air minum layak atau sanitasi layak nilainya di bawah atau sama dengan rata-rata. Untuk Hunian layak huni pada cluster 1 masih banyak yang di bawah rata-ratanya (58,02%). Klaster 2 adalah kumpulan provinsi yang nilai persentase hampir semua variabelnya berada di atas rata-rata. Dalam kata lain, provinsi yang ada pada cluster 2 adalah provinsi yang mempunyai persentase Hunian layak huni yang tinggi. Klaster 3 berisikan 1 provinsi yaitu provinsi Papua. Persentase semua variabelnya berada di bawah rata-rata artinya, di Provinsi Papua masih sedikit Hunian yang layak huni.</p>
 <br></br>
<h2> Perancangan Dashboard</h2>
<p align="justify"> Perancangan dashboard untuk memvisualisasikan indikator sosial kependudukan dibuat menggunakan platform Tableau Desktop. Dashboard dirancang menggunakan warna pastel keungu-unguan karena unik dan eksotis.</p>
<br></br>
<h2> Pembuatan Dashboard Visualisasi </h2>
<p>Dashboard dapat diakses secara daring melalui link https://public.tableau.com/app/profile/umi.maisyuroh/viz/INSYAALLAHUDHBENER/Dashboard1?publish=yes </p>
<p>Jenis visualisasi yang digunakan adalah :</p>
<p> * Peta Tematik</p>
<p> * Bar Chart </p>
<p> * Tabel </p>
<p> * Horizontal Bar Chart </p>
<br> </br>
<h2>Tampilan Dashboard</h2>
<p align="center">
  <img src="https://github.com/UmiMaisyuroh/UASVisDat/blob/main/5.png" width ="900" height="550"/>
  </p>
  <p align="justify">Dashboard ini menampilkan visualisasi data dari beberapa indikator sosial kependudukan untuk analisis hunian layak huni. Pada peta tematik ditampilkan persebaran hunian layak huni menurut provinsi di Indonesia, 5 Provinsi dengan persentase rumah tangga dengan sumber penerangan listrik PLN, 10 provinsi dengan proporsi rumah tangga yang memiliki akses terhadap layanan sanitasi layak tertinggi ,5 provinsi dengan persentase terendah rumah tangga dengan sumber air minum layak tahun 2021, dan proporsi status kepemilikan rumah tangga menurut provinsi.</p>
 
<h2> Tambahan pada Dashboard</h2>
<p> Pada dashboard ditampilkan juga beberapa tambahan seperti : </p>
<p align="justify"> - Tooltip : Pada saat kursor diarahkan ke visualisasi data misalnya pada batang bar chart, maka akan ditampilkan keterangan dari bar tersebut. Hal ini dibuat untuk memperindah tampilan agar tidak terlihat berantakan</p>
<p align="center">
 <img src="https://github.com/UmiMaisyuroh/UASVisDat/blob/main/4.png" width="900" height="550"/></p>
<p align="justify"> - Pilih kelompok : Pada beberapa visualisasi, ditampilkan pilihan berupa kelompok tahun dari data </p>
<p align="center">
 <img src="https://github.com/UmiMaisyuroh/UASVisDat/blob/main/3.png" width="900" height="550"/></p>
<br></br>
<h2>Embed Dashboard Tableau</h2>
<p align="justify"> Dashboard yang dibuat di tableau dapat dipublikasikan dan diakses secara online. Jika ingin menyimpan dalam format html maka hal yang harus dilakukan adalah mengembed dashboard dengan cara menyalin embed code pada tableau lalu diletakkan pada bagian div. 
