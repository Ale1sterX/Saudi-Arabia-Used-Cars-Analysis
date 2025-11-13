# Saudi Arabia Used Car Price Prediction

A machine learning project that predicts **used car prices** in Saudi Arabia using various features such as brand, model year, mileage, and engine size.  
The model is trained using **XGBoost** and includes exploratory data analysis (EDA), preprocessing, hyperparameter tuning, and model interpretability with SHAP.

---

## 📊 Business Understanding

The Saudi Arabian used car market has rapidly grown, and understanding price patterns can help both **buyers** and **sellers** make informed decisions.  
This project aims to provide an interpretable model that estimates fair prices for used vehicles.

**Objectives:**
- Identify key factors influencing car prices  
- Build a predictive model with strong generalization performance  
- Explain model predictions using SHAP values

---

## ⚙️ Installation

### 1. Requirements
- **Python 3.8+**
- **Jupyter Notebook**
- Required packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `xgboost`, `scikit-learn`, `shap`

### 2. Clone Repository

```bash
git clone https://github.com/<your-username>/used-car-price-prediction.git
cd used-car-price-prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Notebook

```bash
jupyter notebook "Saudi Arabia Used Cars Price Prediction.ipynb"
```

---

## 🧱 Project Structure

```
📁 used-car-price-prediction
├── 📘 Saudi Arabia Used Cars Price Prediction.ipynb
├── 📄 data_saudi_used_cars.csv
├── 📄 requirements.txt
└── 📄 README.md
```

---

## 📈 Features
- Data preprocessing and feature engineering  
- Model training with **XGBoost**  
- Hyperparameter tuning with **RandomizedSearchCV**  
- Evaluation with **RMSE** and **R² Score**  
- Model interpretability using **SHAP**  

---

## 🧠 Insights
- Car **brand**, **model year**, and **mileage** are major predictors of price.  
- Newer cars and premium brands (e.g., BMW, Mercedes) show higher resale value.  
- SHAP analysis highlights feature contributions per prediction.  

---

## 👤 Author
**Brian Samuel Matthew**  
Data Science Capstone Project  
Jakarta, Indonesia — 2025  

📧 [your-email@example.com]  
🔗 [LinkedIn / GitHub profile if desired]

---
