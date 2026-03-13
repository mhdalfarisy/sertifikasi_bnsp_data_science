# Prediksi Harga Rumah dengan Machine Learning

## Deskripsi Proyek

Proyek ini merupakan implementasi Machine Learning untuk memprediksi
**harga rumah** menggunakan *California Housing Dataset*.\
Tujuan utama proyek ini adalah membangun model yang dapat memperkirakan
harga rumah secara lebih akurat berdasarkan karakteristik wilayah dan
kondisi ekonomi.

------------------------------------------------------------------------

# Dataset

Dataset yang digunakan adalah **California Housing Dataset** yang berisi
informasi geografis dan demografi wilayah perumahan.

### Fitur yang digunakan

-   longitude
-   latitude
-   housing_median_age
-   total_rooms
-   total_bedrooms
-   population
-   households
-   median_income
-   ocean_proximity

### Target Prediksi

    median_house_value

Target tersebut merepresentasikan **harga median rumah** pada suatu
wilayah di California.

------------------------------------------------------------------------

# Tahapan Proyek Data Science

Tahapan yang dilakukan dalam proyek ini meliputi:

1.  **Data Understanding**
    -   Memahami struktur dataset
    -   Mengidentifikasi tipe data dan variabel penting
2.  **Data Cleaning**
    -   Menangani missing values
    -   Menghapus atau memperbaiki data yang tidak valid
3.  **Exploratory Data Analysis (EDA)**
    -   Analisis distribusi data
    -   Analisis korelasi antar fitur
    -   Visualisasi hubungan antar variabel
4.  **Feature Engineering**
    -   Encoding variabel kategorikal (`ocean_proximity`)
    -   Normalisasi atau standarisasi fitur numerik
5.  **Model Training**
    -   Melatih beberapa algoritma machine learning
6.  **Model Evaluation**
    -   Mengukur performa model menggunakan metrik evaluasi
7.  **Model Selection**
    -   Memilih model dengan performa terbaik

------------------------------------------------------------------------

# Algoritma Machine Learning yang Digunakan

Model yang diuji dalam proyek ini:

-   Linear Regression
-   K-Nearest Neighbors Regressor
-   Decision Tree Regressor
-   Random Forest Regressor
-   XGBoost Regressor

------------------------------------------------------------------------

# Evaluasi Model

Model dievaluasi menggunakan metrik berikut:

-   **MAE (Mean Absolute Error)**
-   **MAPE (Mean Absolute Percentage Error)**

  Model               MAE         MAPE
  ------------------- ----------- -----------
  Linear Regression   42984       0.267
  KNN                 36684       0.211
  Decision Tree       42409       0.251
  Random Forest       30915       0.184
  XGBoost             **29607**   **0.177**

Dari hasil evaluasi tersebut, **XGBoost** memberikan performa terbaik
dibandingkan model lainnya.

------------------------------------------------------------------------

# Model Terbaik

Model terbaik setelah proses tuning adalah:

**XGBoost Regressor**

Hasil evaluasi:

-   **MAE ≈ 28,293 USD**
-   **MAPE ≈ 16%**

Artinya rata-rata selisih antara prediksi harga rumah dengan harga
sebenarnya sekitar **28 ribu USD**.

------------------------------------------------------------------------

# Insight Penting dari Data

Beberapa fitur yang paling berpengaruh terhadap harga rumah:

-   **median_income**
-   **ocean_proximity**

Hal ini menunjukkan bahwa **kondisi ekonomi wilayah dan kedekatan dengan
pantai** memiliki pengaruh besar terhadap nilai properti.

------------------------------------------------------------------------

# Manfaat Bisnis

Model prediksi ini dapat digunakan untuk:

-   Menentukan harga rumah secara lebih akurat
-   Menghindari overpricing atau underpricing
-   Membantu agen properti dalam menentukan harga jual
-   Memberikan rekomendasi harga berbasis data

------------------------------------------------------------------------

# Teknologi yang Digunakan

-   Python
-   Pandas
-   NumPy
-   Scikit-Learn
-   XGBoost
-   Matplotlib
-   Seaborn

------------------------------------------------------------------------

# Author

**Muhammad Alfarisy**\
Ujian Sertifikasi BNSP Data Science
