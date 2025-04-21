# 🏃‍♂️ EDA Portfolio Project – Treadmill Buyer Profile

## 📌 Project Overview
This exploratory data analysis (EDA) project focuses on identifying key customer characteristics that influence the purchase of different treadmill models offered by **AeroFit**. The goal is to help the market research team better understand the target audience for each product and improve customer recommendations.

---

## 📊 Dataset Description
The dataset, `aerofit_treadmill_data.csv`, contains customer data from the past three months and includes the following features:

- **Product**: Treadmill model purchased – KP281, KP481, KP781  
- **Age**: Customer's age  
- **Gender**: Male or Female  
- **Education**: Years of education  
- **MaritalStatus**: Single or Partnered  
- **Usage**: Expected weekly treadmill usage  
- **Fitness**: Self-rated fitness level (1–5)  
- **Income**: Annual income in USD  
- **Miles**: Expected weekly distance in miles  

---

## 🧠 Business Objective
To investigate whether significant differences exist in customer profiles based on the product purchased and extract insights that can be used to:
- Segment the market
- Improve targeting and personalization
- Enhance product recommendation systems

---

## 🧪 Project Workflow

### 1. Data Exploration & Processing
- Importing and reading data
- Checking shape, datatypes, missing and duplicate values

### 2. Statistical Summary
- Descriptive stats for numerical and categorical features

### 3. Non-Graphical Analysis
- Value counts and unique values for categorical features

### 4. Graphical Analysis
- Univariate: Histograms, boxplots, count plots  
- Bivariate: Product vs Gender, Age, Marital Status  
- Multivariate: Pairplots

### 5. Correlation Analysis
- Heatmap visualization and interpretation

### 6. Outlier Detection
- IQR method for spotting anomalies

### 7. Conditional Probabilities
- Frequency tables and probability calculations across Product, Gender, Age, Income, Fitness, and Marital Status

### 8. Actionable Insights & Recommendations
- Key takeaways and suggestions for business decision-making

---

## 📁 Files
- `aerofit_treadmill_data.csv` – The dataset used
- `treadmill_eda.ipynb` – Jupyter Notebook with full analysis

---

## 🔍 Key Insights
- High-income and high-fitness individuals tend to purchase the KP781 model
- KP281 is preferred by younger, single customers
- Weekly usage and fitness levels are strong indicators of the product type

---

## 📌 Conclusion
This project provides a comprehensive customer profile analysis for each treadmill type, supporting data-driven decisions in marketing and product strategy.

---
