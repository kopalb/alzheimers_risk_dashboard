# 🧠 Alzheimer's Risk Dashboard
This interactive Power BI dashboard analyzes patient data to uncover risk profiles and cognitive decline patterns in Alzheimer's disease. It provides insights into how demographics, health metrics, and cognitive scores relate to disease severity and functional impairment.

![Dashboard Screenshot](alzheimer%27s%20risk%20dashboard.png)

## 📊 Dashboard Features
2149 total patients analyzed. Out of these, 760 diagnosed with Alzheimer's.
## - Key KPIs:
1. Total Patients
2. High Risk Patients
3. Average MMSE Score
4. Average Functional Score
## - Interactive Charts:
1. MMSE trend by age
2. Risk-linked functional decline
3. Distribution by ethnicity and education
## - Average Health Metrics by Risk Level:
BMI, Cholesterol, Blood Pressure
## - Dynamic Filters:
Gender, Education Level

## 🧮 How Overall Risk Levels Were Calculated
The Overall Risk Level in this dashboard is a composite score based on three domains (Each of the following contributes 1 point per attribute if present):
## i. Lifestyle Risk Factors
•	Smoking
•	Excessive alcohol consumption (>14 units/week)
•	Low physical activity (<2 times/week)
•	Poor diet (Diet quality score < 4)
•	Poor sleep (Sleep quality < 6)
Score Range: 0–5
## ii. Medical Risk Factors
•	Cardiovascular Disease
•	Diabetes
•	Hypertension
•	Depression
•	History of Head Injury
Score Range: 0–5
## iii. Genetic Risk
•	Family history of Alzheimer’s: 1 point
## -  Total Risk Score = Lifestyle + Medical + Genetic
This total score (out of 11) is classified as:
1.	0–1: Low
2.	2–3: Moderate
3.	4–5: High
4.	6+ : Very High
This scoring helps group patients for comparison across different cognitive and health metrics.

## 🧠 Score Interpretations
•	MMSE (Mini-Mental State Examination): Ranges from 0 to 30 — lower scores indicate greater cognitive impairment.
•	Functional Assessment Score: Ranges from 0 to 10 — lower scores indicate greater difficulty with daily tasks.

## 💡 Interactive Tips
1. Hover Tooltips: Hover over any chart to view detailed values.
2. Filter Selections: Use slicers on the left to explore data by gender and education level.
3. Reset View: Click the 🔄 refresh icon (top-left) to return to the default view and clear all filters.

## 📁 Files Included
1. Alzheimer’s Risk Dashboard.pbix: Power BI file
2. Alzheimer’s Risk Dashboard.pdf: PDF view of dashboard
3. alzheimer's risk dashboard.png: Image of the full dashboard
4. interactivity of dashboard.png: Dashboard view with gender (male) and education (high school) filter applied
5. zoomed in view.png: Zoomed in view of Average Health Mterics by Risk Level
6. alzheimers_disease_data.csv: Dataset

## 🚀 Getting Started
1) Download or clone this repo.
2) Open the .pbix file in Power BI Desktop.
3) Explore the interactive dashboard.

## 📚 Data Source
This project uses data from the Alzheimer's Disease Dataset published on Kaggle by Rabie El Kharoua (https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset)
