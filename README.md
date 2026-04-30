# PeoplePulse - HR Insights Dashboard

A modern, executive-ready HR analytics dashboard built in Power BI to visualize employee attrition, satisfaction, and organizational trends. This project explores key workforce metrics using interactive KPIs, department-level comparisons, and engagement indicators.

---

## Tech Stack & Tools

[![Power BI](https://img.shields.io/badge/Power%20BI-visualization-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-data--processing-purple?logo=pandas)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-EDA-orange?logo=jupyter)](https://jupyter.org/)
[![GitHub](https://img.shields.io/badge/GitHub-hosted-181717?logo=github)](https://github.com/)



## Objective

Enable business and HR leaders to:
- Understand department-wise attrition trends
- Identify roles with low engagement or satisfaction
- Compare workforce distribution and overtime impact
- Use interactive filters for slicing insights by demographics

---

## Key Features

- **Interactive KPI Cards** – Total Employees, Attrition Rate, Avg Tenure, Satisfaction Score
- **Visual Breakdown** – Attrition by Department, Overtime, Age, and Job Role
- **Filters** – Department, Gender, Tenure Bucket, Education Field, Marital Status
- **Dynamic Reporting Date** – Based on system time
- **Executive Layout** – Compact, readable, designed for business storytelling

---

## Project Structure
```
## Project Structure

peoplepulse/
├── data/                      # Datasets used in the project
│   ├── raw/                   # Original unprocessed data
│   ├── processed/             # Cleaned and feature-engineered data
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv          # CSV file
│
├── notebooks/                 # Jupyter notebooks for EDA and transformation
│   ├── EDA.ipynb/                   # Python NB with EDA steps
│   └── Feature_Engineering.ipynb/             # Python NB with feature engineering steps    
│
├── dashboard/                 # Power BI dashboard file
│   └── PeoplePulse_HR_Executive.pbix
│
├── assets/                    # Images for README and documentation
│   ├── kpi_overview.png
│   ├── trends.png
│   └── line_and_roles.png
│
└── README.md                  # Project documentation


```
---
## Visual Highlights

### KPI & Overview Section
![KPI Overview](assets/kpi_overview.png)

### Workforce & Attrition Breakdown
![Trends](assets/trends.png)

### Trend and Satisfaction Insights
![Line & Roles](assets/line_and_roles.png)

---

## Tools Used

- **Power BI** – Interactive dashboard design & KPI metrics
- **Python (Pandas, Seaborn)** – Data wrangling, EDA
- **DAX** – KPI and conditional logic in Power BI
- **Dataset** – [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## Key Insights

- Departments like Sales and R&D experience the most attrition
- Overtime employees are 2x more likely to leave
- Younger employees show higher churn
- Several job roles have below-average satisfaction levels (≤ 2.7)

---

## Author

**Hari Dave**  
MS Data Science | University of Arizona  
[LinkedIn](https://www.linkedin.com/in/your-profile/)  
[GitHub](https://github.com/your-username)

---

## Contact

If you’d like to collaborate, give feedback, or discuss HR analytics, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/your-profile/).

---

> ✨ This project was created to demonstrate best practices in executive dashboarding, visual storytelling, and real-time filtering for workforce data.
