# House-price-prediction
This project focuses on predicting house prices using regression models such as Linear Regression, Ridge, and Lasso. It includes data preprocessing, feature engineering, and model evaluation to identify the best-performing model.

# 🏡 House Price Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict house prices using Machine Learning regression techniques.  
It covers the complete ML pipeline from data preprocessing to model evaluation.

---

## 🎯 Objective
To build and compare regression models to accurately predict house prices based on various features.

---

## 📊 Dataset
- Dataset: House Prices Dataset (Kaggle)
- Total Rows: 1460
- Features: 80+

---

## 🧠 Workflow

### 1. Data Preprocessing
- Handled missing values
- Removed irrelevant columns
- Treated outliers (GrLivArea)
- Applied log transformation to target variable

### 2. Exploratory Data Analysis (EDA)
- Identified important features using correlation
- Visualized relationships (GrLivArea vs SalePrice, etc.)
- Detected skewness in SalePrice

### 3. Feature Engineering
- One-hot encoding for categorical variables
- Feature selection based on correlation and importance

---

## 🤖 Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression

---

## 📈 Model Evaluation

Evaluation Metric:
- RMSE (Root Mean Squared Error)

| Model              | RMSE  |
|------------------|------|
| Linear Regression | 0.130 |
| Ridge Regression  | **0.124** ✅ |
| Lasso Regression  | 0.139 |

---

## 💡 Key Insights

- Ridge Regression performed best due to handling multicollinearity
- Lasso removed some useful features, reducing performance
- Log transformation improved model performance significantly
- Important features:
  - OverallQual
  - GrLivArea
  - GarageCars
  - TotalBsmtSF

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/muneer-ahmad10/house-price-prediction.git

# Navigate to project folder
cd house-price-prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
