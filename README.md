Credit Card Fraud Detection (ML Project)
📌 Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. The dataset is highly imbalanced, with fraud cases representing only 0.172% of transactions. To address this, techniques like oversampling (SMOTE) and undersampling were applied to improve fraud detection accuracy.
Models such as Logistic Regression, Random Forest, and Gradient Boosting were trained and evaluated using precision, recall, F1-score, and AUC-PR.

📂 Project Structure
fraud-detection-ml/
│── CreditCard_FraudDetection.ipynb   # Main notebook
│── requirements.txt                  # Dependencies
│── LICENSE                           # License file
│── README.md                         # Project documentation
│── data/                             # Dataset folder

▶️ Run on Google Colab

Click the badge below to run the notebook in Google Colab:

📊 Dataset

Source: Transactions made by European cardholders in September 2013.

Size: 284,807 transactions (492 fraud cases).

Features:

V1 to V28: PCA-transformed features

Time: seconds since the first transaction

Amount: transaction amount

Class: 1 → Fraud, 0 → Genuine

⚙️ Installation

Clone the repo and install dependencies:

git clone: https://github.com/Ansh-38/fraud-detection-ml.git

cd fraud-detection-ml
pip install -r requirements.txt

🚀 Usage

Open the notebook:

jupyter notebook CreditCard_FraudDetection.ipynb


Or run directly in Google Colab using the badge above.

✅ Results

Best performance with Random Forest & Gradient Boosting.

Evaluation metrics used: Precision, Recall, F1-score, AUC-PR.

Focused on fraud recall to minimize false negatives.

🔮 Future Work

Deploy model using Flask/Django API.

Integrate with real-time transaction data streams.

Experiment with deep learning models (LSTM/Autoencoders).

📜 License

This project is licensed under the MIT License.
