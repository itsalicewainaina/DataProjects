# 📊 TalentCore HR Workforce Analytics & Attrition Diagnostic

### Pan-African HR Data Mining & Interactive Power BI Dashboard

## 📌 Project Overview
**TalentCore HR Workforce Analytics** is an end-to-end HR analytics project focused on understanding **employee attrition, workforce composition, training, compensation, diversity, and departmental performance** across six African hubs: Nairobi, Mombasa, Kisumu, Kampala, Dar es Salaam, and Kigali.

Using the **CRISP-DM methodology**, I transformed 1,000 raw HR records into **247 validated employee profiles**, then developed an interactive **5-page Power BI dashboard** to turn workforce data into actionable diagnostic insights.

## 🗂️ Project Structure

```text
New-Project/
├── README.md
├── dashboard/
│   └── TalentCore WorkForce Dashboard.pbix
├── data/
│   └── cleaned_talent_core_workforce_data.xlsx
└── docs/   (optional for additional notes or screenshots)
```

- The Power BI dashboard is stored in the dashboard folder.
- The cleaned dataset used for analysis is stored in the data folder.
- The project README documents the business context, methodology, insights, and recommendations.

---

## 🎯 Business Questions
The analysis focused on questions such as:

- Which departments and locations have the highest attrition?
- Are there notable differences in attrition across employee groups?
- How does overtime status relate to employee retention?
- How are training hours distributed across departments?
- How does training relate to performance ratings?
- How is compensation distributed across roles and genders?
- Which workforce areas require further HR investigation?

---

## 🧹 Data Preparation
The raw dataset contained missing values, invalid records, inconsistent categories, and outliers.

Key preparation steps included:

- Removed **753 invalid/non-employee records**
- Standardized department, location, and gender categories
- Mapped location variations such as **DSM → Dar es Salaam**
- Imputed missing and negative salary values using role-based median logic
- Identified and resolved age and training-hour outliers
- Addressed negative tenure calculations
- Prepared the dataset for Power BI modeling
**Tools:** Python, Pandas, NumPy, Power Query

---

## 📊 Power BI Dashboard
The final dashboard contains five analytical pages:

### 1. Workforce Overview
Headcount, demographics, regional distribution, and hiring trends.

### 2. Departmental Performance
Training hours, performance ratings, and departmental comparisons.

### 3. Attrition Analysis
Attrition patterns across departments, locations, gender, and overtime status.

### 4. Compensation & Diversity
Salary distributions, role-based compensation, and gender comparisons.

### 5. Executive Summary
Key KPIs and interactive diagnostic visuals, including a decomposition tree.

---

## 💡 Key Insights

- **Finance:** Female employees recorded **33.33% attrition**, compared with **0% among male employees** in the department.
- **Overtime:** Employees without overtime had **23.89% attrition**, compared with **8.96%** among employees working overtime.
- **Regional attrition:** **Kisumu recorded 22.45% attrition**, one of the highest rates across locations.
- **Departmental attrition:** **Customer Support recorded 21.43% attrition**.
- **Training:** Sales and HR had the highest average training hours at **43.3** and **40.3 hours**, respectively, alongside relatively high performance ratings.
These findings highlight areas for further investigation rather than establishing direct causal relationships.

---

## 🎯 Recommendations
Based on the observed patterns, the analysis recommends:

- Conduct targeted retention reviews in high-attrition locations and departments.
- Investigate the Finance gender attrition gap through exit interviews and employee experience analysis.
- Review workload, engagement, and project allocation among non-overtime employees.
- Strengthen tracking of training outcomes to better evaluate training effectiveness.

---

## 🛠️ Tech Stack
**Data Analysis:** Python, Pandas, NumPy
**Business Intelligence:** Power BI, DAX, Power Query
**Visualization:** Power BI, Matplotlib, Seaborn
**Methodology:** CRISP-DM

---

## 📈 Skills Demonstrated

- HR & Workforce Analytics
- Data Cleaning & Transformation
- Exploratory Data Analysis
- Data Modeling
- DAX & Power BI
- ETL & Power Query
- Attrition Analysis
- Compensation & Diversity Analysis
- Data Visualization
- Business Insight & Recommendations

---

## 🚀 Project Outcome
The project demonstrates an end-to-end analytics workflow:

**Raw HR Data → Data Cleaning → Data Modeling → Power BI Dashboard → Diagnostic Insights → Business Recommendations**

It showcases how messy workforce data can be transformed into an interactive decision-support solution for HR and organizational planning.
