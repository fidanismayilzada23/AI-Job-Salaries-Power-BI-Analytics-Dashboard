# AI Job Salaries — Power BI Analytics Dashboard

This repository contains an **interactive Power BI dashboard** that analyzes salary trends across the Artificial Intelligence job market.  
The dashboard explores **average, minimum, maximum, and median salary levels** based on job role, country, company size, education level, and experience seniority.  
In addition, **month-over-month salary growth metrics** have been implemented using advanced DAX calculations to identify salary fluctuations over time.

---

## 📌 Dashboard Insights

The visuals within the dashboard highlight the following key observations:

- Highest-paid roles include **Head of AI, Machine Learning Engineer, Research Scientist, Principal Data Scientist**
- **PhD and Master’s degree holders** earn higher salaries compared to Bachelor’s degree holders
- **Expert-level experience (EX)** corresponds to the highest salary range
- **Salary variation across countries** shows the highest compensation in **North America and Northern Europe**
- **Yearly and monthly salary dynamics** indicate **periodic increases and seasonal declines**

---

## 📊 Core Analytical Visuals

### 1️⃣ Salary by Job Title (Avg / Min / Max)
Clear comparison of salary distributions across AI-related roles.

### 2️⃣ Salary by Experience Level
EX → SE → MI → EN salary progression pattern.

### 3️⃣ Salary by Education Level
PhD and Master’s degrees correlate with the highest compensation.

### 4️⃣ Salary by Company Location
Comparison of average, max, and min salary across countries.

### 5️⃣ Monthly & Yearly Total Salary Trend
Visualizes salary market fluctuations across **2024–2025**.

---

## 🧮 DAX Measures Used in the Project

A full list of all **12 DAX measures** used in the dashboard is stored in the following file:

📄 `dax_measures.txt`

### Examples:
```DAX
Average Salary = AVERAGE(ai_job_dataset1[salary_usd])
Median Salary  = MEDIAN(ai_job_dataset1[salary_usd])
Max Salary     = MAX(ai_job_dataset1[salary_usd])
Min Salary     = MIN(ai_job_dataset1[salary_usd])
```
## 📂 Repository Structure
```
AI-Salary-PowerBI-Dashboard
│── dashboards
│── dataset
│── exports
│── dax_measures.txt
```
## 🚀 Use Cases
This dashboard can be used for:
- AI job market salary research
- HR & recruitment compensation strategy
- Salary benchmarking by country and job title
- Career planning and skill-gap analysis
- Education-based salary comparison for workforce planning
## 👤 Author
**Fidan Ismayilzada**  
Data Analyst  
🔗 LinkedIn: https://linkedin.com/in/fidan-ismayilzada-529104193
