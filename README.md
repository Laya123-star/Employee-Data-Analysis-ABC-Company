# 📊 ABC CompanyEmployee Data Analysis Project
A Comprehensive Data Analytics & Visualization Project

## 📘 Project Overview
This project provides a comprehensive analysis of employee data from ABC Company.  
The dataset contains **458 rows and 9 columns**.
The company required a detailed, data-driven report to understand employee demographics, team distribution, salary expenditure, and workforce traits.

**Objective:**  

The project includes:

🔹 Data Preprocessing

🔹 Exploratory Data Analysis (EDA)

🔹 Five business-driven analytical tasks

🔹 Graphical visualizations

🔹 Insights & data story

🔹 Clean, reproducible Jupyter Notebook

---

 ## 📂 Dataset Description
- **Rows:** 458  
- **Columns:** 9  
- **Key Columns:**

The dataset (ABC Company.xlsx) contains the following columns:

| Column Name | Description                             |
| ----------- | --------------------------------------- |
| empid       | Employee ID                             |
| age         | Age of the employee                     |
| gender      | Gender                                  |
| height      | Height (corrected during preprocessing) |
| weight      | Weight                                  |
| team        | Team or department                      |
| position    | Job position                            |
| salary      | Monthly salary                          |
| experience  | Professional experience in years        |

---
🧹 1. Data Preprocessing

Key preprocessing steps performed:

✔ Standardized inconsistent values
✔ Removed duplicate records
✔ Treated missing values
✔ Replaced incorrect height values with random values between 150–180 cm
✔ Converted columns to appropriate data types
✔ Ensured dataset cleanliness for accurate analysis
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























Key preprocessing steps performed:

✔ Standardized inconsistent values

✔ Removed duplicate records

✔ Treated missing values

✔ Replaced incorrect height values with random values between 150–180 cm

✔ Converted columns to appropriate data types

✔ Ensured dataset cleanliness for analysis

📈 2. Analysis Tasks
🔍 Task 1: Team Distribution

Counted employees in each team

Calculated percentage share

Visualized using bar chart

🧑‍💼 Task 2: Employee Segregation by Position

Grouped employees by job role

Identified most frequent positions

🎂 Task 3: Predominant Age Group

Created age bins

Counted occurrences

Visualized using histogram

💰 Task 4: Salary Expenditure Analysis

Total salary spent per team

Total salary spent per position

Visualized using barplots

📉 Task 5: Age–Salary Correlation

Identified correlation strength

Visualized using scatter plot

🎨 Visualizations Included

The notebook contains clean, high-quality visualizations such as:

Bar Charts

Countplots

Histogram

Pie Chart

Scatter Plot

All graphs follow a consistent theme and labeling style.

🧠 Data Story – Key Insights

✔ The Marketing and Sales teams have the largest employee counts.
✔ Most employees fall within the 25–35 age group, indicating a young workforce.
✔ The Engineering team drives the highest salary expenditure due to skill-intensive roles.
✔ A mild positive correlation exists between age and salary, as expected with experience growth.
✔ Senior-level roles receive significantly higher salary allocations.

These insights help the company in:

Workforce planning

Budget allocation

Recruitment strategies

Organizational structuring

🛠 Tech Stack
Technology	Purpose
Python	Main programming language
Pandas	Data cleaning & analysis
NumPy	Numerical operations
Matplotlib / Seaborn	Data visualization
Jupyter Notebook	Development environment
