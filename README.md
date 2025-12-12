# 📊 ABC Company Employee Data Analysis Project

A **Comprehensive Data Analytics & Visualization Project**.

---

## 📘 Project Overview

- This project provides a comprehensive analysis of employee data from **ABC Company**.  
- The dataset contains **458 rows and 9 columns**.  
- The company required a detailed, data-driven report to understand employee demographics, team distribution, salary expenditure, and workforce traits.

**🎯 Objective:**  

The project includes:

 🔹 Data Preprocessing.
 
 🔹 Exploratory Data Analysis (EDA).
 
 🔹 Five business-driven analytical tasks.
 
 🔹 Graphical visualizations.
 
 🔹 Insights & data story.
 
 🔹 Clean, reproducible Google collab.

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

✔ **Ensured dataset cleanliness for accurate analysis:**  
Verified that all data was consistent, error-free, and properly structured.

✔ **Standardized column names:**  
Converted all column names to lowercase and replaced spaces with underscores.

✔ **Missing Value Handling:**  
- **Numeric columns:** Filled using median values.  
- **Categorical columns:** Filled using mode or `"Unknown"` where appropriate.

✔ **Duplicate Removal:**  
Identified and removed duplicate rows from the dataset.

✔ **Height Column Correction:**  
Replaced the `height` column with random integers between **150–180 cm** to maintain consistency.

---
## 📈 Analysis Tasks

### 🔍 Task 1: Team Distribution
- Counted employees per team.
- Calculated percentage split.  
- Identified the largest team.  
- Visualized using **bar chart** and **pie chart**.  

### 🧑‍💼 Task 2: Employee Position Segregation
- Grouped employees by job role.  
- Calculated percentage split.  
- Highlighted the most common roles.  
- Visualized using **count plot**.  

### 🎂 Task 3: Predominant Age Group
- Created age bins.  
- Counted occurrences.  
- Visualized using **bar chart**.  

### 💰 Task 4: Salary Expenditure Analysis
- Calculated total salary spent per team and per position.  
- Visualized using **Grouped bar charts**.  

### 📉 Task 5: Age–Salary Correlation
- Calculated correlation coefficient between age and salary.  
- Visualized using **scatter plot** with team and position markers.  

---

## 🎨 Visualizations Included

| Analysis Task             | Visualization Type                                 |
|----------------------------|---------------------------------------------------|
| Team Distribution          | Bar chart, Pie chart                              |
| Position Segregation       | Count plot                                        |
| Age Group Analysis         | Bar chart                                         |
| Salary Expenditure         | Bar charts by team & position                     |
| Age–Salary Relationship    | Scatter plot with team & position markers        |

All graphs follow a consistent **theme, color palette, and labeling**.

---

## 🧠 Data Story – Key Insights

- ✔ Majority of employees belong to the **25–35 age group**, indicating a young workforce.  
- ✔ The **Engineering team** accounts for the highest salary expenditure.  
- ✔ A **mild positive correlation** exists between age and salary.  
- ✔ **Senior-level positions** significantly increase overall salary costs.  

**Business Applications:**

- Workforce planning.  
- Budget allocation.  
- Recruitment strategies.  
- Organizational decision-making.  

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

ABC-Company-Employee-Analysis/


├── 📄 ABC Company.xlsx # Dataset

├── 📄 Python Module End Assessment 2.ipynb # Final notebook

├── 📄 README.md # Project documentation

---

## 🚀 How to Use

1. Download the dataset.  
2. Open the notebook in **Google Colab**.  
3. Run all cells to generate analyses, visualizations, and insights automatically.

