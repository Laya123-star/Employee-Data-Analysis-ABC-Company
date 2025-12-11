# Employee Data Analysis Project

## Project Overview
This project provides a comprehensive analysis of employee data from ABC Company.  
The dataset contains **458 rows and 9 columns**, detailing employee demographics, positions, teams, salaries, and other attributes.  

**Objective:**  
Preprocess the dataset, perform analyses, generate visualizations, and extract actionable insights for workforce planning, salary management, and HR decisions.

---

## Dataset Description
- **Rows:** 458  
- **Columns:** 9  
- **Key Columns:**  
  - `team` – Employee's team assignment  
  - `position` – Employee's job role  
  - `age` – Employee age  
  - `salary` – Employee salary  
  - `height` – Employee height (corrected during preprocessing)  

---

## Preprocessing Steps
1. **Column Standardization:**  
   - Converted all column names to lowercase and replaced spaces with underscores for consistency.  

2. **Missing Value Handling:**  
   - Numeric columns: Filled with median values.  
   - Categorical columns: Filled with mode or `"Unknown"` where necessary.  

3. **Duplicate Removal:**  
   - Identified and removed duplicate rows to maintain data integrity.  

4. **Height Column Correction:**  
   - Replaced `height` column with random integers between **150–180 cm** for consistency.  

---

## Analysis Tasks

### 1. Team Distribution
- Counted employees per team and calculated percentage split.  
- Identified the largest team.  

**Visualizations:**  
- Bar chart: Number of employees per team  
- Pie chart: Percentage distribution of employees by team  

---

### 2. Employee Position Segregation
- Counted employees per position and calculated percentage split.  
- Highlighted the most common roles.  

**Visualizations:**  
- Count plot of employee distribution by position  

---

### 3. Age Group Analysis
- Categorized employees into age groups: `<25`, `25–35`, `35–45`, `45–55`, `55+`.  
- Identified the predominant age group.  

**Visualizations:**  
- Bar chart showing employee counts per age group  

---

### 4. Salary Expenditure Analysis
- Calculated total salary expenditure per team and per position.  
- Identified the team and position with the highest salary costs.  

**Visualizations:**  
- Bar charts: Salary expenditure by team and by position  

---

### 5. Age–Salary Relationship
- Investigated correlation between age and salary.  
- Calculated correlation coefficient and interpreted the relationship.  

**Visualizations:**  
- Scatter plot of salary vs. age, color-coded by team and position  

**Note:** All visualizations are included and displayed within the Google Colab Notebook.  

---

## Key Insights
1. **Team Distribution:**  
   - The largest team has the highest number of employees, indicating a main operational focus.  

2. **Position Segregation:**  
   - Certain positions dominate the workforce, reflecting operational priorities.  

3. **Age Group Analysis:**  
   - Most employees fall in early- to mid-career stages, supporting career development planning.  

4. **Salary Expenditure:**  
   - Salary costs vary significantly across teams and positions, highlighting key roles and cost centers.  

5. **Age–Salary Correlation:**  
   - Correlation between age and salary is weak/moderate, suggesting that seniority partially influences compensation.  

---

## Visualization Summary
| Analysis Task | Visualization |
|---------------|---------------|
| Team Distribution | Bar chart, Pie chart |
| Position Segregation | Count plot |
| Age Group Analysis | Bar chart |
| Salary Expenditure | Bar charts by team & position |
| Age–Salary Relationship | Scatter plot with team & position markers |

---

## Conclusion
This analysis provides a detailed view of ABC Company’s workforce, highlighting:  
- Team composition and operational concentration  
- Role concentration and employee segregation  
- Age demographics and predominant groups  
- Salary distribution and major cost centers  
- Age–salary relationship  

The insights can guide workforce planning, budgeting, and HR policy decisions.

---

## Technologies & Libraries Used
- **Python** – Data processing and analysis  
- **Pandas, NumPy** – Data manipulation and preprocessing  
- **Matplotlib, Seaborn** – Data visualization  
- **Google Colab** – Execution environment and visualizations  

---

## How to Use
1. Download the dataset.  
2. Open and run in Google Colab.  
3. All analyses, visualizations, and insights will be generated automatically.

---
