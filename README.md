## 📌 Project: Employee Attrition Prediction

### 👩‍💼 Overview:

This project aims to analyze and predict employee attrition using HR data. The dataset includes various features such as age, job role, satisfaction level, work-life balance, income, and more.

We followed a structured 3-part approach:

1. **Exploratory Data Analysis (EDA)**
2. **Visualizations & Insights**
3. **Attrition Prediction using Machine Learning (Logistic Regression & Random Forest)**

---

## 🗂 Dataset Source

[Kaggle - IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 📁 Project Files

* `WA_Fn-UseC_-HR-Employee-Attrition.csv` — Raw Dataset from Kaggle
* `Employee_Attrition_Prediction_Assignment.ipynb` — Jupyter Notebook with code for EDA + ML
* `README.md` — Project Summary

---

## 🔍 Part 1: EDA (Exploratory Data Analysis)

* Checked for null values and data types
* Performed basic descriptive statistics
* Explored categorical and numerical features
* Visualized distributions and outliers

---

## 📊 Part 2: Data Visualization

* Attrition by Department and Gender (Bar Charts)
* Age Distribution of Employees
* Monthly Income vs Job Role
* Job Satisfaction vs Performance Rating
* Correlation Heatmap

---

## 🤖 Part 3: Predictive Modeling

### 🔬 Goal: Predict whether an employee is likely to leave (Attrition = Yes/No)

* **Preprocessing**: Label Encoding, Scaling, Feature Selection
* **Models Used**:

  * Logistic Regression
  * Random Forest Classifier
* **Evaluation Metrics**:

  * Confusion Matrix
  * Classification Report (Precision, Recall, F1-score)
  * ROC Curve
* **Best Model**: Random Forest (AUC = 0.77)

---

## ✅ Results Summary

| Model               | Accuracy | AUC Score |
| ------------------- | -------- | --------- |
| Logistic Regression | \~82%    | 0.70      |
| Random Forest       | \~86%    | 0.77 ✅    |

---



That’s it — your project will be live on GitHub!
Let me know if you also want a `.pptx` or `.pdf` report for submission or presentation.
