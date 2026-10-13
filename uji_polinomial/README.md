# Coursera ML – Course 2, Modul 3

Data split dan polynomial regression.

## Isi
- `polynomial_regression_data_split.ipynb` – notebook belajar (Bahasa Indonesia)
- `data/auto_mpg.csv` – dataset Auto MPG (398 baris, UCI Machine Learning Repository, salinan dari seaborn-data)

## Cara pakai
```bash
pip install -r requirements.txt
jupyter notebook polynomial_regression_data_split.ipynb
```

## Konsep
- `train_test_split` – pisah data latihan dan ujian
- `PolynomialFeatures` – tambah fitur x², x³, ...
- Underfitting vs overfitting – bandingkan RMSE train dan test
- `cross_val_score` – evaluasi lebih stabil
