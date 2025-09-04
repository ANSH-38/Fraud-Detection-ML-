# 💳 Credit Card Fraud Detection (ML Project)

## 📌 Project Overview
This project detects fraudulent credit card transactions using Machine Learning.  
The dataset is highly imbalanced, so techniques like **SMOTE oversampling** were applied.  
Models trained: Logistic Regression & Random Forest.  
Best performing model: **Random Forest**.

---

## 🚀 Features
- Preprocessing & normalization of transaction data
- Handling class imbalance using **SMOTE**
- Model training (LogReg, Random Forest)
- Evaluation with Precision, Recall, F1-Score
- Confusion Matrix & Precision-Recall Curve plots
- Saved trained model for re-use (`best_fraud_model.pkl`)

---

## 📊 Dataset
- Source: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- 284,807 transactions, 492 frauds (0.172% of all transactions)
- Features: PCA transformed components (V1–V28), Time, Amount
- Target: `Class` (1 = Fraud, 0 = Legitimate)

---

## ⚙️ Installation & Usage

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/Fraud-Detection-ML.git
cd Fraud-Detection-ML
