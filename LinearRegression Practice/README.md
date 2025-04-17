# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview
This project uses Linear Regression to predict housing prices in Boston using numerical features like average number of rooms, % lower status population, and pupil-teacher ratio.

---

## 📂 Dataset
- **Name:** Boston Housing Dataset  
- **Source:** [Kaggle Boston Housing Dataset](https://www.kaggle.com/datasets/krupadharamshi/bostonhousing) *(Replace with actual link)*  
- **Features Used:**
  - `RM`: Average number of rooms per dwelling
  - `LSTAT`: % lower status of the population
  - `PTRATIO`: Pupil-teacher ratio by town
- **Target:**
  - `MEDV`: Median value of owner-occupied homes in $1000s

---

## 🧱 Technologies Used
- Python
- pandas, numpy
- scikit-learn
- seaborn, matplotlib

---

## 🚀 Steps Performed
1. Data Loading
2. Feature Selection – `RM`, `LSTAT`, `PTRATIO`
3. Train-Test Split
4. Model Training – Linear Regression
5. Evaluation – R² Score, MAE
6. Visualization – Actual vs Predicted, Residual Plot

---

## 📊 Model Results
- R2 Score = 0.6302528487272828
- MAE = 3.332538078324096
- Intercept = 14.588099261571081
- Coefficients = [ 4.93311836 -0.56712588 -0.86709475]
