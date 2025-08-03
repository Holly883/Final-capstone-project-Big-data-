# 🦠 TB Case Trends Across Different Countries - Capstone Project 🌍

👩🏾‍💻  Muvunyi Holiness ID 27137
**🏥 Sector:** Health  
**📊 Project Summary:**  
Analyzing tuberculosis (TB) case trends across countries using WHO data from 2023. The goal is to identify high TB burden countries and cluster them to support targeted health interventions and resource allocation.  

---

## 🔬 Project Overview

This capstone project explores real-world TB incidence data to uncover patterns that inform health policies and resource distribution. Using **Python** for data cleaning, exploratory data analysis (EDA), and machine learning clustering, combined with **Power BI** for interactive visualization, the project delivers comprehensive insights into global TB trends.

---

## 📚 Dataset

- **📂 Title:** Estimated number of incident TB cases by age group and sex  
- **🔗 Source:** [WHO Global TB Database](https://data.who.int/dashboards/tuberculosis?m49=004)  
- **📄 Format:** CSV  
- **📈 Rows:** Varies (depending on dataset)  
- **🧾 Columns:** Country, Year, TB Cases, Age Group, Sex, Estimate Ranges

---

## 🛠️ Project Components

### 1️⃣ Data Cleaning & Preprocessing

- Loaded and inspected raw WHO TB dataset.  
- Cleaned missing or inconsistent data entries.  
- Selected relevant columns (Country, Year, TB Cases).  
- Standardized column names for consistency.

### 2️⃣ Exploratory Data Analysis (EDA)

- Summarized total and average TB cases per country.  
- Visualized top 10 countries with highest TB incidence using bar plots.  
- Identified trends and initial insights into TB distribution.

### 3️⃣ 🤖 Machine Learning: Clustering

- Applied KMeans clustering to group countries by average TB cases.  
- Evaluated model with Silhouette Score (0.931 - strong cluster separation).  
- Developed a **custom cluster summary function** providing:  
  - Number of countries per cluster  
  - Average TB cases within each cluster  
  - Top country by TB cases in each cluster  

### 4️⃣ 📊 Power BI Dashboard

- Created an interactive dashboard highlighting key findings.  
- Included filters, slicers, and multiple chart types for easy exploration.

---

## 🚀 Innovation

Implemented a custom function to summarize cluster characteristics, enhancing interpretability and demonstrating advanced coding skills beyond standard clustering.

---

## 📁 How to Use This Repository

- **📓 Jupyter Notebook:** Complete Python code with markdown explanations for cleaning, analysis, clustering, and evaluation.  
- **📊 Power BI File:** Interactive dashboard presenting visual insights.  
- **📂 Dataset:** Cleaned dataset for full reproducibility.

---
## 🛠️ Tools Used

- **Python** 🐍 — For data cleaning, exploratory analysis, and machine learning modeling (clustering).  
- **Jupyter Notebook** 📓 — Interactive coding environment for analysis and documentation.  
- **Pandas & NumPy** 📊 — Data manipulation and numerical operations.  
- **Matplotlib & Seaborn** 📈 — Data visualization libraries for plotting graphs.  
- **Scikit-learn** 🤖 — Machine learning library for clustering and evaluation metrics.  
- **Power BI** 📊 — For creating interactive dashboards and visualizing key insights.  
- **Git & GitHub** 🧑🏽‍💻 — Version control and project repository hosting.

---
## 🔮 Future Work

- Integrate socio-economic and healthcare infrastructure data for deeper analysis.  
- Implement time-series forecasting to predict TB trends.  
- Add AI visuals and live data feeds to Power BI dashboard.

---
