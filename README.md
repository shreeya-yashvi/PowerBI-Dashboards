Heart Disease Analysis in India — Power BI Dashboard
📁 Project Overview
This Business Intelligence (BI) project uses Power BI to analyze heart disease trends across India using a dataset originally sourced from Kaggle. To enhance the analytical scope, synthetic variables such as City, Work Type, and Date of Diagnosis were added. The primary goal is to assist health insurance firms in making data-backed decisions regarding premium structuring, risk profiling, and regional segmentation of heart disease insurance policies.

🧪 Dataset Description
The dataset includes the following categories:

Demographics: Age, Gender, City, Work Type

Health Indicators: BMI, Blood Pressure, Diabetes Status, Stress Level, Sleep Hours

Lifestyle Factors: Smoking, Alcohol Consumption, Exercise Frequency

Medical Markers: C-Reactive Protein (CRP), Homocysteine Level

Temporal Data: Date of Diagnosis (Month, Year)

🧼 Data Preprocessing and Normalization
To ensure clean and analyzable data, the following preprocessing steps were undertaken:

Handling Missing Values: NA values were identified and treated through imputation or removal where applicable.

Normalization: Continuous variables such as Age, BMI, CRP, and Homocysteine levels were scaled using Min-Max Normalization to bring them into a 0–1 range.

Categorical Encoding: Variables like Gender, Work Type, Smoking, and Alcohol levels were converted into numeric form using label encoding and mapping.

Synthetic Data Addition: New fields such as City, Work Type, and Date of Diagnosis were generated hypothetically to simulate real-world scenarios for location and time-based analysis.

This enabled more robust modeling and interactive visualization in Power BI.

🎯 Project Objectives
Analyze how age influences heart disease prevalence.

Study the correlation between BMI, blood pressure, and diabetes.

Assess the impact of exercise on heart health.

Explore how smoking and alcohol consumption affect heart disease risk.

Examine stress and sleep quality as contributors.

Identify geographic (city-based) and temporal (month/year) trends.

🧠 Key Insights for Health Insurers
✅ Age-Based Risk
Risk increases significantly after age 40, peaking post 60 years.

Premium brackets can be aligned to these age thresholds.

✅ BMI & Chronic Conditions
Individuals with BMI ≥ 25 are more susceptible to hypertension and diabetes.

Risk-based premium scaling can be used for overweight profiles.

✅ Lifestyle Behaviors
Smoking and heavy alcohol consumption substantially increase heart disease incidence.

Emphasis on behavioral health disclosures during policy onboarding.

✅ Stress & Sleep Patterns
High stress and low sleep hours correlate with elevated heart risk markers.

Stress-sensitive occupations may warrant higher scrutiny.

✅ City-Wise Segmentation
Urban areas (especially metro cities) report higher cases, likely due to lifestyle and environmental factors.

Consider city-specific underwriting rules and wellness incentives.

📊 Tools & Technologies
Power BI: Visual analytics and dashboard creation

MS Excel: Data transformation, normalization, and encoding

Python (optional): For data validation and preprocessing (if required)

🏁 Conclusion
The insights from this Power BI dashboard offer actionable guidance for health insurance firms, enabling smarter underwriting, regional targeting, and risk-aligned pricing. This project showcases how data-driven decisions can enhance both operational efficiency and public health outcomes.
