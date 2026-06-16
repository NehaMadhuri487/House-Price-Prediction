# House-Price-Prediction
# House Price Prediction

**Intern ID:** CITS1931  
**Full Name:** Boddu Neha Madhuri  
**Project Name:** House Price Prediction  
**Duration:** 6 Weeks  
**Project Scope:** Predict house prices using machine learning models on structured housing data. The project involves data cleaning, exploratory data analysis (EDA), feature selection, model training, evaluation, and deployment of the best-performing model.

---

## 📌 Project Overview
This project aims to build a machine learning model that can accurately predict house prices based on various features such as location, size, age, and condition.  

The workflow includes:
1. **Data Cleaning** – handling missing values, duplicates, outliers, and encoding categorical features.  
2. **Exploratory Data Analysis (EDA)** – visualizing distributions, correlations, and feature relationships.  
3. **Feature Selection** – selecting the most relevant predictors for house price.  
4. **Train/Test Split** – splitting the dataset into training and testing sets.  
5. **Model Training & Evaluation** – experimenting with multiple regression models.  
6. **Model Selection** – choosing the best-performing model based on metrics.  
7. **Prediction** – using the final model to predict new house prices.  

---

## 🛠️ Models Tested
- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  

---

## 📊 Results
| Model                | R² Score | RMSE     |
|-----------------------|----------|----------|
| Linear Regression     | 0.70     | 146,772  |
| Random Forest         | 0.87     | 94,937   |
| Gradient Boosting     | 0.88     | 92,631   |
| **XGBoost (Final)**   | **0.90** | **83,820** |

---

## ✅ Final Model
The **XGBoost Regressor** was selected as the final model because it achieved the highest R² score and lowest RMSE, meaning it explains ~90% of the variance in house prices and has the smallest average prediction error.  

---

## 🚀 How to Use
## Clone Repository

```bash
git clone https://github.com/NehaMadhuri487/House-Price-Prediction.git
```

## Navigate to Project Folder

```bash
cd House-Price-Prediction
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Project

```bash
streamlit run app.py
```
