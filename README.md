# Prediksi Harga Rumah Berdasarkan Luas Tanah Menggunakan Linear Regression

## Deskripsi Proyek
Proyek ini menggunakan model *Machine Learning* sederhana dengan algoritma **Linear Regression** untuk memprediksi harga rumah berdasarkan luas tanah. Contoh ini menggunakan dataset fiktif di mana terdapat hubungan linear antara **Luas Tanah (m2)** dan **Harga Rumah (juta)**. Kode ini melibatkan beberapa langkah seperti pembagian dataset menjadi training dan testing, pelatihan model, evaluasi kinerja model, serta visualisasi hasil.

## Fitur yang Digunakan:
- **Luas Tanah (m2)**: Input fitur (X), mewakili ukuran tanah dalam meter persegi.
- **Harga Rumah (juta)**: Target variabel (y), mewakili harga rumah dalam jutaan rupiah.

## Algoritma yang Digunakan:
- **Linear Regression**: Algoritma regresi linear untuk memprediksi hubungan antara variabel independen (Luas Tanah) dan variabel dependen (Harga Rumah).

## Library yang Digunakan:
1. **NumPy**: Untuk operasi numerik dan array.
2. **Pandas**: Untuk manipulasi dan analisis data.
3. **Matplotlib**: Untuk visualisasi data.
4. **Scikit-learn**: Untuk pembuatan model *Machine Learning*.

## Langkah-langkah Kode:
1. **Pembuatan Dataset**: Dataset sederhana dengan fitur `Luas_Tanah` dan `Harga_Rumah` disimpan dalam DataFrame.
2. **Visualisasi Data**: Scatter plot dibuat untuk memvisualisasikan hubungan antara luas tanah dan harga rumah.
3. **Pembagian Dataset**: Data dibagi menjadi training set dan testing set dengan rasio 80:20 menggunakan `train_test_split`.
4. **Pembuatan dan Pelatihan Model**: Model *Linear Regression* dibuat dan dilatih menggunakan data training.
5. **Prediksi dan Evaluasi**: Model memprediksi harga rumah berdasarkan data testing. Mean Squared Error (MSE) dihitung untuk mengukur performa model.
6. **Visualisasi Prediksi**: Grafik hasil prediksi dibandingkan dengan data sebenarnya.

## Cara Menjalankan Kode
1. **Instalasi Library**: Jika belum terpasang, pastikan untuk menginstal library yang diperlukan dengan perintah berikut:

   ```bash
   pip install numpy pandas matplotlib scikit-learn
