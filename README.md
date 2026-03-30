# Bike Sales Customer Behavior Analysis with Excel Dashboard
This project analyzes bike sales data using Microsoft Excel to uncover customer purchasing behavior. The data was cleaned, transformed, and analyzed using pivot tables, then visualized through an interactive dashboard. This project highlights how Excel can be used to turn raw data into actionable business insights for better decision-making.

## 1. Backround
Dalam dunia bisnis yang kompetitif, memahami perilaku pelanggan menjadi kunci penting dalam meningkatkan penjualan dan menyusun strategi pemasaran yang efektif. Perusahaan perlu mengetahui faktor-faktor apa saja yang memengaruhi keputusan pelanggan dalam membeli suatu produk, termasuk karakteristik demografis, kondisi finansial, serta kebiasaan sehari-hari.

Dataset penjualan sepeda yang digunakan dalam proyek ini menyediakan informasi terkait profil pelanggan seperti usia, jenis kelamin, pendapatan, tingkat pendidikan, pekerjaan, serta jarak perjalanan harian (commute distance). Data ini memiliki potensi untuk dianalisis lebih lanjut guna mengidentifikasi pola pembelian dan segmentasi pelanggan.

## 3. Tujuan
Tujuan dari proyek ini adalah:

- Menganalisis perilaku pelanggan dalam pembelian sepeda berdasarkan data demografis dan finansial
- Mengidentifikasi faktor-faktor yang memengaruhi keputusan pembelian pelanggan
- Melakukan segmentasi pelanggan berdasarkan karakteristik seperti usia, pendapatan, dan jarak perjalanan
- Menyajikan hasil analisis dalam bentuk dashboard yang mudah dipahami
- Menghasilkan insight yang dapat mendukung strategi pemasaran dan pengambilan keputusan bisnis

## 4. Dataset
Dataset yang digunakan dalam proyek ini merupakan data penjualan sepeda yang berisi informasi terkait profil demografis, kondisi finansial, dan perilaku pelanggan.

Jumlah data: ±1.000 baris

Fitur dalam dataset meliputi:

- ID: Identitas unik setiap pelanggan
- Marital Status: Status pernikahan (Married/Single)
- Gender: Jenis kelamin pelanggan (Female/Male)
- Income: Pendapatan tahunan pelanggan
- Children: Jumlah anak
- Education: Tingkat pendidikan
- Occupation: Pekerjaan pelanggan
- Home Owner: Status kepemilikan rumah (Yes/No)
- Cars: Jumlah kendaraan yang dimiliki
- Commute Distance: Jarak perjalanan harian pelanggan
- Region: Wilayah tempat tinggal pelanggan
- Age: Usia pelanggan
- Purchased Bike: Status pembelian sepeda (Yes/No)

## 5. Data Cleaning & Preprocessing
Pada tahap ini, dilakukan proses pembersihan dan persiapan data untuk memastikan data siap dianalisis dan menghasilkan insight yang akurat.

Beberapa langkah yang dilakukan meliputi:

1. Data Cleaning:

Memeriksa dan memastikan tidak terdapat missing values atau data duplikat yang dapat memengaruhi hasil analisis.

2. Standarisasi Data:

Mengubah format data agar lebih konsisten dan mudah dipahami, seperti:
  - Mengubah kode kategori pada fitur Marital status dari M/S menjadi format lengkap Married/Single
  - Mengubah kode kategori pada fitur gender dari F/M menjadi format lengkap Female/Male
  - Menyederhanakan format pada kolom Commute Distance agar lebih terstruktur
  
3. Data Transformation:

Melakukan penyesuaian tipe data dan format, seperti memastikan kolom numerik (Income, Age, Cars) dalam format angka yang sesuai.

5. Feature Engineering:

Membuat fitur baru untuk mempermudah analisis, seperti:
  - Mengelompokkan usia ke dalam kategori (Age Brackets) untuk segmentasi pelanggan

6. Data Validation:

Melakukan pengecekan ulang untuk memastikan data sudah konsisten, bersih, dan siap digunakan dalam proses analisis dan pembuatan dashboard.

Proses ini penting untuk meningkatkan kualitas data sehingga hasil analisis menjadi lebih valid dan dapat diandalkan dalam mendukung pengambilan keputusan bisnis.

## 6. Key Insight
Berdasarkan hasil analisis dan visualisasi pada dashboard, diperoleh beberapa insight utama terkait perilaku pelanggan dalam pembelian sepeda:

1. Pendapatan berpengaruh terhadap keputusan pembelian

Pelanggan yang membeli sepeda cenderung memiliki rata-rata pendapatan lebih tinggi dibandingkan yang tidak membeli, baik pada laki-laki maupun perempuan.

2. Kelompok usia middle-age memiliki tingkat pembelian tertinggi

Dibandingkan kelompok usia lainnya, pelanggan pada kategori middle age menunjukkan jumlah pembelian sepeda paling tinggi, sehingga menjadi segmen potensial.

3. Jarak perjalanan memengaruhi perilaku pembelian

Pelanggan dengan jarak perjalanan tertentu (terutama jarak menengah) menunjukkan kecenderungan lebih tinggi untuk membeli sepeda, yang mengindikasikan adanya kebutuhan mobilitas yang relevan.

4. Perbedaan perilaku berdasarkan gender relatif kecil

Tidak terdapat perbedaan signifikan antara laki-laki dan perempuan dalam keputusan pembelian, sehingga strategi pemasaran dapat difokuskan lebih pada faktor lain seperti pendapatan dan usia.

5. Segmentasi pelanggan penting untuk strategi bisnis

Kombinasi faktor seperti pendapatan, usia, dan jarak perjalanan dapat digunakan untuk mengidentifikasi target pelanggan yang lebih potensial dalam meningkatkan penjualan.

## 7. Business Recomendation
Berdasarkan insight yang diperoleh dari analisis data, berikut beberapa rekomendasi yang dapat diterapkan untuk meningkatkan penjualan sepeda:

1. Target pelanggan dengan pendapatan menengah ke atas

Fokuskan strategi pemasaran pada segmen pelanggan dengan pendapatan lebih tinggi karena memiliki kecenderungan membeli yang lebih besar.

2. Prioritaskan segmen usia middle-age

Kelompok usia ini merupakan kontributor pembelian terbesar, sehingga dapat dijadikan target utama dalam kampanye pemasaran.

3. Optimalkan promosi berdasarkan kebutuhan mobilitas

Pelanggan dengan jarak perjalanan menengah menunjukkan potensi tinggi, sehingga promosi dapat difokuskan pada manfaat sepeda sebagai solusi transportasi harian.

4. Gunakan segmentasi untuk personalisasi strategi marketing

Kombinasi faktor seperti usia, pendapatan, dan jarak perjalanan dapat digunakan untuk membuat strategi pemasaran yang lebih tepat sasaran.
