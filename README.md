[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anshulskumbhare/Fraud-Detection-System/blob/main/Fraud_Detection_System.ipynb)
# 💳 Real-Time Fraud Detection System

## 🚀 Executive Summary
This project implements a high-performance Fraud Detection model using **LightGBM**. By analyzing over 500,000 anonymized transactions, the system identifies fraudulent patterns with high sensitivity, focusing on minimizing financial loss while maintaining a smooth customer experience.

### 🛠️ Key Technical Highlights
* **Memory Optimization:** Reduced dataset memory footprint by **70%** (from 4GB to ~1GB) using data-type downcasting.
* **Imbalanced Learning:** Utilized **Scale-Pos-Weight** and **PR-Curve Tuning** to handle the 3.5% fraud minority class.
* **Advanced Evaluation:** Achieved **96% Recall** for fraud cases by optimizing the decision threshold.
* **Tech Stack:** Python, LightGBM, Scikit-Learn, Pandas, Joblib.

## 📊 Business Impact
* **Recall:** 96% (Caught nearly all fraudulent attempts).
* **False Positive Reduction:** Balanced threshold to prevent unnecessary customer card declines.
* **Production Ready:** Includes a serialized `.pkl` model and feature mapping for API deployment.

## 📂 Project Structure
* `Fraud_Detection_System.ipynb`: Full end-to-end pipeline (EDA to Evaluation).
* `lgb_fraud_model.pkl`: The trained production model.
* `model_features.txt`: Required feature list for model inference.
