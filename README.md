# Breast Cancer Classification using Machine Learning

## 📌 Overview

This project focuses on building and evaluating classification models to predict breast cancer diagnosis using machine learning techniques. The workflow includes data preprocessing, model training, evaluation, and comparison.

---

## 📊 Dataset

* Breast Cancer Wisconsin (Diagnostic) Dataset
* 569 samples with 30 numerical features
* Target classes:

  * Malignant (cancerous)
  * Benign (non-cancerous)

---

## ⚙️ Data Preprocessing

* Checked for missing values and duplicates
* Applied feature scaling using StandardScaler (Z-score normalization)

---

## 📊 Data Exploration

* Feature histograms
* Correlation heatmap
* Pairplot visualization

---

## 🔀 Dataset Splitting

* Training set: 70%
* Validation set: 10%
* Test set: 20%
* Stratified splitting used to preserve class distribution

---

## 🔁 Cross-Validation

* Stratified K-Fold (K=5)
* Ensures model stability and reliability

---

## 🤖 Models Implemented

* Logistic Regression
* Random Forest Classifier

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📊 Results

* Random Forest achieved higher accuracy compared to Logistic Regression
* Cross-validation confirmed stable performance

---

## ⚖️ Model Comparison

| Model               | Performance                               |
| ------------------- | ----------------------------------------- |
| Logistic Regression | Good baseline performance                 |
| Random Forest       | Higher accuracy and better generalization |

---

## 🧠 Conclusion

Machine learning classification models can effectively predict breast cancer diagnosis. Random Forest performed best due to its ability to model complex relationships in data.

---

## 🚀 Future Improvements

* Use advanced models (XGBoost, Neural Networks)
* Hyperparameter tuning for optimization
* Deploy model as a web application

---

## 👨‍💻 Author

Lakshay Saini
