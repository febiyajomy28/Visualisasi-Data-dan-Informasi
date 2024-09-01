Resume Jurnal
FEBIYA JOMY PRATIWI
122450074

Visualisasi data digunakan sebagai Gambaran umum yang baik tentang data yang sangat besar, dan mempermudah interpretasi hasil analisis data kepada ilmuwan data. Perkembangan visualisasi data telah mencapai kemajuan karena kontribusi dari berbagai komunitas seperti komunitas grafis computer, komunitas visualisasi dan komunitas database. Selain itu visualisasi data juga banyak dipakai diberbagai aplikasi terkait database, seperti excel, google sheet dan banyak lainnya.
 
Alur visualisasi data yaitu
•	pertama import data yaitu pengambilan data yang diperlukan dari sumber data yang diinginkan 
•	kedua persiapan data dimana data yang diimpor untuk visualisasi akan disiapkan dahulu seperti normalisasi nilai, koreksi entri yang salag dan interpolasi nilai yang hilang,
•	ketiga manipulasi data dimana memilih data atau memfilter dari komunitas visualisasi dan operasi lainnya seperti penggabungan dan pengelompokan,
•	keempat pemetaan yaitu memetakan data yang siperoleh dari proses diatas ke dalam geoetri primitive (misalnya titik dan garis), beserta atributnya misalnya warna, posisi, dan ukuran. 
•	Dan terakhit rendering adalah mengubah data geometri menjadi representasi visual.  
Setelah adanya alur kemudian mengidentifikasi tiga arah yang membuat visualisasi data lebih efisien dan efektif yaitu:
1.	 spesifikasi visualisasi yang menyediakan berbagai cara agar pengguna dapat menentukan apa yang mereka inginkan, 
2.	pendekatan efisien untuk visualisasi data yaitu pembuatan visualisasi data yang efisien dan terukur terutama untuk manipulasi data dan pemetaan, 
3.	rekomendasi visualisasi data merupakan hal yang sulit karena pemahaman tentang data yang divisualisasikan cerita mana yang diceritakan dan sebagainya.

Bahasa visualisasi data terbagi tiga bagian yaitu data yang perlu divisualisasikan dengan operasi group, filter dan pengurutan digunakan untuk mengubah rekaman data tertentu,kedua yaitu tanda (atau isyarat visual), dan pemetaan diantara keduanya.

Kategorisasi Bahasa visualisasi data didasarkan pada ekspresifnya, berbagai tingkat spresifikasinya visualisasi Bahasa juga melalui aksesibilatsnya , semakin tinggi tingkat bahasanya semakin mudah digunkan
-	Bahasa tingkat rendah: 
•	Prefuse dan Flare : perpustakaan visualisasi data berbasis java
•	Proto-vis : perangkat grafis berbasis JavaScript deklaratif
•	D3 : pengembangan dari protovis dan lebih efektif dalam menangani interaksi pengguna
•	Vega dan reaktif vega : menyediakan tata Bahasa interaksi deklaratif yang dapat disusun 
-	Bahasa tingkat tinggi:
•	Ggplot : Bahasa grafis berlapis yang tertanama di r
•	Vega-lite : mendukung desain interaktif yang dapat disusun 
•	Altair: membuat Vega-lite tersedia untuk komunitas python.
•	Echarts : pengembangan terbaru dalam Bahasa visualisasi deklaratif
•	VizQL berkembang dari system 

Operasi visual berbasis GUI yaitu Qlik, Excel, Google sheets, Amazon Quick-sight, Microsoft Power BI, Google Fusion Tables , MsDesigner, Lyra , Keishif , Data llustrator. Tujuannya adalah untuk menunjukkan cara berbeda yang dapat ditentukan pengguna visualisasi terlepas dari menggunakan Bahasa deklaratif atau operasi visual.

Visualisasi data yang tepat menggunakan system basis data yaitu DBMS yang dapat membaca dan menampilkan visualisasi data dengan cara menerjemahkan kueri visualisasi ke kueri yang diterima oleh system. Mengintegrasikan system visualisasi dengan DBMS ini mendukung dua hubungan data dan skala. Peringkat visualisasi di Ermac direpresentasikan sebagai rencana visualisasi logis (LVP) dan LVP dikompilasi menjadi queri seperti SQL. Pengembagan lebih lanjut dari Ermac diusl untuk menyediakan Bahasa mirip SQL,DeVlL, untuk mewakili keuda statis dan visualisasi interaktif.
Teori pengoptimalan  untuk visualisasi interaktif DVMS:
•	Kolom menyimpan 
•	Indeks

