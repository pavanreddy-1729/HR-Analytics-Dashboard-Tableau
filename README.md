# HR Analytics Dashboard — Tableau

An interactive HR Analytics Dashboard built in Tableau, analyzing employee attrition trends across 1,470 employees and 39 attributes. The dashboard helps HR and leadership teams identify high-risk attrition segments and make data-driven retention decisions.

## 🔗 Live Interactive Dashboard

[**View on Tableau Public →**]([PASTE_YOUR_TABLEAU_PUBLIC_LINK_HERE](https://public.tableau.com/app/profile/pavan.daggula/viz/HRDASHBOARD_17781879266050/HRANALYTICSDASHBOARD))

## 🎯 Project Objective

Analyze employee attrition patterns to identify:
- Which departments and demographics have the highest attrition risk
- Whether age, gender, education, or job role correlate with attrition
- How job satisfaction varies across roles
- Actionable insights for HR retention strategy

## 📊 Key Insights

- **Overall attrition rate:** 16.12% (237 of 1,470 employees)
- **Sales department** has the highest attrition at **38.82%** (92 employees) — investigate compensation and quotas
- **R&D** accounts for the largest share of attrition (133 employees, 56.12%)
- **Mid-career employees aged 25-34** attrit at **29.11%** — the highest of any age group, suggesting onboarding and growth gaps
- **Life Sciences** is the most affected education field (89 attritions)
- **Male attrition (150)** significantly exceeds female (87) in absolute numbers
- Job satisfaction varies widely across roles, with Sales Executives showing both high counts and high satisfaction variance

## 🛠️ Tools & Technologies

- **Tableau Desktop / Tableau Public** — Dashboard development and publishing
- **Microsoft Excel** — Data preparation and exploration
- **IBM HR Analytics Employee Attrition Dataset** — Source data

## 📁 Repository Structure
HR-Analytics-Dashboard-Tableau/
├── README.md
├── HR_Data.xlsx                       # Source dataset
├── HR_Analytics_Dashboard.twbx        # Packaged Tableau workbook
├── dashboard_preview.png              # Dashboard screenshot
└── .gitignore

## 📊 Dataset

**IBM HR Analytics Employee Attrition & Performance Dataset**

- **Size:** 1,470 employees × 39 attributes
- **Target Variable:** Attrition (Yes/No)
- **Source:** IBM (publicly available on Kaggle)

**Attribute Categories:**

- **Demographics:** Age, Gender, Marital Status, Education, Education Field, Distance From Home
- **Job Details:** Department, Job Role, Job Level, Business Travel, Over Time, Years at Company, Years in Current Role, Years Since Last Promotion, Years With Current Manager, Total Working Years
- **Compensation:** Monthly Income, Daily Rate, Hourly Rate, Monthly Rate, Percent Salary Hike, Stock Option Level
- **Satisfaction Metrics:** Job Satisfaction, Environment Satisfaction, Job Involvement, Relationship Satisfaction, Work Life Balance, Performance Rating
- **Other:** Training Times Last Year, Num Companies Worked

## 🎨 Dashboard Features

- **KPI Summary Cards:** Employee Count, Attrition Count, Attrition Rate, Active Employees, Average Age
- **Department-wise Attrition** breakdown with percentage share
- **Age Group Distribution** with adjustable age bin parameter
- **Job Satisfaction Rating** matrix across 9 job roles and 4 satisfaction levels
- **Education Field-wise Attrition** breakdown
- **Attrition Rate by Gender Across Age Groups** with donut visualizations
- **Interactive Education-level filter** affecting all charts

## 🚀 How to Use

1. Click the **Live Dashboard** link above to interact with the published version on Tableau Public
2. To explore the workbook locally: download `HR_Analytics_Dashboard.twbx` and open in Tableau Desktop or Tableau Public
3. The dataset (`HR_Data.xlsx`) is included for transparency and reproducibility

## 📈 Future Enhancements

Planned additions for v2:
- [ ] **Compensation vs Attrition** — Monthly Income distribution analysis
- [ ] **Distance From Home vs Attrition** — Commute impact analysis
- [ ] **Overtime impact** — Cross-tab of Over Time × Job Satisfaction × Attrition
- [ ] **Years Since Last Promotion** — Career stagnation as attrition driver
- [ ] **Predictive modeling** in Python to identify high-risk employees

## 👤 Author

**Pavan Kumar Daggula**
Data Analyst | Power BI · SQL · Python · Tableau

- 🔗 LinkedIn: [linkedin.com/in/pavandaggula](https://www.linkedin.com/in/pavandaggula)
- 🐙 GitHub: [github.com/pavanreddy-1729](https://github.com/pavanreddy-1729)
- 📧 Email: pavanreddy6174@gmail.com

---

⭐ If you found this project helpful, please consider giving it a star!
