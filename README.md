# Capstone Project 2026 - Cardiovascular Disease Analysis

Projek ini merupakan **Capstone Project** yang bertujuan untuk menganalisis data penyakit kardiovaskular, mencakup proses pengolahan data, pemodelan machine learning, hingga visualisasi dashboard.

## 📂 Struktur Proyek

```text
├── dataset/
│   ├── data for AI/
│   │   ├── cardio_processed_cleaned.csv              # Data hasil preprocessing siap untuk modeling AI
│   │   ├── cardio_test_scaled.csv                    # Dataset pengujian (test set) yang telah di-scaling
│   │   └── cardio_train_scaled.csv                   # Dataset pelatihan (train set) yang telah di-scaling
│   ├── age_group.csv                                 # Data segmentasi berdasarkan kelompok usia
│   ├── cardio_clean (dashboard).csv                  # Dataset bersih khusus untuk visualisasi dashboard
│   ├── cardio_train (data mentah).csv                # Dataset mentah awal sebelum proses cleaning
│   ├── correlation.csv                               # Matriks korelasi antar fitur/variabel
│   └── lifestyle.csv                                 # Data terkait faktor gaya hidup (merokok, alkohol, fisik)
├── Data Dictionary Cardio.xlsx                       # Kamus data yang menjelaskan arti dari setiap kolom/fitur
├── LAPORAN KOMPREHENSIF DS.pdf                       # Dokumen laporan akhir komprehensif yang menyajikan latar belakang, metodologi, hasil analisis, serta kesimpulan proyek Data Science ini.
├── Project_Capstone_Fixed_(ready_to_model)(1).ipnyb  # Notebook utama analisis data dan pengembangan model machine learning
├── README.md                                         # Dokumentasi proyek
├── dashboard.py                                      # Source code untuk aplikasi dashboard interaktif (Streamlit)
└── url-dashboard.txt                                 # Tautan resmi menuju dashboard yang telah di-deploy
```

## Cara Menjalankan

1. **Analisis Notebook**:
   Buka file `.ipynb` menggunakan Google Colab atau Jupyter Notebook untuk melihat proses analisis data secara mendalam.

2. **Visualisasi Dashboard**:
   Buka file `url-dashboard.txt` dan akses link yang tertera di dalamnya untuk melihat ringkasan temuan dalam bentuk visual.
   Atau buka dalam file `dahsboard.py` dengan pip install -r requirements.txt & streamlit run dashboard.py

## Teknologi yang Digunakan

*   **Bahasa Pemrograman**: Python
*   **Library**: Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn
*   **Dashboard**: Streamlit

---
