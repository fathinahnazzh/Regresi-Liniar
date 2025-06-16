# Regresi-Liniar

## 📦 Dataset

- Dataset: Boston Housing
- Sumber: Package `MASS`
- Jumlah observasi: 506
- Jumlah variabel: 14
- Variabel target: `medv` (median value of owner-occupied homes)

## 🔧 Tools dan Teknologi

- Bahasa Pemrograman: **R**
- Library yang digunakan:
  - `MASS` (untuk dataset)
  - `ggplot2` (visualisasi)
  - `dplyr` (manipulasi data)
  - `corrplot` (korelasi heat map)
  - `caret` (machine learning)

---

## 📊 Langkah Analisis

1. Load dan eksplorasi data
2. Analisis korelasi antar variabel
3. Pembuatan model regresi linier
4. Evaluasi model menggunakan RMSE dan R²
5. Mengecek residual plot

---

## 🔍 Hasil Singkat

- Model regresi linier mampu memprediksi harga rumah dengan cukup baik diliat dari R² 0.76 dengan variabel prediktor `nox`, `rm`, `dis`, `rad`, `ptratio`, `black`, `lstat` yang paling signifikan (berpengaruh) terhadap hasil `medv`


