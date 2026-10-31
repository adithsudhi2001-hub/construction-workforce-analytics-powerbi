# 🏗️ Construction Workforce & Operational HR Analytics | Power BI & Excel

An enterprise-grade HR and workforce operations dashboard analyzing **1,000 employees**, multi-period payroll, safety compliance, and training development across major engineering disciplines (Civil, Structural, Mechanical, Electrical, HVAC).

---

## 📌 Executive Summary
In capital-intensive construction and engineering environments, controlling labor overhead, mitigating site safety risks, and addressing high-attrition talent bands are critical to project margins. This project consolidates raw ERP/HRMS logs to evaluate workforce utilization, overtime expenditure, safety incidents, and performance correlations.

---

## 🧭 Dashboard Architecture & Core Modules

The dashboard is structured into 6 operational reporting views:
1. **Executive Overview:** High-level workforce composition, department distribution, utilization rates, and active headcount.
2. **Workforce Cost & Efficiency:** Basic vs. gross salary analysis, overtime hours vs. overtime expenditure, and monthly cost run-rates by Cost Center.
3. **Safety & Compliance:** Incident frequency by site/camp location, severity classification (Near Miss, First Aid, Medical), lost workdays, and financial impact.
4. **Attrition & Retention:** Attrition risk segmentation (High, Medium, Low) cross-referenced by department, grade band, and compensation tiers.
5. **Performance, Training & Rewards:** Evaluation score distributions, training budget ROI, certification pass/fail ratios, and promotion readiness.
6. **Executive Insights:** Strategic recommendations for operations management and project directors.

---

## ⚙️ Tech Stack & Methods
* **Analysis & Visualization:** Microsoft Power BI Desktop
* **Data Cleansing & Transformation:** Microsoft Excel, Power Query
* **Data Modeling:** Multi-table relational schema connecting Employee Master, Payroll Records, Attendance Logs, Training & Certifications, Performance Appraisals, and Safety Incidents.
* **Calculations:** DAX (Overtime Rate indices, Rolling Turnover %, Incident Severity Ratios, Utilization %).

---

## 🔍 Key Findings & Operational Takeaways

### 1. Cost & Overtime Dynamics
* Overtime expenditure accounts for a disproportionate share of labor overhead in site-based disciplines, indicating staffing shortages during critical project milestones.
* Housing and transport allowances represent substantial fixed costs that vary significantly across employee grade bands ($G_1$ to $G_5$).

### 2. HSE (Health, Safety & Environment) Risks
* Camp and site locations account for the majority of recorded incidents, with scaffolding and tool misuse identified as primary root causes.
* Critical and high-severity incidents generated significant direct compensation costs and lost workdays, emphasizing the need for targeted retraining.

### 3. Training Efficacy & Retention
* Employees completing internal *Lean Construction* and safety protocols achieved higher average performance ratings and lower attrition risk scores compared to untrained peers.

---

## 📁 Repository Structure
```text
├── Construction_HR_Dataset.xlsx          # Raw and cleaned multi-sheet dataset
├── Construction_HR_Analytics.pbix        # Interactive Power BI workbook
├── screenshots/                          # Dashboard preview images
└── README.md                             # Documentation and project findings
