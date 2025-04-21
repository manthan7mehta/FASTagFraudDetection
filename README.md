# 🚗 FASTag Fraud Detection

A machine learning project focused on detecting fraudulent FASTag transactions by analyzing behavioral patterns and transaction anomalies. This solution applies multiple classification algorithms to identify suspicious activities and improve the security of toll payments.

---

## 🔍 Project Overview

FASTag is a system used in India for automatic toll payments via RFID. While it offers convenience, it also opens avenues for misuse and fraud. This project leverages data analysis and machine learning to identify such fraudulent transactions.

---

### Objectives:
- Analyze transaction data for patterns indicating fraud.
- Preprocess and visualize the dataset.
- Build and evaluate ML models for fraud detection.
- Identify the most accurate model.

---

## 📁 Repository Contents

- `FASTagFraudDetection.ipynb` – Main notebook with all EDA, preprocessing, model training, and evaluation.
- `README.md` – This documentation file.

---

## 📊 Features

- Exploratory Data Analysis (EDA) with rich visualizations.
- Data cleaning and feature engineering.
- Model training using:
  - Logistic Regression
  - Decision Tree (🏆 Best: 99% accuracy)
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- Evaluation using classification reports and confusion matrices.

---

## 💻 Tech Stack

- **Language**: Python 3.12.4  
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Jupyter Notebook

---

## 📌 Dataset
The dataset contains transactional details such as:

Vehicle type
Transaction amount
Timestamp
Tag ID and location ID
Fraud label

---

## 📈 Results
Decision Tree achieved the best results with 99% accuracy.
The model accurately classified fraudulent vs non-fraudulent transactions.
Feature importance analysis revealed key indicators of fraud.

---

## 🧑‍💻 Author
**Manthan Mehta**  
- [LinkedIn](https://www.linkedin.com/in/manthan7mehta)  
- [GitHub](https://github.com/manthan7mehta)

---

## 🙌 Acknowledgements
Built using open-source Python libraries.
Inspired by real-world use cases of RFID-based toll systems.

---
