# 📊 Customer Churn Prediction

A Machine Learning project that predicts whether a telecom customer is likely to churn (leave the service) based on customer demographics, account information, and service usage patterns.

---

## 🚀 Project Overview

Customer retention is a critical challenge for telecom companies. Acquiring new customers is often more expensive than retaining existing ones. This project leverages Machine Learning techniques to identify customers who are at risk of churning, enabling businesses to take proactive retention measures.

---

## 🎯 Objective

Build a classification model that predicts customer churn using historical customer data and identify the key factors influencing customer retention.

---

## 📂 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

### Features Included

* Gender
* Senior Citizen Status
* Partner & Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges

### Target Variable

| Value | Meaning                     |
| ----- | --------------------------- |
| Yes   | Customer is likely to churn |
| No    | Customer is likely to stay  |

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing

* Removed irrelevant columns (e.g., Customer ID)
* Converted `TotalCharges` to numeric format
* Handled missing values
* Encoded categorical variables
* Prepared data for model training

### 2️⃣ Exploratory Data Analysis (EDA)

Performed visual analysis to understand:

* Customer churn distribution
* Impact of monthly charges on churn
* Contract type vs churn behavior
* Feature relationships and correlations

### 3️⃣ Model Development

Implemented and compared:

* Logistic Regression
* Random Forest Classifier

### 4️⃣ Model Evaluation

Models were evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## 📈 Results

| Model               | Accuracy   |
| ------------------- | ---------- |
| Logistic Regression | **81.62%** |
| Random Forest       | **79.77%** |

✅ **Best Performing Model:** Logistic Regression

---

## 🔍 Key Insights

* Customers with **month-to-month contracts** are more likely to churn.
* Customers with **higher monthly charges** show a higher churn tendency.
* Customers with **longer tenure** are generally more loyal.
* Important features influencing churn include:

  * Tenure
  * Monthly Charges
  * Total Charges
  * Contract Type

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook / Google Colab

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── customer_churn_model.pkl
├── README.md
└── dataset.csv
```

---

## 🔮 Future Enhancements

* Hyperparameter tuning
* XGBoost implementation
* Streamlit web application deployment
* Real-time churn prediction dashboard
* Feature importance visualization

---

## 👨‍💻 Author

**R. Kaushik**

AI/ML Internship Project

---

⭐ If you found this project useful, consider giving it a star on GitHub!
