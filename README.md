# Credit Risk Loan: A Machine Learning Model for Credit Risk Classification

## Deskripsi Proyek
Proyek ini merupakan bagian dari Project Based Internship di **id/x partners**. Tujuan utama proyek ini adalah membangun model machine learning untuk mengklasifikasi risiko kredit guna membantu bank mengurangi tingkat kredit macet (bad loan) sebesar 12% dan meningkatkan akurasi keputusan peminjaman.

## Detail Proyek
- **Nama File**: Final Project Muhammad Ravil.pdf
- **Tujuan**: Mengembangkan model prediksi risiko kredit untuk meningkatkan validitas keputusan peminjaman dan stabilitas keuangan bank.

## Isi Utama
- **Business Understanding**: Mengidentifikasi tantangan bank dalam menilai risiko kredit dengan rasio kredit macet mencapai 12%, yang berdampak pada stabilitas keuangan.
- **Data Understanding (EDA)**: Dataset berisi 486,285 baris dan 74 kolom dengan tipe data int64, float64, dan object. Terdapat ketidakseimbangan kelas: high risk (11.9%) dan low risk (88.1%).
- **Data Preprocessing**: 
  - Membersihkan data null (17 kolom kosong, 40 kolom dengan nilai null).
  - Encoding fitur kategorikal (low-risk: 1, high-risk: 0).
  - Scaling fitur numerik menggunakan MinMaxScaler.
  - Balancing data menjadi rasio 50:50 menggunakan SMOTE.
- **Modeling**: Random Forest menjadi model terbaik dengan F1-test 0.963 setelah tuning hyperparameter (contoh: n_estimators, max_depth, max_features)

