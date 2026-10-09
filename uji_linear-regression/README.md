# 01 Linear Regression — Real Estate Valuation

Proyek pembelajaran Data Mining menggunakan Linear Regression untuk memprediksi harga properti per unit area.

## Dataset
Dataset asli dari UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/477/real+estate+valuation

Notebook mengunduh data melalui `ucimlrepo` ketika dijalankan, sehingga koneksi internet diperlukan saat memuat dataset.

## Menjalankan di laptop
```bash
python -m venv .venv
.venv\\Scripts\\activate
python -m pip install -r requirements.txt
jupyter notebook
```
Lalu buka `01_linear_regression_real_estate.ipynb` dan jalankan sel dari atas ke bawah.

## Cakupan
- Pengenalan dataset dan EDA
- Train-test split
- Linear Regression
- Evaluasi dengan MAE, RMSE, dan R²
- Visualisasi prediksi dan interpretasi koefisien

Dataset berasal dari Taiwan; targetnya menggunakan satuan 10.000 NTD per ping, bukan rupiah.
