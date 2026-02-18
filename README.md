# credit-card-fraud-detection-ml
Credit Card Fraud Detection using Logistic Regression and Random Forest with class imbalance handling and performance evaluation.
# Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
This project builds a machine learning model to detect fraudulent credit card transactions.  
The dataset is highly imbalanced, making fraud detection a challenging classification problem.

The project focuses on:
- Handling class imbalance
- Model comparison
- Performance evaluation using proper metrics

---

## 📂 Dataset
Dataset used:
Credit Card Fraud Detection Dataset (Kaggle)

- 284,807 transactions
- 492 fraud cases
- Highly imbalanced dataset
- Features are anonymized (V1–V28), plus Time and Amount
- Target variable: Class (0 = Normal, 1 = Fraud)

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## 🔎 Steps Performed

1. Data Loading and Exploration
2. Class imbalance analysis
3. Feature scaling (Time & Amount)
4. Under-sampling to balance dataset
5. Train-test split
6. Model training:
   - Logistic Regression
   - Random Forest
7. Model evaluation:
   - Accuracy
   - Confusion Matrix
   - Precision
   - Recall
   - F1-Score

---

## 📊 Model Evaluation

Accuracy alone is not reliable for imbalanced datasets.

Key metrics considered:
- Precision → How many predicted frauds were actually fraud
- Recall → How many actual frauds were detected
- F1-Score → Balance between precision and recall

Random Forest performed better in detecting fraudulent transactions compared to Logistic Regression.

---

## 🚀 Future Improvements
- Apply SMOTE for better oversampling
- Add ROC-AUC curve
- Hyperparameter tuning
- Try advanced models (XGBoost, LightGBM)
- Deploy as a web app using Flask or Streamlit

---
