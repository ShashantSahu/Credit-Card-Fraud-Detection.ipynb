# 💳 Credit Card Fraud Detection using Machine Learning

## 📖 Overview

Credit card fraud is a major issue in the financial industry, leading to significant losses every year. This project focuses on building a robust machine learning model to detect fraudulent transactions from highly imbalanced data.

The system analyzes transaction patterns and classifies them as **fraudulent** or **legitimate** using supervised learning algorithms.

---

## 🎯 Objectives

* Develop a reliable fraud detection model
* Handle class imbalance effectively
* Minimize false negatives (undetected fraud cases)
* Compare multiple machine learning algorithms

---

## 📊 Dataset

* Source: Kaggle (Public Dataset)
* Transactions: ~284,000
* Features: V1–V28 (anonymized), Time, Amount
* Target:

  * `0` → Legitimate Transaction
  * `1` → Fraudulent Transaction

---

## ⚙️ Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn
* **Visualization:** Matplotlib, Seaborn
* **Imbalance Handling:** SMOTE (Imbalanced-learn)
* **Environment:** Google Colab / Jupyter Notebook

---

## 🔍 Methodology

### 1. Data Preprocessing

* Checked for missing values
* Scaled `Time` and `Amount` using StandardScaler
* Separated features and target variable

### 2. Handling Class Imbalance

* Applied **SMOTE (Synthetic Minority Oversampling Technique)**
* Balanced fraud and normal transactions in training data

### 3. Model Training

* Logistic Regression
* Random Forest Classifier

### 4. Model Evaluation

* Confusion Matrix
* Precision, Recall, F1-score
* Accuracy

---

## 📈 Results

| Model               | Performance                         |
| ------------------- | ----------------------------------- |
| Logistic Regression | Good baseline performance           |
| Random Forest       | Best performance with higher recall |

* Achieved high accuracy and improved fraud detection capability
* Random Forest performed better in identifying fraudulent transactions

---

## 📊 Output Visualization

* Fraud vs Normal transaction distribution
* Confusion Matrix heatmap
* Model performance metrics

---

## 📂 Project Structure

```bash
Credit-Card-Fraud-Detection/
│── creditcard.csv
│── fraud_detection.py
│── README.md
│── requirements.txt
```

---

## 💡 Key Learnings

* Importance of handling imbalanced datasets
* Real-world challenges in fraud detection
* Trade-off between precision and recall
* Model evaluation beyond accuracy

---

## 🔮 Future Enhancements

* Deploy as a web application using Streamlit
* Implement advanced models (XGBoost, Neural Networks)
* Real-time fraud detection system
* Add ROC-AUC curve analysis

---

## 👨‍💻 Author

**Shashant Sahu**
B.Tech CSE (4th Semester)

