# HR Employee Attrition Analysis | Power BI

An interactive **Human Resources Analytics dashboard** built with Power BI to analyse employee attrition, identify workforce risk patterns, and uncover factors associated with employee turnover.

The project examines attrition across departments, job roles, salary levels, tenure, overtime, work-life balance, business travel, distance from work, job satisfaction, gender, and career progression.

---

## 📌 Project Overview

Employee attrition can create significant operational and financial challenges for organisations through recruitment costs, productivity loss, knowledge gaps, and disruption to team performance.

This project uses employee-level HR data to answer key business questions:

* What is the organisation's overall attrition rate?
* Which departments and job roles experience the highest attrition?
* Which employee groups are most vulnerable to turnover?
* Is attrition associated with overtime, salary, tenure, or work-life balance?
* Does distance from work appear to be associated with higher attrition?
* Are career progression and promotion patterns associated with employee turnover?
* What areas should HR investigate to improve employee retention?

---

## 🎯 Business Problem

The organisation needs to understand **where employee attrition is concentrated and which workforce characteristics are associated with higher turnover**.

The analysis provides HR and management with a data-driven view of employee retention risks that can support:

* Workforce planning
* Employee retention strategies
* Compensation reviews
* Career development programmes
* Work-life balance initiatives
* Workforce risk monitoring

> **Note:** The analysis identifies patterns and associations in the data. It does not establish causal relationships between these factors and employee attrition.

---

## 📊 Key Metrics

| KPI                      | Result |
| ------------------------ | -----: |
| Total Employees          |  1,470 |
| Attrition Count          |    237 |
| Overall Attrition Rate   |  16.1% |
| Average Monthly Income   |  6.50K |
| Estimated Attrition Cost | 12.49M |

---

## 🔍 Key Findings

### 1. Attrition is concentrated in Sales

Sales accounts for approximately **56% of total employee departures**, making it the department with the largest attrition volume.

Sales Representatives also record the highest job-role attrition rate at approximately **39.8%**, highlighting this group as an important retention-risk segment.

### 2. Overtime is associated with higher attrition

Employees who work overtime show noticeably higher attrition rates than employees who do not.

This suggests that workload and working-hour patterns should be investigated as potential contributors to employee turnover.

### 3. Lower-paid employees show higher attrition

The lowest salary group records the highest attrition rate among the salary bands analysed.

This highlights compensation as an area that HR may need to investigate alongside other employee experience factors.

### 4. Early-tenure employees are particularly vulnerable

Employees with **less than one year of tenure** have the highest attrition rate among the tenure groups.

This suggests that onboarding, early employee experience, role expectations, and initial career support may deserve further investigation.

### 5. Work-life balance is an important risk indicator

Employees with the lowest work-life balance rating show substantially higher attrition than employees in the other work-life balance groups.

### 6. Distance from the workplace may matter

Employees living more than **15 km from the workplace** show relatively high attrition rates, particularly within Sales and Human Resources.

This may indicate that commuting burden and workplace accessibility are areas worth investigating.

### 7. Career progression may influence retention

The promotion-status analysis highlights differences in attrition across employees who were recently promoted, moderately progressed, or experienced longer periods without promotion.

This suggests that career development and progression should be considered when designing retention strategies.

---

## 📈 Dashboard Pages

### 1. Executive Overview

Provides a high-level view of:

* Total employees
* Attrition count
* Attrition rate
* Average monthly income
* Estimated attrition cost
* Attrition by department
* Attrition by age group and gender
* Attrition by job role
* Business travel and overtime
* Income and salary progression

### 2. Work Environment & Overtime Risk

Examines relationships between attrition and:

* Overtime
* Department
* Distance from workplace
* Marital status
* Gender
* Work-life balance
* Job satisfaction
* Environmental satisfaction

### 3. Compensation & Career Stagnation

Explores attrition in relation to:

* Years at company
* Monthly income
* Salary level
* Tenure
* Promotion status

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Microsoft Excel**
* Data modelling
* Data cleaning and transformation
* Interactive dashboard design
* Business intelligence
* HR analytics

