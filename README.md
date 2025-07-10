# Project-Portofolio
Repositori ini berisi proyek-proyek data analysis yang saya kerjakan, antara lain analisis penyakit jantung menggunakan data medis untuk menemukan faktor risiko utama, serta prediksi penjualan BBM berbasis time series untuk membantu estimasi distribusi energi. Proses meliputi data preprocessing, eksplorasi data, visualisasi, serta pembuatan model analitik dan prediktif menggunakan Python
# Analisis Penyakit Jantung
File Project :https://github.com/Brilyann/Project-Portofolio/tree/main/Analisis%20Penyakit%20Jantung  
Proyek ini bertujuan untuk menganalisis faktor-faktor yang mempengaruhi risiko penyakit jantung menggunakan dataset yang saya dapatkan dari kaggle. Saya melakukan proses data cleaning, eksplorasi data (EDA), dan visualisasi untuk mengidentifikasi pola dari variabel seperti usia, tekanan darah, kolesterol, dan detak jantung. Selain itu, saya juga melakukan modeling sederhana untuk memprediksi kemungkinan pasien terkena penyakit jantung berdasarkan fitur yang tersedia.
# Prediksi Penjualan BBM
File Project : 
Proyek ini bertujuan untuk melakukan prediksi jumlah penjualan Bahan Bakar Minyak (BBM) jenis Pertalite menggunakan pendekatan time series forecasting berbasis metode Long Short-Term Memory (LSTM).
Langkah-langkah yang Dilakukan:
- Pra-pemrosesan data: Menggabungkan kolom Tahun dan Bulan menjadi format datetime, membersihkan data, serta menyaring data untuk jenis BBM tertentu (Pertalite).
- Visualisasi tren historis: Menganalisis pola musiman dan jangka panjang pada penjualan BBM dari waktu ke waktu.
- Normalisasi data: Menggunakan MinMaxScaler untuk memastikan data berada pada skala yang sesuai untuk model LSTM.
- Pembentukan data urutan (sequence): Mengubah data menjadi bentuk time window agar dapat digunakan sebagai input LSTM.
- Pelatihan model LSTM: Membangun dan melatih model LSTM dengan library TensorFlow/Keras untuk mempelajari pola historis penjualan.
- Forecasting: Melakukan prediksi penjualan BBM selama 3 bulan ke depan berdasarkan data sebelumnya.
- Evaluasi dan visualisasi hasil: Membandingkan hasil prediksi terhadap data aktual untuk menilai performa model.
- Penyimpanan model dan scaler: Menyimpan model (.keras) dan normalizer (.pkl) untuk digunakan kembali tanpa perlu pelatihan ulang.

Tools dan Library:
- Python
- Pandas
- Matplotlib
- Seaborn
- TensorFlow/Keras
- Scikit-Learn
  
Hasil & Manfaat:
Model ini dapat digunakan untuk mendukung pengambilan keputusan oleh perusahaan, seperti:
- Perencanaan distribusi dan stok BBM
- Prediksi kebutuhan operasional ke depan
- Deteksi pola musiman untuk menghindari kelebihan atau kekurangan pasokan
