# 💓 Heart Disease Analysis in India — Power BI Dashboard

## 📁 Project Overview
The primary goal is to assist health insurance firms in making data-backed decisions regarding premium structuring, risk profiling, and regional segmentation of heart disease insurance policies.
This Business Intelligence (BI) project analyzes heart disease patterns across India using a dataset originally sourced from Kaggle. To enable richer analysis, synthetic variables such as `City`, `Work Type`, and `Date of Diagnosis` were added.

🔍 **Objective**: Empower health insurance companies to make informed, data-backed decisions for:
- 💰 Premium structuring  
- 📊 Risk profiling  
- 🌍 City-wise segmentation of heart disease insurance policies

---

## 🧪 Dataset Description

The dataset includes:

- **Demographics**: Age, Gender, City, Work Type  
- **Health Indicators**: BMI, Blood Pressure, Diabetes Status, Stress Level, Sleep Hours  
- **Lifestyle Factors**: Smoking, Alcohol Consumption, Exercise Frequency  
- **Medical Markers**: C-Reactive Protein (CRP), Homocysteine Level  
- **Temporal Data**: Date of Diagnosis (Month, Year)

---

## 🧼 Data Preprocessing & Normalization

To ensure quality insights, the following preprocessing steps were conducted:

- 🔧 **Missing Value Handling**: Cleaned or imputed where applicable  
- 📏 **Normalization**: Min-Max scaling of continuous variables (e.g., BMI, Age, CRP, Homocysteine)  
- 🧠 **Categorical Encoding**: Applied label encoding for gender, city, work type, etc.  
- 🏙️ **Synthetic Variable Addition**:  
  - `City` — to enable regional insights  
  - `Work Type` — to explore occupational health patterns  
  - `Date of Diagnosis` — for time-series analysis  

---

## 🎯 Project Objectives

- Correlate **age** with heart disease prevalence  
- Analyze how **BMI** influences blood pressure and diabetes  
- Evaluate the **impact of exercise** on cardiovascular health  
- Explore the effects of **smoking and alcohol** on heart disease  
- Assess how **stress** and **sleep** contribute to heart health  
- Visualize **city-level** and **temporal trends** in diagnosis patterns  

---

## 📊 Tools & Technologies

- 💻 **Power BI** – for interactive dashboard creation  
- 📊 **Excel** – for normalization, encoding, and data preparation  
- 🐍 *(Optional)* Python – for data validation and preprocessing  

---

## 🧠 Key Insights for Health Insurers

### 🧓 Age-Based Risk
- Risk increases significantly **after age 40**, and peaks **post 60**
- Suggests preventive screening and adjusted premiums for senior applicants  

### ⚖️ BMI & Chronic Conditions
- Individuals with **BMI ≥ 25** show increased rates of **hypertension** and **diabetes**
- Incentives for healthy BMI could reduce claims burden  

### 🚬 Lifestyle Behaviors
- **Smoking + Alcohol** users are at the highest risk
- Lifestyle-based rating models recommended  

### 😴 Stress & Sleep
- **High stress** and **low sleep** are associated with elevated heart risk markers (CRP, Homocysteine)  
- Targeted wellness programs can reduce claims  

### 🏙️ City-Wise Segmentation
- **Metro cities** show higher prevalence — likely due to pollution and lifestyle  
- Policies can be tailored by urban/rural location  
- **Winter months** show upticks — seasonal factors may contribute  

---

## 📈 Output: Power BI Dashboard

The interactive dashboard visualizes all findings dynamically, allowing stakeholders to filter insights by:
- City  
- Time (Month, Year)  
- Lifestyle habits  
- Health indicators  

---

## 🏁 Conclusion

This project demonstrates how **data-driven BI tools** can help insurers, researchers, and public health stakeholders:
- Identify high-risk groups  
- Design targeted interventions  
- Optimize premium structures  

For best outcomes, larger and real-time datasets can be incorporated in future research.

---

## 📂 Files Included

- `Heart_Disease_India_Dashboard.pbix` — Power BI Dashboard File  
- `heart_disease_india_dataset_normalised.xlsx` — Cleaned and Preprocessed Dataset  

