
# 🏦 Loan Approval Prediction Project

This project focuses on predicting whether a loan will be approved based on applicant details using both **classification** and **regression** techniques. It also demonstrates a full machine learning pipeline including **data cleaning**, **encoding**, **model building**, and **regularization**.

---

## 📊 Project Overview

- **Classification Task:** Predict if a loan will be approved (`Loan_Status`).
- **Regression Task:** Predict the loan amount (`LoanAmount`).
- **Techniques Used:**
  - Data Cleaning
  - Categorical Encoding (Label & One-Hot)
  - Train-Test Split
  - Classification Models (Logistic Regression, Random Forest)
  - Regression Models (Linear Regression, Ridge, Lasso)
  - Evaluation Metrics

---

## 🗂️ Dataset Info

The dataset includes details about loan applicants:

| Feature             | Description                                  |
|---------------------|----------------------------------------------|
| Loan_ID             | Unique identifier for the loan               |
| Gender              | Male / Female                                |
| Married             | Marital status                               |
| Dependents          | Number of dependents                         |
| Education           | Graduate / Not Graduate                      |
| Self_Employed       | Employment status                            |
| ApplicantIncome     | Income of the applicant                      |
| CoapplicantIncome   | Income of the co-applicant                   |
| LoanAmount          | Requested loan amount                        |
| Loan_Amount_Term    | Loan duration in months                      |
| Credit_History      | 1 if credit history is good, 0 otherwise     |
| Property_Area       | Urban / Semiurban / Rural                    |
| Loan_Status         | Y (Approved) / N (Rejected)                  |

---

## 🧪 Requirements

Install dependencies using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

---

## 🧠 ML Models Used

### 🔹 Classification
- Logistic Regression
- Random Forest Classifier

### 🔹 Regression
- Linear Regression
- Ridge Regression
- Lasso Regression

---

## 📈 Evaluation Metrics

### Classification:
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score

### Regression:
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🚀 How to Run

1. Clone the repo or download the files.
2. Ensure `loan_data.csv` is in the same directory.
3. Run `loan_prediction.py` or your notebook.
4. Results will be printed in the console.

---

## 🗃️ Output Example

```text
Accuracy: 0.84
Confusion Matrix:
[[20  5]
 [ 3 56]]
Classification Report:
              precision    recall  f1-score   support
           0       0.87      0.80      0.83        25
           1       0.92      0.95      0.93        59

RMSE (Loan Amount): 43.67
R² Score: 0.78
```

---

## 📌 Author

Made by Abdul Mannaan
Part of 100 Days of AI Challenge 🚀

---

## 📎 License

This project is open-source under the MIT License.
