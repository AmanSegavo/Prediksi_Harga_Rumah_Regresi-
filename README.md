# Prediksi_Harga_Rumah_Regresi

Proyek ini bertujuan untuk memprediksi harga rumah di Ames, Iowa menggunakan algoritma Random Forest Regressor. Dataset yang digunakan berasal dari kompetisi Ames Housing di Kaggle, dengan modifikasi kolom ke dalam Bahasa Indonesia.

## Deskripsi Dataset Submission

- `Id`: Nomor unik untuk setiap rumah.
- `HargaRumah`: Harga rumah yang diprediksi oleh model (dalam satuan USD).

## Tools dan Library

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

## Langkah-Langkah Proyek

1. **Eksplorasi Data Awal (EDA):**
   - Analisis distribusi harga rumah.
   - Analisis fitur yang memengaruhi harga.

2. **Preprocessing Data:**
   - Menghandle missing values.
   - Encoding kategori.
   - Feature scaling.

3. **Modeling:**
   - Menggunakan Random Forest Regressor.
   - Cross-validation dan hyperparameter tuning.

4. **Evaluasi Model:**
   - Menggunakan metrik seperti MAE dan RMSE.
   - Membandingkan hasil dengan baseline model.

5. **Submission:**
   - Menghasilkan file submission dengan format `Id` dan `HargaRumah`.

## Cara Menjalankan

1. Clone repository:
   ```bash
   git clone https://github.com/username/Prediksi_Harga_Rumah_Regresi.git
   cd Prediksi_Harga_Rumah_Regresi
