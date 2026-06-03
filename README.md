# 🏠 House Price Prediction — Regression Modelling

> Predicting property prices using feature engineering and regularized regression.

![Python](https://img.shields.io/badge/Python-3.9+-0f2027?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Regression-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 🚩 Problem

Accurate house price estimation is critical for buyers, sellers, and real estate platforms. Simple models overfit noise; regularization helps generalize to unseen properties.

---

## ✅ Approach

Compared three regression models — Linear Regression as the baseline, then Ridge and Lasso as regularized alternatives — with careful feature engineering to improve prediction accuracy.

---

## 📊 Models compared

| Model | Key Property | Use Case |
|---|---|---|
| Linear Regression | No regularization (baseline) | Simple relationships |
| Ridge (L2) | Shrinks all coefficients | Multicollinear features |
| Lasso (L1) | Zeroes out weak features | Feature selection |

---

## ⚙️ Pipeline

```
Raw Housing Data
      ↓
Exploratory Data Analysis
      ↓
Data Cleaning + Missing Value Treatment
      ↓
Feature Engineering
      ↓
Model Training (Linear / Ridge / Lasso)
      ↓
Hyperparameter Tuning (alpha for Ridge/Lasso)
      ↓
Evaluation: RMSE · MAE · R² Score
```

---

## 🔍 Key techniques

- Log transformation on skewed price distribution
- Encoding categorical features (location, property type)
- Cross-validation to prevent overfitting
- Alpha tuning via GridSearchCV for Ridge and Lasso

---

## 🛠️ Tech stack

`Python` · `Scikit-learn` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

---

## 🚀 Run locally

```bash
git clone https://github.com/muneer-ahmad10/House-price-prediction.git
cd House-price-prediction
pip install -r requirements.txt
jupyter notebook
```

---

## 🔮 Planned improvements

- [ ] XGBoost and LightGBM comparison
- [ ] Geospatial feature engineering (distance to amenities)
- [ ] Streamlit deployment for live price prediction
- [ ] SHAP values for feature importance explainability

---

## 👨‍💻 Author

**Muneer Ahmad Dar** · [LinkedIn](https://linkedin.com/in/muneerahmad-826363267) · [GitHub](https://github.com/muneer-ahmad10)
