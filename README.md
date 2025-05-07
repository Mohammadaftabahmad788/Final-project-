# Elevate-Task-Final-Submission---

# 🧑‍💼 HR Employee Attrition Analysis

This project focuses on analyzing HR employee attrition data using Python libraries like Pandas, Seaborn, Matplotlib, and Scikit-learn. The objective is to visualize attrition trends and build a predictive model.

---

## 📂 Dataset

* **File Used:** `HR-Employee-Attrition.csv`
* The dataset includes employee details like Age, Department, Monthly Income, and Attrition status.
* Null values are checked to ensure clean data.

---

## 📊 Exploratory Data Analysis & Visualizations

### 1️⃣ Attrition by Department

A countplot shows how employee attrition varies across different departments. This helps identify which departments have higher attrition.

### 2️⃣ Attrition by Income Band

The `MonthlyIncome` column is divided into four income bands: Low, Medium, High, and Very High. A countplot shows how attrition is related to income level.

### 3️⃣ Attrition by Age Group

A bar chart is used to visualize attrition across different age groups. It helps understand whether younger or older employees are more likely to leave.

### 4️⃣ Pie Chart: Department-wise Attrition (Attrition = Yes)

A pie chart shows the percentage distribution of employees who left, grouped by their department. This offers a quick glance at which departments experience more attrition.

---

## 🤖 Machine Learning - Logistic Regression

### ✅ Model Building

* The data is split into training and testing sets using `train_test_split`.
* A Logistic Regression model is trained to predict employee attrition.
* Evaluation is done using metrics like Accuracy Score and Classification Report.

### 📈 ROC Curve & AUC Score

* The model’s performance is visualized using an ROC curve.
* AUC (Area Under Curve) value is calculated to evaluate prediction quality.
* A higher AUC means better model performance.

---

## 🛠 Tools & Technologies

* Python
* Pandas
* Seaborn
* Matplotlib


---

## 📌 Key Takeaways

* Visualizations clearly show trends in employee attrition based on department, income, and age.
* The model helps predict which employees are likely to leave.
* Useful for HR departments to take preventive measures and improve retention.

---
