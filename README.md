# Work Place Analytics

This project explores employee demographics, attrition rates, performance trends, and diversity metrics. It delivers actionable insights to support HR in strategic decision-making and workforce optimization through interactive Power BI dashboards.

The analysis covers key dimensions such as gender, marital status, age groups, tenure, department-level attrition, performance alignment, and work conditions.

---

## 📂 Dataset Used

The dataset is a fictional HR dataset containing 1,470 employee records with fields such as:
- Demographics (Gender, Age, Marital Status, Education)
- Job Information (Department, Job Role, Monthly Income, Overtime)
- Employee History (Years at Company, Number of Companies Worked, Business Travel)
- Performance Ratings and Attrition Status

_Source: IBM HR Analytics Employee Attrition & Performance (Kaggle)_

---

## 🛠 Tools Used

- **Excel** – For data cleaning and initial formatting
- **Power BI** – For data modeling, dashboard creation, and visualization
- **DAX (Data Analysis Expressions)** – For calculated metrics and custom KPIs in Power BI

---

## 📊 General Insights

- 👥 **Total Employees:** 1,470  
- 🔻 **Attrition Percentage:** 17%  
- 🔻 **Attrition Count:** 237  
- 🎂 **Average Age:** 37 years  
- 🕒 **Average Tenure:** 7 years  

---

## 📁 Key Insights by Dashboard

---

### **1. Employee Overview**  
![HR Dashboard Overview](Images/Overview.png)

**Highlights:**
- **Gender Split:** 60% Male (882), 40% Female (588)
- **Dominant Age Group:** 26–35 years (606 employees); least = 56–65 years (47 employees)
- **Department Distribution:** R&D = 65.4% (961 employees)
- **Tenure Breakdown:**
  - 0–5 Years: 52.8% (776 employees)
  - 20+ Years: 4.5% (66 employees)
- **Marital Status:** 45.8% of employees are married

---

### **2. Employee Attrition**  
![Attrition Dashboard](Images/Attrition.png)

**Key Insights:**
- **R&D** has the highest number of employees who left, while **Sales** has the highest attrition rate (23%)
- **Top attrition group**: Employees with 2–3 years tenure
- **Males under 30** in technical roles show higher attrition trends
- **31 top performers** exited, highlighting potential risk areas in engagement or rewards

---

### **3. Performance Metrics**  
![HR Performance Overview](Images/Performance.png)

**Performance by Tenure**
- 11–15 years tenure = highest average rating (3.22)
- Newer employees (0–5 years) average 3.15
- 20+ year tenure group shows slight decline (3.12)

**Departmental Performance**
- Sales performs slightly above others (3.16)
- Narrow performance spread suggests consistent evaluation but limited differentiation

**Training vs. Performance**
- 2–4 training sessions = strongest performers
- No/low training correlates with underperformance

**Performance vs. Monthly Income**
- Positive but non-linear relationship
- Sales shows wide income range at similar performance levels (commission-based?)
- HR and R&D = more consistent compensation structure

**Attrition Risk**
- 31 top performers exited, pointing to issues like unmet career goals or pay misalignment

---

### **4. Diversity Dashboard**  
![Diversity Dashboard](Images/Diversity.png) *(Insert screenshot)*

**Key Insights:**
- Gender imbalance exists in some departments
- Younger employees (under 30) make up 22% of the workforce
- 31% of employees work overtime — with higher incidence in certain roles
- Frequent travelers account for 18% of staff
- Average commute distance is 8.6 km; environment satisfaction is high (3.6/4)

---

## 📌 Project Summary

This analysis helps identify:
- Workforce diversity gaps
- Attrition trends by role, age, and performance
- Performance-related retention risks
- Strategic areas for improving employee satisfaction, equity, and developme