Falcon menggunakan Teknik pengindeksan untuk mengurangi waktu interaksi untuk menyikqt dan menghubungkan dalam visualisasi. Visualisasi yang digunakan adalah tampilan aktif dan tampilan pasif. 
Komputasi Paralel menggunakan pemrosesan query agregasi pada ubin data di imMensdiparalelkan menggunakan representasi indeks padat dari ubin data. Harald dkk menyediakan arsitektur multithreading untuk eksplorasi visualisasi interaktif
Prediksi dan pengambilan awal salah satu Langkah penting dalam visualisasi data atau bisa disebut eksplorasi data. Seringkali visualisasi yang dieksplorasikan saat ini biasanya terinspirasi dari visualisasi sebelumnya. Dengan kata lain pengguna dapat memperoleh visualisasi berikutnya dengan mengubah parameter visualisasi data ini atau memperbesar/ memperkecil untuk mendapatkan informasi detail/ keseluruhan.

Mengkategorikan teknologi visualisasi data dan prediksi menjadi dua jenis
•	Visualisasi yang sedang dieksplorasi yaitu XmdvTool untuk pengelompokan tupel dalam rincian berbeda untuk mendukung navigasi hierarki pengguna. Sistem caching menggunakan LRU sebagai kebijakan pengganti dan strategi prefetch-ing berbasis visualisasi yang sedang dieksplorasi adalah dengan memilih arah secara acak dari posisi data yang sedang dieksplorasi.
•	Data Historis, yaitu teknik memanfaatkan lintasan historis untuk prefetch-ing. XmdvTool mengusulkan tiga strategi untuk mengambil data terlebih dahulu berdasarkan data historis: arah, focus dan vector 
•	Pendekatan berbasis pembelajaran mesin juga telah dipelajari. ForeCache mempartisi data menjadi blok atau ubin data di tingkat yang berbeda dan memprediksi ubin data kepada pengguna.

Studi Kasus 
1	Kyrix adalah sistem visualisasi data interaktif yang dapat diskalakan. Kyrix menyediakan antarmuka spesifikasi visualisasi deklaratif di ujung depan dan pemrosesan visualisasi terukur yang efektif di ujung belakang,
  •	Spesifikasi Visualisasi di Front end. Ada dua abstraksi dalam bahasa spesifikasi visualisasi Kyrix: kanvas dan lompat.
  •	Pendekatan Efisien untuk Visualisasi Data di Back-end
2	TDE adalah mesin data yang disesuaikan untuk visualisasi di Tableau 6.0. TDE mengoptimalkan mesin data terutama dalam perspektif berikut. 
  •	Penyimpanan dan Kompresi Berorientasi Kolom. Karena tingginya biaya I/O dari database Tableau Firebird sebelumnya dan data visualisasi biasanya disimpan dalam kolom yang berbeda, teknik penyimpanan dan kompresi berorientasi kolom telah dirancang untuk memecahkan masalah ini di TDE.
  •	Pemesanan Ulang Operator. 
  •	Pengurangan Kardinalitas. Untuk kolom dengan kardinalitas tinggi kolom, TDE secara otomatis mengubah kolom ini ke hierarki yang lebih tinggi.
  •	Dukungan Visualisasi Lainnya. TDE menyediakan domain. Informasi (misalnya, kardinalitas, nilai maksimum dan minimum domain) kolom. domain ini informasi dapat digunakan untuk memilih tingkat detail nformasi dapat digunakan untuk memilih tingkat detail visualisasi bagi pengguna.

Perkiraan visualisasi data
1.	Berbasis AQP yaitu cara mudah untuk menghasilkan perkiraan visualisasi dalam waktu interaktif 
2.	Berbasis Pengambilan Sampel Inkremental Beberapa karya  mencoba menghubungkan teknik kueri data inkremental dengan visualisasi data.
3.	Berbasis Persepsi Manusia Terkadang, meningkatkan ukuran sampel tidak selalu meningkatkan kualitas visualisasi.

Visualisasi data progresif
Secara umum, mereka membangun struktur hierarki dengan menggabungkan data pada tingkat yang berbeda, misalnya, ukuran wadah yang berbeda, rentang nilai temporal yang berbeda, zona nilai spasial yang berbeda. 
Binning Berbasis Rentang imMens menyediakan visualisasi resolusi berbeda dengan mengubah ukuran bin. Tempat sampah dengan resolusi yang sama memiliki rentang yang sama. Data multidimensi di imMens dipartisi menjadi kubus data, dan kubus dipartisi menjadi ubin dengan level berbeda
Pengelompokan Berbasis Rentang dan Konten Karya menyediakan dua struktur pohon untuk eksplorasi hierarki: HETree-R (HETree berbasis rentang) dan HETree-C (HETree berbasis konten). HETree-R mirip dengan imMens, dan simpul daun HETree-R menunjukkan titik data dalam rentang lebar yang sama, sedangkan HETree-C memiliki jumlah titik data yang sama di semua simpul daun. 

