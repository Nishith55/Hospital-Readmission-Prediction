# 🏥 Patient Readmission Prediction using Machine Learning

> Predicting 30-day hospital readmissions in diabetic patients to reduce healthcare costs and improve care quality.

---

## 📘 Problem Overview

Hospital readmissions, especially within 30 days, are a key metric for healthcare quality and operational cost. This project addresses the prediction of readmissions in **diabetic patients** using medical claims data, helping hospitals reduce unnecessary readmissions and improve resource utilization.

📉 In 2011 alone, over **$41 billion** was spent on diabetic patients who were readmitted within 30 days. Identifying risk factors and predicting such readmissions can directly reduce costs and improve patient outcomes.

---

## 🎯 Objective

- Identify the **key factors** that predict hospital readmission in diabetic patients.
- Develop a **predictive machine learning model** to determine the probability of patient readmission within 30 days.
- Enable hospitals to **optimize resources**, enhance **patient care**, and reduce **penalties under government healthcare programs**.

---

## ⚙️ Tech Stack

- 🐍 Python (Pandas, NumPy, Scikit-learn, LightGBM, Matplotlib, Seaborn)
- 📊 EDA & Data Visualization
- 🧠 Machine Learning: Logistic Regression, Random Forest, XGBoost, LGBM
- 📁 Jupyter Notebook

---

## 🗃️ Dataset

- Medical claims dataset focused on diabetic patients
- Contains both **numerical** and **categorical** data
- No missing/null values observed
- Balanced target variable (Readmitted vs Not Readmitted)

---

## 📌 Key Challenges & Insights

### 🔍 Data Observations

- No null values, aiding seamless preprocessing
- Weak correlation between most features
- Dominant values in some categorical features
- Some features exhibit low variability with respect to the target

### 📊 Model Performance

| Model               | Accuracy (%) |
|--------------------|--------------|
| Logistic Regression| ~55%         |
| Random Forest      | ~59%         |
| XGBoost            | ~60%         |
| ✅ **LightGBM**          | **61.49%** (Best) |

🔧 **Tried Techniques**:  
Outlier removal, one-hot encoding, label encoding, and feature elimination — still, only moderate improvements achieved.

---

## 🛠️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/readmission-prediction.git

# Navigate into the project directory
cd readmission-prediction

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