---

## 🔄 Data Analysis Process

The project followed an end-to-end analytics workflow:

### 1. Data Preparation

* Imported the employee dataset
* Reviewed data structure and field types
* Identified relevant HR attributes
* Prepared categorical and numerical variables

### 2. Data Transformation

* Cleaned and standardised fields using Power Query
* Created analytical categories such as:

  * Salary bands
  * Tenure groups
  * Distance groups
  * Promotion status
  * Age groups

### 3. Data Modelling

Built the analytical structure required for Power BI reporting and created measures for workforce and attrition analysis.

### 4. DAX Analysis

Created measures for:

* Total Employees
* Attrition Count
* Attrition Rate
* Average Monthly Income
* Estimated Attrition Cost
* Attrition by department
* Attrition by job role
* Attrition by employee characteristics

### 5. Dashboard Development

Designed interactive Power BI pages with:

* KPI cards
* Bar charts
* Donut charts
* Scatter plots
* Stacked charts
* Slicers
* Interactive filtering

### 6. Business Insights

Interpreted the results to identify employee segments and workforce characteristics associated with higher attrition.

---

## 💡 Business Recommendations

Based on the observed patterns, HR could investigate:

1. **Sales retention**

   * Review workload, compensation and career progression among Sales Representatives.

2. **Early-tenure support**

   * Strengthen onboarding, mentorship and early-career support.

3. **Overtime management**

   * Review workload distribution and overtime requirements.

4. **Compensation**

   * Assess whether lower-paid employee groups are competitively compensated.

5. **Career development**

   * Improve visibility of promotion pathways and development opportunities.

6. **Work-life balance**

   * Investigate workload and employee wellbeing among employees reporting lower work-life balance.

7. **Commuting challenges**

   * Explore flexible work arrangements or other support for employees with long commuting distances.

---

## 📷 Dashboard Preview

### Executive Overview

![Executive Overview](images/executive-overview.png)

### Work Environment & Overtime Risk

![Work Environment & Overtime Risk](images/work-environment-overtime.png)

### Compensation & Career Stagnation

![Compensation & Career Stagnation](images/compensation-career-stagnation.png)

> Replace the image paths above with the actual screenshot filenames in the repository.

---

## 📁 Repository Structure

```text
hr-employee-attrition-analysis/
│
├── README.md
│
├── PowerBI/
│   └── HR_Employee_Attrition_Analysis.pbix
│
├── Data/
│   └── HR_Employee_Attrition.csv
│
├── Images/
│   ├── executive-overview.png
│   ├── work-environment-overtime.png
│   └── compensation-career-stagnation.png
│
└── Documentation/
    └── HR_Attrition_Analysis_Notes.pdf
```

---

## 🧠 Skills Demonstrated

### Data Analytics

* Exploratory Data Analysis
* Workforce analytics
* Pattern identification
* Business insight generation
* KPI development

### Power BI

* Dashboard development
* Data modelling
* Interactive visualisation
* Slicers and filters
* KPI cards
* Drill-down analysis

### Power Query

* Data cleaning
* Data transformation
* Data categorisation

### DAX

* Measure creation
* Conditional calculations
* Attrition metrics
* Percentage calculations
* Business KPI development

### Business Intelligence

* Translating business questions into analytical requirements
* Identifying workforce risks
* Communicating insights to decision-makers
* Developing data-driven recommendations

---

## 🚀 Project Outcome

The dashboard provides an interactive view of employee attrition and highlights the employee segments where retention risks appear most pronounced.

The analysis indicates that attrition is particularly concentrated around **Sales, early-tenure employees, overtime workers, lower salary groups, lower work-life balance ratings, and some longer-distance commuters**.

These findings provide HR stakeholders with clear areas for further investigation and targeted retention initiatives.

---

## 👩🏽‍💻 Author

**Roseline Ndukwe**

Data Analyst | Business Intelligence | Power BI | SQL | Python

GitHub: [FinRose](https://github.com/FinRose)

---
