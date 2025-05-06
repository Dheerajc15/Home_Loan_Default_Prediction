# Home Loan Default Prediction
This project aims to build a robust binary classification model to predict loan defaults using advanced deep learning techniques and a custom weighted focal loss to address class imbalance.

## 🔍 Problem Statement
In financial lending, predicting whether an applicant will default is critical. Traditional models may underperform when handling highly imbalanced datasets where defaulters are rare.

## 🛠️ Techniques Used
- Exploratory Data Analysis (EDA)
- Advanced Imputation for Missing Data
- Feature Engineering & Feature Selection
- Hybrid Resampling (SMOTE + Tomek Links)
- Deep Neural Network with:
  - `Swish` activation functions
  - Batch Normalization & Dropout layers
  - Weighted Focal Loss to handle imbalance

## 📈 Evaluation Metrics
- ROC-AUC Score
- Classification Report (Precision, Recall, F1)
- Confusion Matrix

## 📌 Note
This project was originally developed in Google Colab and utilizes TensorFlow and Scikit-learn.
