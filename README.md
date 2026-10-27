# Pertemuan 10 - Praktik Regresi Linear Multivariabel

Repo ini berisi praktik coding regresi linear dengan dua prediktor untuk mata kuliah **Pengantar Sains Data**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satriarmdhn/Pengantar_Sains_Data_Pertemuan10/blob/main/Regresi_Linear_Multivariabel.ipynb)

## File

- [**Regresi_Linear_Multivariabel.ipynb**](Regresi_Linear_Multivariabel.ipynb): notebook praktik (kode dan output)

## Ringkasan Praktik

Data sintetis dengan 1000 observasi dan dua prediktor:

```
Y = 5 + 3.5 * X1 - 2 * X2 + noise
```

Alur kerja di notebook:

1. Membuat data sintetis (`seed 2007`)
2. Membagi data latih dan data uji (80:20)
3. Melatih model `LinearRegression` dengan dua prediktor
4. Evaluasi dengan MSE dan R²
5. Visualisasi nilai aktual vs prediksi

## Hasil

Persamaan model hasil fitting:

```
Y = 5.6834 + 3.5031 * X1 - 1.9943 * X2
```

| Metrik | Nilai |
| ------ | ----- |
| MSE    | 0.1999 |
| R²     | 0.9987 |

Koefisien hasil model hampir sama dengan rumus asli. Ini wajar karena data dibuat sendiri dengan noise kecil.

## Cara Menjalankan

1. Klik tombol **Open In Colab** di atas.
2. Pilih **Runtime > Run all**.

Library yang dipakai: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.

## Author

**Satria Ramadhani (20264920010)** / Statistika - Data Science

Matana University

### Terima kasih