1.	Rekomendasi berdasarkan spesifikasi
 •	Spesifikasi tidak lengkap yaitu sistem rekomendasi visualisasi dengan spesifikasi kosong tidak memerlukan masukan pengguna, sedangkan sistem rekomendasi dengan spesifikasi parsial menerima masukan spesifikasi elemen visualisasi parsial pengguna untuk visualisasi yang diinginkan. Ada dua metode umum yang digunakan untuk menentukan peringkat kandidat visualisasi:
     1.	Solusi berbasis aturan, yang biasanya berupa metrik efektivitas persepsi manusia, diukur sebagai skor efektivitas dengan mempertimbangkan tipe data, informasi statistik, preferensi visual manusia, dll. 
         -	Kerangka aturan statistic sistem rekomendasi berbasis aturan statistik. Ini dapat memberi peringkat visualisasi proyeksi paralel sumbu 1D atau 2D (histogram, plot kotak, dan plot sebar) kepada pengguna berdasarkan metrik peringkat statistik yang berbeda.
        -	Kerangka aturan perseptual memberi peringkat antara jenis visualisasi yang sama (misalnya, histogram, plot kotak) dengan metrik statistik tunggal.
    2.	Solusi berbasis pembelajaran mesin, pertama-tama mengumpulkan data pelatihan, yang berasal dari crowdsourcing atau web, lalu latih model pemeringkatan yang mengambil ruang masukan X sebagai daftar fitur vektor, dan Y ruang keluaran yang terdiri dari nilai (atau peringkat). 
 •	Spesifikasi berbasis referensi, yaitu sistem akan merekomendasikan visualisasi yang mirip atau berbeda dari yang diberikan referensi dalam aspek tertentu.
   o	SeeDB berbasis deviasi merekomendasikan visualisasi dengan penyimpangan dengan beberapa visualisasi referensi.
   o	Profiler berbasis anomali merekomendasikan visualisas yang paling dapat membedakan anomali dalam visualisasi utama.
   o	Zenvisage berbasis Kesamaan/Jarak mencoba menemukan visualisasi menarik lainnya ketika pengguna memberikan visualisasinya tren, pola, atau wawasan yang diinginkan. pentingnya Fungsi jarak yang digunakan oleh Zenvisage adalah Jarak Euclidean dan Pembengkokan Waktu Dinamis.

2.	Rekomendasi berbasis perilaku
menangkap perilaku pengguna saat ini sebagai masukan, kemudian menyimpulkan tugas yang diinginkan pengguna dan merekomendasikan visualisasi yang berguna berdasarkan tugas mereka.
HARVEST adalah sistem rekomendasi visualisasi berbasis perilaku. HARVEST dapat mendeteksi pola pemindaian, yang artinya bahwa pengguna ingin membandingkan beberapa atribut di antara beberapa atribut objek serupa, sehingga HARVEST dapat merekomendasikan diagram batang.

3.	Rekomendasi yang dipersonalisasi
menangkap riwayat perilaku pengguna sebagai masukan untuk merekomendasikan visualisasi menarik yang dipersonalisasi
•	Model Linier VizDeckvmemberikan hasil rekomendasi visualisasi yang dipersonalisasi dengan melatih model linier setiap pengguna menggunakan perilaku historisnya.
•	Pemfilteran Kolaboratif Selain melatih model untuk masing-masing pengguna, ternyata ada banyak teknik lainnya:
  1)	Pemfilteran Kolaboratif
  2)	Pemfilteran Berbasis Konten
  3)	Penyaringan Hibrid.

Persiapan data untuk visualisasi data
1)	Analisis Bagaimana-jika untuk Outlier
2)	Mengevaluasi Visualisasi dengan Data yang Hilang
3)	Mendeteksi visualisasi yang bias
4)	Pembersihan data sadar tugas

Tolok ukur visualisasi data : Sebuah karya penelitian VizNet telah menyajikan korpus skala besar yang berisi lebih dari 31 juta kumpulan data yang dikumpulkan dari repositori data terbuka dan galeri visualisasi online.
Peluang dalam penggunaan visualisasi data untuk aplikasi yang berhubungan dengan database
1)	Visualisasi data untuk penemuan data
2)	Visualisasi data untuk debugging data
