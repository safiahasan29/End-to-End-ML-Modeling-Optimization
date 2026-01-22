# End-to-End-ML-Modeling-Optimization
Built an ML pipeline for approval outcome prediction, covering EDA, preprocessing, imbalance handling, model tuning, and evaluation.

# EasyVisa Visa Approval Prediction – Machine Learning Project

## 📌 Project Overview
This project builds an end-to-end **machine learning classification solution** to predict whether a U.S. visa application should be **Certified** or **Denied**.

The goal is to help the Office of Foreign Labor Certification (OFLC) and EasyVisa **streamline visa processing**, reduce manual review effort, and identify the **key drivers that influence visa approval decisions**.

The solution follows a **clean, structured, production-style ML workflow** and is designed to be easy to explain in interviews and resumes.

---

## 🎯 Business Objective
- Facilitate faster visa approval decisions using data-driven insights
- Identify applicant and employer characteristics that increase approval probability
- Minimize costly **false approvals** by prioritizing **precision** as a key metric

---

## 🗂️ Project Structure (High-Level)
The notebook is organized into **8 clearly defined sections**, each representing a standard step in a real-world ML pipeline.

### **Section 1 – Imports & Configuration**
- Import required libraries (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost, Imbalanced-learn)
- Set random seeds for reproducibility
- Suppress warnings and define global settings

---

### **Section 2 – Data Loading & Initial Inspection**
- Load the EasyVisa dataset
- Inspect dataset shape, column names, and data types
- Perform basic sanity checks

---

### **Section 3 – Exploratory Data Analysis (EDA)**
- Univariate and bivariate analysis of key features
- Understand approval trends across:
  - Education level
  - Job experience
  - Wage levels
  - Employer size
  - Region of employment
- Identify class imbalance in visa outcomes

---

### **Section 4 – Data Preprocessing & Feature Engineering**
- Handle missing values
- Encode categorical variables
- Scale numerical features where required
- Prepare feature matrix (`X`) and target variable (`y`)

---

### **Section 5 – Handling Class Imbalance**
- Analyze imbalance between **Certified** vs **Denied** cases
- Apply:
  - Oversampling techniques
  - Undersampling techniques
- Compare model behavior under different sampling strategies

---

### **Section 6 – Model Training & Evaluation**
Multiple classification models are trained and evaluated, including:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost

Each model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

> **Precision is prioritized** due to the business impact of false approvals.

---

### **Section 7 – Hyperparameter Tuning & Model Selection**
- Perform hyperparameter tuning on top-performing models
- Compare tuned models on validation performance
- Select the **final best-performing model** based on business metrics

---

### **Section 8 – Final Model Evaluation & Business Insights**
- Evaluate final model on unseen test data
- Interpret feature importance
- Translate ML results into **actionable business insights**

Examples:
- Higher education and prior job experience significantly improve approval chances
- Higher prevailing wages correlate strongly with approvals
- Medium to large employers show better approval rates

---

## 📊 Key Results
- Final model achieved **high precision**, minimizing false approvals
- Model generalized well from validation to test data
- Feature importance provided clear, explainable decision drivers

---

## 🧠 Skills Demonstrated
- End-to-end ML pipeline design
- Handling imbalanced datasets
- Model comparison and selection
- Business-focused metric optimization
- Explainable ML for real-world decision-making

---

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab

---

## 🔗 How to Use This Repository
1. Clone the repository
2. Open the notebook in Jupyter or Colab
3. Run cells sequentially from top to bottom
4. Review outputs and business insights

---

📌 **This project is designed to demonstrate both strong ML fundamentals and real-world decision-making skills.**
