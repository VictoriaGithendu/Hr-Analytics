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
- 🔻 **Attrition Percentage:** 16.1%  
- 🔻 **Attrition Count:** 237  
- 🎂 **Average Age:** 37 years  
- 🕒 **Average Tenure:** 7 years  

---

## Key Insights by Dashboard

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

**Attrition Overview**
- 237 employees left the company, giving an attrition rate of 16.1%.
- Average age of attrition: **34yrs**; average tenure: **5yrs**
   
**Attrition by Department and Role**
- R&D had the highest number of exits (133 employees).
- Sales has the highest attrition rate  of 21%, despite having fewer total exits than R&D.
- Lab Technicians (62), Research Scientists (47), and Managers (25) were the most affected roles.
       
**Attrition by Demographics**
- The age group(26–35) experienced the highest attrition(116 employees), sugessting career mobility or unmet expectations.
 - Life Sciences (89) and Medical (63) account for the most exits — consider reviewing workload or career growth in these fields.
   
**Attrition by Satisfaction and Performance**
- Employees across all satisfaction scores exited, including middle to high scores, indicating other hidden drivers beyond work conditions.
- No clear link between high pay or performance and retention — suggests non-financial factors (like growth or engagement) are driving exits. 

**Implications**  
- Review retention efforts for mid-career staff in technical roles.
- Reassess career development, recognition and promotion opportunities in high risk roles.

---

### **3. Performance Metrics**  
![HR Performance Overview](Images/Performance.png)

**Performance by Tenure**
- Employees with 11–15 years of tenure have the highest average performance rating (3.22).
- Newer employees (0–5 years) perform steadily at an average of 3.15.
- A slight decline is observed in the 20+ year group (avg. 3.12), which may suggest a need for renewed engagement at this stage.

**Departmental Performance**
- The Sales department slightly outperforms others, with an average score of 3.16.
- Performance ratings across all departments are close, indicating consistent evaluation but possibly masking distinctions between high and average performers.

**Training vs. Performance**
- Employees who completed 2–4 training sessions performed the best, with scores consistently in the 70–80 range.
- Employees with no or minimal training tended to underperform, showing the value of structured learning and development.

**Performance vs. Monthly Income**
- There's a positive but non-linear relationship between performance and income.
- Sales employees show wide income variation at similar performance levels, possibly due to commission structures.
- HR and R&D departments display tighter clusters, with compensation more directly aligned to performance.

**Attrition Risk**
- A total of 31 top performers left the company.
- These exits suggest possible issues such as lack of recognition, limited career progression, or compensation misalignment.

**Implications**
- Consider enhancing training initiatives and differentiating performance rewards more clearly.
- Analyze why high performers are leaving and apply targeted retention strategies for key roles and tenure bands.

---

### **4. Diversity Dashboard**  
![Diversity Dashboard](Images/Diversity.png)

**Workplace Conditions**
- 20% of employees travel frequently.
- Average commute distance is 9.2 km.
- Environment satisfaction is moderate at 2.7 out of 4.
- Career mobility is moderate, with an average of 2.7 previous companies worked.
- 30% of employees work overtime, more common among males(236) than (180) females.
   
**Gender Distribution**
- R&D and Sales are male-dominated.
- HR department has a higher female population.
- Male employees earn more than female employees at every tenure level, suggesting a potential gender-based income gap.

**Education and roles by gender**
- Education Level 3 and 4 are most common for both genders.
- Males dominate technical and leadership roles, while healthcare and HR roles have higher female representation.  

**Implications:**  
- Consider equity audits and role-based training to promote fair opportunities and address gender imbalances.
- Review overtime and satisfaction by department to improve inclusivity and work-life balance.
- Promote inclusive growth strategies to balance leadership representative.

---
