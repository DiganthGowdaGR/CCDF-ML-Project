# Credit Card Fraud Detection 💳🔍

## 📌 Overview
This project detects **fraudulent credit card transactions** using **Logistic Regression**.  
It is designed to help financial institutions prevent fraud and reduce financial losses.  
A **Streamlit web application** is also provided, allowing users to upload their own dataset and check for fraud in real-time.

## 📂 Dataset
- **Source:** [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download)
- **Size:** 31 columns, 284,807 rows  
- **Target Column:** `Class`  
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction  

## ⚙️ Data Preprocessing
- Separated legitimate & fraudulent transactions
- Handled class imbalance by **undersampling** legitimate transactions
- Split data into **train & test sets**
- Normalized feature values for better model performance

## 🤖 Model
- **Algorithm:** Logistic Regression (Scikit-learn)
- **Test Accuracy:** `93.29%`
- Model predicts whether a given transaction is legitimate or fraudulent

## 🖥️ Streamlit App
- Upload CSV dataset
- View training & testing accuracy
- Input transaction features and get predictions instantly

## 📊 Evaluation
| Metric      | Value |
|-------------|-------|
| Test Accuracy | 0.9329 |

## 📌 How to Run Locally
1. Clone the repository  
   ```bash
   git clone https://github.com/DiganthGowdaGR/CreditCardFraudDetection.git
   cd CreditCardFraudDetection
