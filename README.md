# HR Analysis Team Project

## 📘 Project Overview
This project focuses on **HR Data Analysis** to understand employee behavior, performance trends, and key workforce metrics.  
The work involved three major phases — **Data Cleaning**, **Exploratory Data Analysis (EDA)**, and **Dashboard Development** — conducted collaboratively under the guidance of **[RD Group of Industries](https://github.com/TheRDGroupOfIndustries)**.

---

## 🧩 Project Details

### **Title:** HR Analysis Team Project  
### **Description:**  
A collaborative HR analytics project involving data cleaning, EDA, and the creation of an interactive Power BI dashboard.  
The goal was to analyze employee data and derive insights into workforce patterns and behaviors.

---

## 👥 Team Members & Roles

| Name | Role | GitHub Profile |
|------|------|----------------|
| Himanshu | Data Cleaning | [Himanshu76-DA](https://github.com/Himanshu76-DA) |
| Siddhesh | Exploratory Data Analysis (EDA) | [siddheshDA](https://github.com/siddheshDA) |
| Nandini | Dashboard Development | [nandiniarjun03](https://github.com/nandiniarjun03) |

**Guided by:** [RD Group of Industries](https://github.com/TheRDGroupOfIndustries)

---

## 🔹 Phase 1: Data Cleaning  
**Performed by:** [Himanshu](https://github.com/Himanshu76-DA)

**Steps:**
- Collected the raw dataset: [HR_Analytics.csv](https://github.com/nandiniarjun03/HR_Analysis_Team_Project/blob/main/HR_Analytics.csv)  
- Cleaned and preprocessed using Python (Pandas): [Data Cleaning Notebook](https://github.com/nandiniarjun03/HR_Analysis_Team_Project/blob/main/HR%20Analytics%20Data%20cleaningJUP.ipynb)  
- Exported the cleaned dataset: [HR_Analysis_cleaned.xls](https://github.com/nandiniarjun03/HR_Analysis_Team_Project/blob/main/HR_Analysis_cleaned.xls)

**Key Tasks:**
- Handled missing values and duplicates  
- Standardized column names and data formats  
- Prepared dataset for further analysis  

---

## 🔹 Phase 2: Exploratory Data Analysis (EDA)  
**Performed by:** [Siddhesh](https://github.com/siddheshDA)

**Notebook:** [EDA File](https://github.com/nandiniarjun03/HR_Analysis_Team_Project/blob/main/HR_DATA_EDA_ENHANCED.ipynb)

**Highlights:**
- Analyzed employee demographics, department distribution, and retention trends  
- Identified relationships between experience, performance, and attrition  
- Derived key insights for HR decision-making  

---

## 🔹 Phase 3: Dashboarding  
**Performed by:** [Nandini](https://github.com/nandiniarjun03)

**Deliverables:**
- Built an interactive Power BI dashboard  
- Integrated visual insights derived from the EDA  
- Designed KPIs for HR analytics and employee retention metrics  

**Files:**
- Power BI File: [Dashboard - HR Analytics.pbix](https://github.com/nandiniarjun03/HR_Analysis_Team_Project/blob/main/Dashboard%20-%20HR%20Analytics%20copy.pbix)

---

## 🛠️ Tools & Technologies
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** — for data processing and visualization  
- **Jupyter Notebook** — for analysis and documentation  
- **Power BI** — for interactive dashboarding  
- **GitHub** — for project collaboration and version control  

---

## 🔎 Phase 3 Insights: HR & Performance Dashboards

**Performed by:** [Nandini](https://github.com/nandiniarjun03)

---

### 📊 Executive Snapshot
- **Avg Monthly Salary:** ~₹6,403  
- **Total Employees:** ~100K  
- **Avg Age:** ~41 years  
- **Avg Performance Score:** ~3  
- **Avg Training Hours:** ~49.5  

> Used slicers (Gender, Education, Department, Resigned, Performance Score, Hire Year, Job Title, Remote Status, Satisfaction) to drill down.

---

### 💰 Compensation Insights
- **Salary tracks performance:** Avg monthly salary **rises steadily with higher performance scores**.  
- **Department spend is balanced:** No single department dominates salary outlay at a glance.  
- **Team-size effect:** Compensation **peaks in mid-to-larger teams**; very small/very large teams show dips—likely span-of-control/role-mix effects.

**What to do**
- Tighten **comp–perf alignment** (bands/bonus calibration).
- Investigate **outliers** (high pay + low perf, or inverse).
- Review **team structure** where salary peaks.

---

### 👥 Workforce Composition
- **Gender:** Near-balanced male/female; small “Other” segment.  
- **Education:** Majority **Bachelor**, followed by **Master**; HS/PhD are smaller cohorts.  
- **Remote Mix:** Significant **hybrid/occasional** segment; **fully-remote** and **never-remote** also present.

**What to do**
- Maintain **inclusive pipelines** across gender/education.
- Tune **remote policy** by role, measuring engagement & performance.

---

### 🎖️ Promotions & Performance
- **Promotions skew male** across most departments; female/other promotions are lower.  
- Higher performance cohorts show **clear salary uplift** and mobility.

**What to do**
- Run a **promotion equity audit** (rate by gender/department controlling for tenure, level, performance).  
- Add **structured criteria & calibration** to reduce bias.  
- Track **time-in-level** and readiness pipelines.

---

### 🔁 Attrition / Resignations
- **Resignations by department** are relatively even—no single standout spike.  
- Combine **Resigned = Yes** with **Satisfaction / Remote** slicers to surface at-risk cohorts.

**What to do**
- Launch **stay interviews** and targeted **manager coaching** where filtered views show risk.  
- Pair **mentorship + clear career paths** to reduce exits in low-mobility cohorts.

---

### 🟢 Multi-Factor View (Bubble/Scatter)
- Departments with **higher performance** tend to land **higher pay**; bubble size/color reveal departmental patterns.

**What to do**
- **Replicate best practices** from high-conversion departments (perf → pay).  
- Where performance is high but pay lags, check **band constraints** or **budget timing**.

---

### 🔧 How to Drill Down (suggested slicer paths)
- **Equity check:** `Gender = Female` → compare **Promotions** vs Male across Departments.  
- **New-hire retention:** `Hire Year = recent` → `Resigned` + `Satisfaction`.  
- **Remote productivity:** `Remote = Fully / Hybrid / Never` → compare **Performance & Salary**.

---

### ✅ Recommended Actions (Summary)
1. **Promotion Equity Program:** Quarterly calibration & transparent criteria; publish promo rates by cohort.  
2. **Comp–Perf Refresh:** Recalibrate bands; add performance-weighted variable pay where impactful.  
3. **Retention Playbooks:** Cohort-specific interventions (manager training, mentorship, mobility paths).  
4. **Team Design Review:** Validate spans/role-mix where salary peaks around mid-size teams.  
5. **Remote Policy Tuning:** Optimize flexibility by role using satisfaction/performance evidence.

---

### 📝 Notes
- Values are **aggregate indicators** from the dashboards provided; confirm exact counts in the dataset.  
- “Total Promotions” appears **org-level**; verify definition (unique employees vs events).  
- Insights are **directional**; quantify with slicers before policy changes.



## 📊 Outcomes
- Cleaned and structured HR dataset ready for analytics  
- Comprehensive EDA providing actionable insights  
- Interactive Power BI dashboard enabling HR data-driven decisions  

---

