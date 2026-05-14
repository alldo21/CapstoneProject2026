# Capstone Project 2026 - Cardiovascular Disease Analysis

Repository ini berisi proyek akhir (Capstone Project) mengenai analisis data penyakit kardiovaskular, mencakup proses pengolahan data, pemodelan machine learning, hingga visualisasi dashboard.

## 📂 Struktur Proyek

*   **dataset/**: Folder yang berisi seluruh kumpulan data yang digunakan dalam proyek:
    *   `cardio_train (data mentah).csv`: Dataset asli sebelum diproses.
    *   `cardio_processed (before scale).csv`: Data yang telah melalui tahap pembersihan.
    *   `cardio_train_scaled (latih model).csv` & `cardio_test_scaled (uji model).csv`: Data yang sudah siap digunakan untuk proses machine learning.
    *   `cardio_clean (dashboard).csv`: Data final yang dioptimalkan untuk visualisasi dashboard.
    *   `lifestyle.csv`, `age_group.csv`, `correlation.csv`: File pendukung untuk analisis spesifik.
*   **Data Dictionary Cardio.xlsx**: Dokumen penjelasan mengenai keterangan kolom dan variabel dalam dataset.
*   **Project_Capstone_Fixed_(ready_to_model).ipynb**: Notebook utama yang berisi seluruh alur kerja mulai dari Exploratory Data Analysis (EDA) hingga persiapan model.
*   **url-dashboard.txt**: Berisi tautan/link menuju dashboard interaktif Streamlit yang telah di-deploy.

## Cara Menjalankan

1. **Analisis Notebook**:
   Buka file `.ipynb` menggunakan Google Colab atau Jupyter Notebook untuk melihat proses analisis data secara mendalam.

2. **Visualisasi Dashboard**:
   Buka file `url-dashboard.txt` dan akses link yang tertera di dalamnya untuk melihat ringkasan temuan dalam bentuk visual.

## Teknologi yang Digunakan

*   **Bahasa Pemrograman**: Python
*   **Library**: Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn
*   **Dashboard**: Streamlit

---
