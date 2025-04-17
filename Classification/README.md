# 🌸 IRIS FLOWER CLASSIFICATION USING LOGISTIC REGRESSION

## 📌 PROJECT OVERVIEW  
This project uses **Logistic Regression** to classify iris flowers into one of three species based on four flower measurements. It covers multiclass classification, model evaluation, and confusion matrix visualization.

## 📂 DATASET  
**NAME**: Iris Dataset (from `sklearn.datasets`)  
**FEATURES USED**:  
- **Sepal Length (cm)**  
- **Sepal Width (cm)**  
- **Petal Length (cm)**  
- **Petal Width (cm)**  
**TARGET**:  
- **Species**: One of `Setosa`, `Versicolor`, `Virginica`  

## 🧱 TECHNOLOGIES USED  
- Python  
- numpy, pandas  
- scikit-learn  
- seaborn, matplotlib  

## 🚀 STEPS PERFORMED  
- Dataset Loading from sklearn  
- Feature and Target Extraction  
- Train-Test Split  
- Model Training – Logistic Regression  
- Prediction on Test Set  
- Evaluation – Accuracy, Confusion Matrix, Classification Report  
- Visualization – Confusion Matrix Heatmap  

## 📊 MODEL OUTPUTS  
- **ACCURACY** = `0.8666666666666667` (example)  
- **CONFUSION MATRIX** =  
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
- **CLASSIFICATION REPORT**:
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30


## 🧠 NOTES  
- A perfect example of multiclass classification in ML.  
- Try experimenting with other classifiers like **SVM**, **KNN**, or **Decision Trees**.  
- Dataset is small and clean — great for beginners to explore model evaluation metrics.

