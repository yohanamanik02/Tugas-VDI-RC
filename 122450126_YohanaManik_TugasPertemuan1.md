# Membuat visualisasi data lebih efisien dan efektif: survei

## 1.	Pendahuluan 
Cara ampuh untuk menyajikan data yang menarik untuk manusia adalah dengan membuat visualisasi dari data tersebut, dengan mengubah data menjadi tampilan fisik( contohnya panjang, bentuk, warna, dan sebagainya). Kemampuan dalam menyajikan data secara visual ini memungkinkan perusahaan untuk menganalisis informasi dengan cepat dan membuat Keputusan yang lebih baik. Untuk memvisualisasikan data di mulai dengan mengimpor data, preparation(persiapan), manipulation(manipulasi), mapping(pemetaan), dan rendering. Menentukan visualisasi secara tepat adalah hal yang sulit, bahkan para ahli, dikarenakan pemahaman data apa yang akan divisualisasiakan, cerita yang mana yang harus diceritakan, dan cara memvisualisasikan nya. 

## 2.	Spesifikasi Visualisasi
Secara umum, Bahasa visualisasi data terdiri dari tiga bagian : data, tanda( atau isyarat visual), dan pemetaan.

•	Data : data yang perlu divisualisasikan, transfomasi data.

•	Tanda: jenis visualisasi nya berupa garis, batang, atau titik. Kemudian ukuran nya serta warna nya.

•	Pemetaan: memetakan data ke tanda yang sesuai.

### Kategori Bahasa dalam visualisasi data:
Bahasa visualisasi data diklasifikasikan menjadi empat jenis, yaitu bahasa tingkat rendah, bahasa tingkat tinggi, bahasa berbasis GUI, dan bahasa yang kurang spesifik. Bahasa tingat rendah mengharuskan pengguna untuk menentukan semua elemen pemetaan secara manual. Contoh dari bahasa ini termasuk Prefuse dan Flare, Protovis, D3 dan Vega. Bahasa tingkat tinggi merangkum  detail konstruksi visualisasi seperti fungi pemetaan, serta beberapa property untuk tanda seperti ukuran kanvas, legenda, dan property lainnya. Contoh dari Bahasa ini termasuk ggplot2, Vega-lite, Altair, Echarts, VizQl, dan ZQL. Perlu dicatat bahwa, dalam bahasa tingkat rendah, pengguna harus menentukan fungsi pemetaan. Namun dalam bahasa tingkat tinggi, pengguna hanya perlu menentukan jenis tanda, misalnya, bar dan tidak perlu menentukan fungsi pemetaan antara data dan tanda. 
Visual berbasis GUI merupakan cara dalam memvisualisasikan data yang lebih mudah digunakan untuk memberikan spesifikasi adalah dengan mengikuti “prinsip manipulasi langsung”. Visualisasi data merupakan proses eksplorasi, di mana pengguna perlu terus menyempurnakan spesifikasi (misalnya, menambah/menghapus/mengubah atribut, mengubah jenis bagan) dari visualisasi yang dieksplorasi saat ini hingga mendapatkan visualisasi yang diinginkan dalam proses eksplorasi. Dua kategori visualisasi data interaktif, Polaris dan Tableau, menggunakan penyempurnaan kueri langkah demi langkah untuk menciptakan visualisasi multidimensi. Selain itu, DeepEye dan Voyager memungkinkan eksplorasi aspek dan membantu pengguna menavigasi visualisasi dengan mudah. Meskipun alat interaktif berbasis GUI menyediakan antarmuka sederhana untuk membuat visualisasi umum dengan cepat, yang sangat penting bagi orang-orang non-teknis, mungkin ada tipe bagan yang terbatas dalam templat, dan juga tidak fleksibel untuk mengubah detail visualisasi, seperti lebar batang, dan pemetaan warna, dll. Oleh karena itu, dalam praktiknya, mirip dengan bahasa visualisasi tingkat tinggi, alat interaktif berbasis GUI biasanya digunakan untuk membuat prototipe dengan cepat, atau untuk menemukan visualisasi yang berguna. Setelah itu, bahasa tingkat rendah (misalnya, D3) akan digunakan untuk menyempurnakan atau mengimplementasikan ulang visualisasi yang diinginkan.
Spesifikasi yang kurang jelas tidak dapat memberikan wawasan tentang data. Ini sering terjadi ketika pengguna tidak sepenuhnya memahami semua aspek dari data yang ada, terutama ketika data tersebut besar atau sering diperbarui. Secara umum, untuk spesifikasi yang kurang spesifik, pengguna hanya memberikan beberapa “petunjuk”, dan merupakan tugas sistem visualisasi untuk menafsirkan masukan yang kurang spesifik tersebut, dalam cara yang (mungkin) berbeda. Jenis petunjuk pertama adalah “berbasis referensi”, Dimana pengguna memberikan visualisasi referensi sebagai benih dan system menyarakan visualisasi berdasarkan referensi tersebut. Jenis petunjuk kedua adalah “berbasis kata kunci”, dalam gaya Google. APT menerima tujuan tampilan data pengguna dari kolom yang diinginkan. Jenis ketiga dari petunjuk adalah “berbasis Bahasa alami”, yang memepertimbangkan konteks masukan pengguna dan status sistem dalam “berbasis kata kunci”.

## 3.	Pendekatan Efisien untuk Visualisasi Data
Menyediakan visualisasi yang tepat mungkin tidak selalu dapat dilakukan karena ukuran data yang besar dan kompleksitas kueri yang tinggi. Metode yang digunakan dengan menerjemahkan kueri, integrasi sistem visualisasi dengan DBMS, penggunaan indeks dan komputasi parallel, dan prediksi. Visualisasi dta perkiraan dengan AQP berbasis teknologi, pengambilan sampel, dan pendekatan berbasis presepsi manusia. Visualisasi data progresif dengan teknik agregasi hirarki, teknik indeks dan kubus data.

## 4.	Rekomendasi Visualisasi
Rekomendasi berbasis spesifikasi tidak lengkap dapat menggunakan sistem seperti DeepEye, spesifikasi berbasis referensi dapat menggunakan sistem SeeDB dan Zenvisage. Untuk berbasis perilaku dapat menggunakan Harvest, menganalisis pola interaksi pengguna dengan visualisasi dan kemudian merekomendasikan visualisasi yang paling relevan berdasarkan pola tersebut.

## 5.	Arah penelitian lainnya
•	Persiapan data untuk visualisasi data : data yang sering kotor (duplikat, nilai yang hilang, dsb) dapat menyesatkan pengguna jika divisualisasikan tanpa dibersihkan dahulu . maka peluang untuk penelitian nya yaitu mendeteksi visualisasi yang bias dan pembersihan data berdasarkan tugas. 

•	Tolak ukur visualisasi data : tolak ukur harus sesuai dengan tugas analisis visual, menyediakan jejak dan data yang dapat digunakan kembali, dan dalam kasus rekomendasi, memiliki cakupan dan kualitas label yang tinggi. Peluang penelitian nya kategorisasi visualisasi dan data pelatihan.

•	Visualisasi data untuk aplikasi terkait database : dengan pesatnya perkembangan teknik visualisasi, semakin banyak peluang untuk menggunakan visualisasi data untuk aplikasi yang terkait dengan basis data. Peluang penelitian nya visualisasi data untuk penemuan data dan visualisasi data untuk debungging.

