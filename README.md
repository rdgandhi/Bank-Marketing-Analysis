# 🚀 **Bank Marketing Prediction & Feature Engineering**  

**Author**: *Rahul Gandhi*  


## 📌 **Project Overview**  
This project explores **predictive modeling and feature engineering** using the **Bank Marketing Dataset**. The objective is to identify **key factors influencing term deposit subscription** and compare **machine learning models** to improve predictive accuracy.  

By leveraging **data imputation, PCA, feature selection, and model evaluation**, this project provides **actionable insights** that can enhance banking marketing strategies.

---
### 🔍 **Dataset Information**  

The dataset used in this project is the **Bank Marketing Dataset**, which contains details about **direct marketing campaigns** conducted by a Portuguese banking institution. The goal of these campaigns was to **convince clients to subscribe to a term deposit** via phone calls.  

📌 **Source:** [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)  
📊 **Size:** **41,188 rows** × **21 columns**  
🎯 **Target Variable:** `y` (Did the client subscribe to a term deposit? → **yes/no**)  

#### 📁 **Dataset Features:**
The dataset includes **demographic, financial, and campaign-related attributes**, along with **economic indicators**:  

| **Feature Category** | **Columns** | **Description** |
|---------------------|------------|---------------|
| **Client Demographics** | `age`, `job`, `marital`, `education` | Client’s age, profession, marital status, and education level. |
| **Financial Status** | `default`, `housing`, `loan` | Whether the client has credit in default, a housing loan, or a personal loan. |
| **Campaign Information** | `contact`, `month`, `day_of_week`, `duration`, `campaign`, `pdays`, `previous`, `poutcome` | Contact method, last contact month/day, call duration, number of contacts, and previous campaign outcome. |
| **Economic Indicators** | `emp.var.rate`, `cons.price.idx`, `cons.conf.idx`, `euribor3m`, `nr.employed` | Employment variation rate, consumer price index, confidence index, Euribor 3-month rate, and number of employees. |
| **Target Variable** | `y` | Binary variable: **yes (1) / no (0)** (term deposit subscription). |

---
## 🔍 **Key Highlights**  
✅ **End-to-End Machine Learning Pipeline**
✅ **Iterative Imputation for Missing Categorical Data**  
✅ **Dimensionality Reduction using PCA**  
✅ **Comparing Models (Random Forest, Logistic Regression, Gradient Boosting.)**  
✅ **Handling Imbalanced Data (SMOTE, Class Weights)**  
✅ **Interactive Visualizations with Plotly**  

---

## 🏆 **Skills Demonstrated**  
💡 **Data Cleaning & Preprocessing** – Handling missing values, encoding categorical data, and standardization.  
📊 **Exploratory Data Analysis (EDA)** – Identifying trends, correlations, and key patterns.  
🤖 **Machine Learning & Model Evaluation** – Training, tuning, and comparing models.  
🎯 **Feature Engineering & Selection** – Improving model accuracy with optimized features.  
📉 **Principal Component Analysis (PCA)** – Reducing dimensionality while retaining performance.  
📈 **Model Performance Metrics** – ROC-AUC, F1-score

---

## 📂 **Project Structure**  
```
📦 Bank-Marketing-Prediction
 ┣ 📂 data
 ┃ ┣ 📜 bank-additional-full.csv  # Raw dataset
 ┃ ┣ 📜 bank-additional-names.txt  # Dataset Description
 ┃ ┗ 📜 banking_data_imputed.csv  # Imputed dataset
 ┃
 ┣ 📜 E2E_Pipeline.ipynb  # Code
 ┣ 📜 README.md  # Project documentation
 ┗ 📜 requirements.txt  # Dependencies (scikit-learn, pandas, etc.)
 
```

---

## 🔥 **How to Run the Project**
### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/rdgandhi/Bank-Marketing-Analysis.git
cd Bank-Marketing-Analysis
```

### 2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

---

## 📊 **Key Findings & Insights**  
1️⃣ **Age and Job Type Significantly Affect Subscription**  
- Older clients and professionals (management, self-employed) are more likely to subscribe.  

2️⃣ **March Shows the Highest Subscription Rate**  
- This could be linked to **end-of-financial-year tax planning** and **marketing efforts**.  

3️⃣ **Call Duration is a Strong Predictor**  
- Longer calls **increase** the probability of subscription.  

4️⃣ **Campaign Strategy Optimization Needed**  
- **Too many calls** reduce subscription chances (spam effect).  
- **Thursdays & Fridays** show slightly better success rates.  

5️⃣ **Feature Reduction with PCA Maintains Model Performance**  
- PCA **retains 95% variance** while reducing dimensionality, **improving computation time**.  

---

## 🤝 **Connect with Me**  
🔗 **LinkedIn**: [Rahul Gandhi](http://linkedin.com/in/rahuldgandhi)  


I’m open to **Data Science, Machine Learning, and AI roles**. If you’re looking for a **data-driven problem solver** who can turn raw data into actionable insights, let’s connect! 🚀  

---

### ⭐ **If you find this project useful, please consider giving it a star!** ⭐  
```bash
⭐ git star https://github.com/yourgithubusername/Bank-Marketing-Prediction
```

---

This `README.md` will make **senior professionals, recruiters, and hiring managers take notice** of your work. Let me know if you’d like me to tweak it further! 🚀😊
