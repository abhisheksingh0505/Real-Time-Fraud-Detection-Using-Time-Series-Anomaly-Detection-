
# 🚨 Real-Time Fraud Detection Using Time Series Anomaly Detection

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/ML-Fraud_Detection-orange)]()
[![Deep Learning](https://img.shields.io/badge/DL-LSTM%2CAutoencoder-brightgreen)]()

## 📘 Abstract

As the world goes digital, online transactions are more susceptible to fraud. Traditional rule-based systems struggle to detect sophisticated fraud patterns. This project introduces a **real-time fraud detection system** using machine learning and deep learning techniques such as:

- ✅ **Random Forest Classifier**
- 📈 **ARIMA for time-series forecasting**
- 🌲 **Isolation Forest for unsupervised anomaly detection**
- 🔁 **LSTM for sequential pattern recognition**
- 🤖 **Autoencoders for deep anomaly detection**

---

## 📊 Dataset Details

- **Source**: Real transaction data
- **Features**: 
  - Transaction Type
  - Amount
  - Pre/Post Balance
  - Fraud Flags (isFraud, isFlaggedFraud)
- **Preprocessing**:
  - Missing Value Imputation
  - Label Encoding
  - Feature Scaling (StandardScaler / MinMaxScaler)
  - Time-Series Generation with Datetime Index

---

## 🔍 Methodology

### 🧼 Data Preparation
- Clean and preprocess the dataset
- Encode categorical variables
- Normalize numerical features
- Handle class imbalance

### ⚙️ Model Implementation
| Model | Type | Purpose |
|-------|------|---------|
| 🎯 Random Forest | Supervised | Classifies fraudulent transactions |
| 📊 ARIMA | Time-Series | Predicts anomalies over time |
| 🌲 Isolation Forest | Unsupervised | Detects statistical outliers |
| 🔁 LSTM | Deep Learning | Identifies sequential patterns |
| 🤖 Autoencoders | Deep Learning | Flags anomalies by reconstruction error |

### 🚀 Real-Time Deployment
- Integrated into streaming pipelines
- Processes transactions with low latency
- Adaptive to evolving patterns

---

## 📈 Results

| Model         | Accuracy | Recall | FPR  | Latency |
|---------------|----------|--------|------|---------|
| 🔁 LSTM        | **98.5%** | 95.2%  | 2.1% | 0.02s   |
| 🤖 Autoencoder | 97.8%    | 93.7%  | Low  | 0.03s   |
| 📊 ARIMA       | 96.3%    | Moderate | Low | 0.04s   |

> **🏆 Best Performer**: LSTM (High accuracy + Real-time performance)

---

## 📚 Literature Support

- Lee et al. – Time Series Anomaly Detection using LSTM
- Ren et al. – Microsoft’s Anomaly Detection service
- Chen et al. – Sensor-Drift-Aware Detection
- Aggarwal et al. – LSTM on US Export-Import data

---

## 🛠 Tools & Technologies

- **Python** (Pandas, NumPy, Sklearn, TensorFlow, Keras)
- **Time-Series Analysis** (ARIMA, Isolation Forest)
- **Deep Learning** (LSTM, Autoencoders)
- **Deployment** (Streaming pipelines for real-time detection)

---

## 🧠 Future Enhancements

- Introduce **Transformer models** for long-term pattern learning
- Automate **hyperparameter tuning**
- Expand dataset diversity to enhance generalization

---

## 👨‍💻 Authors

- **Omkar Singh** – Coordinator, Data Science
- **Swati Singh** – Assistant Professor
- **Abhishek Singh** – PG Student, Data Science
- **Vishal Pandey** – PG Student, Data Science

📫 Contact: `omkarsingh@tcsc.edu.in` | `swatisingh2466@gmail.com` | `singh0505330@gmail.com` | `vishalpandey0266@gmail.com`

---



