# Final-capstone-project-Big-data-
# TB Case Trends Across Different Countries - Capstone Project

**Author:** Muvunyi Holiness  
**Sector:** Health  
**Project Summary:** Analysis of tuberculosis (TB) case trends across various countries using WHO data from 2023. The goal is to identify high TB burden countries and cluster them to help guide targeted health interventions.

---

## Project Overview

This capstone project aims to analyze real-world TB incidence data and uncover patterns that can inform health policies and resource allocation. Using Python for data cleaning, exploratory data analysis (EDA), and machine learning clustering, combined with Power BI for interactive visualization, the project presents a comprehensive approach to understanding TB trends globally.

---

## Dataset

- **Title:** Estimated number of incident TB cases by age group and sex  
- **Source:** [WHO Global TB Database](https://data.who.int/dashboards/tuberculosis?m49=004)  
- **Format:** CSV  
- **Rows:** Varies (depending on dataset)  
- **Columns:** Includes Country, Year, TB Cases, Age Group, Sex, and estimates range

---

## Project Components

### 1. Data Cleaning & Preprocessing

- Loaded and inspected raw WHO TB dataset.  
- Cleaned missing or inconsistent data entries.  
- Selected relevant columns (Country, Year, TB Cases) for analysis.  
- Standardized column names for consistency.

### 2. Exploratory Data Analysis (EDA)

- Summarized total and average TB cases per country.  
- Visualized top 10 countries with highest TB incidence using bar plots.  
- Identified trends and preliminary insights into TB distribution.

### 3. Machine Learning: Clustering

- Applied KMeans clustering to group countries by average TB cases.  
- Evaluated model using Silhouette Score (achieved 0.931, indicating strong clusters).  
- Developed a **custom cluster summary function** to provide additional insights, such as:  
  - Number of countries per cluster  
  - Average TB cases within each cluster  
  - Top country by TB cases in each cluster  

### 4. Power BI Dashboard

- Created an interactive dashboard highlighting key findings.  
- Included filters, slicers, and multiple chart types for user-friendly exploration.

---

## Innovation

The project includes a custom-built function to summarize cluster characteristics, improving interpretability and demonstrating additional coding skills beyond standard model application.

---

## How to Use This Repository

- **Jupyter Notebook:** Contains all Python code for data cleaning, analysis, clustering, and evaluation with detailed markdown explanations.  
- **Power BI File:** Interactive dashboard showcasing visual insights into TB case trends.  
- **Dataset:** The cleaned dataset is included for reproducibility.

---

## Future Work

- Extend the project by integrating socio-economic and healthcare infrastructure data to better understand drivers of TB incidence.  
- Implement time-series forecasting models to predict future TB trends.  
- Enhance Power BI dashboard with AI visuals and real-time data updates.

---



*This project was completed as part of the capstone requirements for [Your School Name or Program]. All work is original and adheres to academic integrity guidelines.*

