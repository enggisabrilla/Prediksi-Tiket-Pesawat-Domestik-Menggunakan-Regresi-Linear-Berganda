# PREDIKSI HARGA TIKET PESAWAT DOMESTIK MENGGUNAKAN METODE REGRESI LINEAR BERGANDA 

Bandar Udara di Indonesia mengalami perkembangan yang sangat cepat di era globalisasi ini. Ditandai semakin banyaknya Bandar Udara baru. Bandar Udara Internasional Juanda Surabaya Sebagai salah satu bandar udara tersibuk ke 3 di Indonesia dan PT. Gapura Angkasa yang bergerak di bidang ground handling mendukung operasional maskapai Pelita Air yang baru beroperasi di tahun 2022. Dengan adanya kebutuhan perjalanan yang cepat, nyaman, dan efisien, pesawat menjadi pilihan utama untuk perjalanan jarak jauh, termasuk rute domestik populer seperti Surabaya-Jakarta. Rute ini menjadi salah satu rute tersibuk di Indonesia, didukung oleh berbagai maskapai penerbangan yang menawarkan layanan dengan variasi harga tiket. 

Harga tiket pesawat selalu mengalami perubahan, sehingga ada sebagian konsumen yang merasa kebingungan dengan perubahan harga tiket pesawat di setiap waktunya. Praktik penetapan harga tiket pesawat di Traveloka.com mengalami fluktuasi harga. Dalam kurun waktu satu hari harga tiket pesawat bisa berubah-ubah meskipun menggunakan maskapai yang sama, kenaikan harga biasa terjadi ketika libur nasional atau akhir pekan

Penelitian ini bertujuan memprediksi harga tiket pesawat domestik pada rute Surabaya-Jakarta menggunakan metode Regresi Linear Berganda. Metode ini dipilih karena mampu menganalisis hubungan antara variabel dependen, yaitu harga tiket, dengan variabel independen seperti maskapai, waktu keberangkatan, waktu kedatangan, lama perjalanan, kapasitas bagasi, dan jenis penerbangan. Hasil analisis diharapkan mengidentifikasi faktor utama yang memengaruhi harga serta menggambarkan pola harga pada rute dengan tingkat permintaan tinggi ini. Prediksi harga tiket penting bagi penumpang untuk merencanakan perjalanan lebih efisien dan memahami pola fluktuasi harga. Sementara itu, maskapai dapat menggunakan hasil penelitian ini untuk menyusun strategi harga yang kompetitif, mengoptimalkan pendapatan, dan meningkatkan kepuasan pelanggan.

## Pengumpulan Data
Data dalam penelitian ini diperoleh dari proses scraping dari web Traveloka selama 2 bulan yaitu pada tanggal 23 Januari – 23 Maret di hari senin-jumat. 

## Kesimpulan

•	Model regresi linier berganda yang digunakan cukup baik dalam memprediksi harga dengan R2 Score sebesar 81.95%.

•	Bagasi memiliki pengaruh yang paling kuat terhadap harga, sementara lama_perjalanan juga berpengaruh tetapi dalam arah negatif.

•	Tidak ada masalah serius pada autokorelasi, tetapi potensi multikolinearitas pada variabel bagasi perlu diperhatikan.

•	Hasil uji statistik menunjukkan bahwa model signifikan secara keseluruhan, dan variabel independen secara parsial memiliki hubungan yang bermakna dengan variabel target.

