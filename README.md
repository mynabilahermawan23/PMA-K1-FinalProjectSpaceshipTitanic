# PMA-K1-FinalProjectSpaceshipTitanic
Final Project PMA - Spaceship Titanic Kaggle Competition | Machine Learning Classification

# 🚀 Final Project PMA — Spaceship Titanic

Final Project Mata Kuliah PMA  
Universitas Gadjah Mada | TA 2025

---

## 📌 Deskripsi

Proyek ini merupakan solusi untuk kompetisi Kaggle [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic/overview) — sebuah task klasifikasi biner untuk memprediksi apakah seorang penumpang ditransportasi ke dimensi lain atau tidak.

Seluruh pendekatan menggunakan **classical machine learning** (tanpa deep learning), dengan strategi **ensemble / OOF Weighted Blend** sebagai model final.

---

## 👥 Anggota Kelompok

| Nama | GitHub |
|------|--------|
| Aditya Iko | [@AdityaIKO](https://github.com/AdityaIKO) |
| Muhana Ilyas | [@muhanailyas](https://github.com/muhanailyas) |
| Nabila Hermawan | [@mynabilahermawan23](https://github.com/mynabilahermawan23) |
| Nur Huda | [@nurhudateguh](https://github.com/nurhudateguh) |

---

## 🤖 Metode yang Digunakan

Eksperimen membandingkan **5 model machine learning**:

| Model | Kelebihan |
|-------|-----------|
| LightGBM | Cepat dan kuat untuk data tabular |
| XGBoost | Stabil dan bagus untuk pola non-linear |
| HistGradientBoosting | Model boosting stabil dari scikit-learn |
| CatBoost | Kuat untuk fitur kategorikal |
| **Voting Classifier / OOF Weighted Blend** ✅ | Menggabungkan prediksi beberapa model agar lebih seimbang |

Model final yang dipilih adalah **Ensemble (OOF Weighted Blend)** — menggabungkan LightGBM, XGBoost, HistGradientBoosting, dan CatBoost.

---

## 📊 Hasil

| Submission | Skor Kaggle |
|------------|-------------|
| Submission sebelumnya | ~0.807 |
| **Model Final (Ensemble)** | **~0.809** ✅ |

---

## ⚙️ Fitur Engineering

Dataset memiliki banyak fitur kategorikal yang diproses, antara lain:
- `HomePlanet`, `Destination`, `Deck`, `Side`
- `AgeGroup`, `Deck_Side`, `Cryo_HasSpending`, `VIP_HasSpending`

---

## 🔗 Link

- [Kaggle Competition](https://www.kaggle.com/competitions/spaceship-titanic/overview)
