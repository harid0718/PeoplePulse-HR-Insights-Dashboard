# 📊 PeoplePulse – HR Insights Dashboard

A modern, executive-ready HR analytics dashboard built in Power BI to visualize employee attrition, satisfaction, and organizational trends. This project explores key workforce metrics using interactive KPIs, department-level comparisons, and engagement indicators.

---

## 🧠 Objective

Enable business and HR leaders to:
- Understand department-wise attrition trends
- Identify roles with low engagement or satisfaction
- Compare workforce distribution and overtime impact
- Use interactive filters for slicing insights by demographics

---

## 📈 Key Features

- 📌 **Interactive KPI Cards** – Total Employees, Attrition Rate, Avg Tenure, Satisfaction Score
- 🧩 **Visual Breakdown** – Attrition by Department, Overtime, Age, and Job Role
- 🎛️ **Filters** – Department, Gender, Tenure Bucket, Education Field, Marital Status
- 📅 **Dynamic Reporting Date** – Based on system time
- 🎨 **Executive Layout** – Compact, readable, designed for business storytelling

---

## 📂 Project Structure
```
peoplepulse/ │ 
├── data/ # Datasets │├── raw/ # Original IBM HR dataset 
│ └── processed/ # Cleaned dataset used in dashboard │ 
├── notebooks/ # EDA and data transformation notebooks │ 
├── scripts/ # Python scripts for data cleaning and processing │ 
├── dashboard/ # Power BI dashboard file │ └── PeoplePulse_HR_Executive.pbix │ 
├── assets/ # Screenshots and visuals for README │ 
├── kpi_overview.png │ 
├── trends.png │ └── line_and_roles.png │ 
├── README.md # Project documentation └── .gitignore # File exclusions for Git

```
---
## 📊 Visual Highlights

### KPI & Overview Section
![KPI Overview](assets/kpi_overview.png)

### Workforce & Attrition Breakdown
![Trends](assets/trends.png)

### Trend and Satisfaction Insights
![Line & Roles](assets/line_and_roles.png)

---

## 🛠 Tools Used

- **Power BI** – Interactive dashboard design & KPI metrics
- **Python (Pandas, Seaborn)** – Data wrangling, EDA
- **DAX** – KPI and conditional logic in Power BI
- **Dataset** – [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 💡 Key Insights

- Departments like Sales and R&D experience the most attrition
- Overtime employees are 2x more likely to leave
- Younger employees show higher churn
- Several job roles have below-average satisfaction levels (≤ 2.7)

---

## 👨‍💻 Author

**Hari Dave**  
MS Data Science | University of Arizona  
📍 [LinkedIn](https://www.linkedin.com/in/your-profile/)  
📦 [GitHub](https://github.com/your-username)

---

## 📬 Contact

If you’d like to collaborate, give feedback, or discuss HR analytics, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/your-profile/).

---

> ✨ This project was created to demonstrate best practices in executive dashboarding, visual storytelling, and real-time filtering for workforce data.
