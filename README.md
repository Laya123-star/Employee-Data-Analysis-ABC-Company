# 📊 ABC Company Employee Data Analysis Project

![Project Banner](assets/images/banner.png)  

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-lightblue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.26-orange?logo=numpy)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab)
![Dataset](https://img.shields.io/badge/Dataset-458%20rows%209%20columns-green)

A **Comprehensive Data Analytics & Visualization Project**  

---

## 📘 Project Overview

This project provides a comprehensive analysis of employee data from **ABC Company**.  
The dataset contains **458 rows and 9 columns**.  
The company required a detailed, data-driven report to understand employee demographics, team distribution, salary expenditure, and workforce traits.

**Objective:**  

The project includes:

- 🔹 Data Preprocessing  
- 🔹 Exploratory Data Analysis (EDA)  
- 🔹 Five business-driven analytical tasks  
- 🔹 Graphical visualizations  
- 🔹 Insights & data story  
- 🔹 Clean, reproducible Jupyter Notebook  

---

## 📂 Dataset Description

| Column Name  | Description                         |
|--------------|-------------------------------------|
| empid        | Employee ID                          |
| age          | Age of the employee                  |
| gender       | Gender                               |
| height       | Height (corrected during preprocessing) |
| weight       | Weight                               |
| team         | Team or department                   |
| position     | Job position                         |
| salary       | Monthly salary                       |
| experience   | Professional experience in years    |

---

## 🧹 Preprocessing Steps

**Key preprocessing steps performed:**

- ✔ **Ensured dataset cleanliness** for accurate analysis  
- ✔ **Standardized inconsistent values** (column names to lowercase, replaced spaces with underscores)  
- ✔ **Missing Value Handling:**  
  - Numeric columns → filled with median values  
  - Categorical columns → filled with mode or `"Unknown"`  
- ✔ **Duplicate Removal**  
- ✔ **Height Column Correction:** replaced height with random integers between **150–180 cm**  

---

## 📈 Analysis Tasks

<details>
<summary>🔍 Task 1: Team Distribution</summary>

- Counted employees per team  
- Calculated percentage split  
- Identified the largest team  
- Visualized using **bar chart** and **pie chart**  

**Example Plot:**

![Team Distribution](assets/plots/team_distribution.png)

</details>

<details>
<summary>🧑‍💼 Task 2: Employee Position Segregation</summary>

- Grouped employees by job role  
- Calculated percentage split  
- Highlighted the most common roles  
- Visualized using **count plot**  

**Example Plot:**

![Position Distribution](assets/plots/position_distribution.png)

</details>

<details>
<summary>🎂 Task 3: Predominant Age Group</summary>

- Created age bins  
- Counted occurrences  
- Visualized using **bar chart**  

**Example Plot:**

![Age Group Analysis](assets/plots/age_group_analysis.png)

</details>

<details>
<summary>💰 Task 4: Salary Expenditure Analysis</summary>

- Calculated total salary spent per team and per position  
- Visualized using **bar charts**  

**Example Plot:**

![Salary Expenditure](assets/plots/salary_expenditure.png)

</details>

<details>
<summary>📉 Task 5: Age–Salary Correlation</summary>

- Calculated correlation coefficient between age and salary  
- Visualized using **scatter plot** with team and position markers  

**Example Plot:**

![Age vs Salary](assets/plots/age_salary_correlation.png)

</details>

---

## 🎨 Visualizations Included

| Analysis Task             | Visualization Type                                 |
|----------------------------|---------------------------------------------------|
| Team Distribution          | Bar chart, Pie chart                              |
| Position Segregation       | Count plot                                        |
| Age Group Analysis         | Bar chart                                         |
| Salary Expenditure         | Bar charts by team & position                     |
| Age–Salary Relationship    | Scatter plot with team & position markers        |

---

## 🧠 Data Story – Key Insights

- ✔ Majority of employees belong to the **25–35 age group**, indicating a young workforce  
- ✔ The **Engineering team** accounts for the highest salary expenditure  
- ✔ A **mild positive correlation** exists between age and salary  
- ✔ **Senior-level positions** significantly increase overall salary costs  

**Business Applications:**

- Workforce planning  
- Budget allocation  
- Recruitment strategies  
- Organizational decision-making  

---

## 🛠 Tech Stack

| Technology | Purpose                                |
|------------|----------------------------------------|
| Python     | Data processing and analysis            |
| Pandas     | Data cleaning & manipulation            |
| NumPy      | Numerical computing                     |
| Matplotlib / Seaborn | Data visualization              |
| Google Colab | Execution environment                 |

---

## 📁 Repository Structure

