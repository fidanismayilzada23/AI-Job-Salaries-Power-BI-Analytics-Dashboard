AI Job Salaries — Power BI Analytics Dashboard

This project presents an interactive Power BI dashboard that analyzes salary trends across the Artificial Intelligence job market. It aims to reveal insights related to average, minimum, maximum, and median salary levels based on job role, country, company size, education level, and experience seniority.
Additionally, month-over-month salary growth metrics are implemented using advanced DAX calculations.

_*Key Findings from the Dashboard_*
KPI	Value
Total Salary	2 bn
Maximum Salary	410K
Minimum Salary	17K
Average Salary	121.99K
Median Salary	107.26K
MoY Salary Growth	-0.02

_*Visuals in the dashboard highlight the following insights:_*

Highest-paid roles include Head of AI, Machine Learning Engineer, Research Scientist, Principal Data Scientist

PhD and Master’s degree holders earn higher salaries compared to Bachelor’s degree holders

Expert-level experience (EX) is associated with the highest salary band

Salary variation across countries shows highest figures in North America and Northern Europe

Yearly and monthly salary dynamics indicate periodic increases and seasonal drops

_*Core Analytical Visuals*_
1. Salary by Job Title (Avg / Min / Max)

-Clear comparison of salary distributions across AI roles

2.Salary by Experience Level

-EX > SE > MI > EN salary progression pattern

3.Salary by Education Level

-PhD and Master’s degrees correlate with the highest compensation

4.Salary by Company Location

-Comparison of average, max, and min salary across countries

5.Monthly & Yearly Total Salary Trend

-Shows salary market fluctuation across 2024–2025

_*DAX Measures Used in the Project*_

A full list of all 12 DAX measures used in the dashboard is available in the file below:
📌 DAX_Measures.txt 

dax_measuresDAX_Measures

Examples:

Average Salary = AVERAGE(ai_job_dataset1[salary_usd])
Median Salary = MEDIAN(ai_job_dataset1[salary_usd])
Max Salary = MAX(ai_job_dataset1[salary_usd])
Min Salary = MIN(ai_job_dataset1[salary_usd])


The key analytical metric:

MoY Salary Growth
-- Calculates month-over-month salary change in percentage by comparing
-- current month total salary against previous month total salary

📁 Repository Structure
AI-Salary-PowerBI-Dashboard
│── dashboards
│── dataset
│── exports
│── dax_measures.txt


This dashboard can be used for:

✔ AI job market salary research
✔ HR & recruitment compensation strategy
✔ Salary benchmarking by country and job title
✔ Career planning and skill-gap analysis
✔ Education-based salary comparison for workforce planning

Author

Fidan Ismayilzada
Data Analyst
🔗 LinkedIn: linkedin.com/in/fidan-ismayilzada-529104193
