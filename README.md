# Job_market_analysis
Project: Job Market Analysis using SQL and Power BI
Type: Data Analyst Internship Project
Year: 2026
Overview
This project analyzes job market trends across the United States for data science-related roles. Using a dataset
of 742 job postings (42 features), I extracted and cleaned the data using SQL, then built an interactive Power
BI dashboard to uncover hiring patterns, salary trends, skill demand, and the impact of education on
compensation.
1 / 8
Project_Submission_Package.md
2026-05-09
Tools Used
SQL — Data extraction and initial cleaning
Power BI — Dashboard development and visualization
Power Query — Additional data transformations within Power BI
DAX — Calculated measures for KPI metrics
Files Included
File
Description
jobs_dataset.csv
Raw/cleaned dataset used for analysis
queries.sql
All SQL queries used for extraction and aggregation
dashboard_Job_analysis.pbix
Interactive Power BI dashboard file
Job_Market_Analysis_Presentation.pptx Final presentation slides
Project_Report.pdf
Written project report
Screenshots/
How to Open
Dashboard screenshots for reference
1. Open dashboard_Job_analysis.pbix in Power BI Desktop
2. Use the slicers (Job Title, State) to filter the dashboard
3. Navigate between pages using the tabs at the bottom
4. Refer to queries.sql for the SQL logic used prior to Power BI import
📝
 PROJECT REPORT
Introduction
This project was completed as part of a Data Analyst Internship. The goal was to analyze the data science job
market across the United States using real-world job posting data. The dataset contained 742 rows and 42
columns, covering job titles, salary estimates, company details, industries, required skills, education
requirements, and location information.
The analysis was carried out using SQL for data extraction and initial cleaning, followed by Power BI for
transformation and interactive dashboard development.
Data Cleaning
The raw dataset required a few rounds of cleaning before it was ready for visualization.
In SQL:
Identified and removed duplicate records
Standardized state abbreviations and company name formatting
2 / 8
Project_Submission_Package.md
2026-05-09
Filtered out records with missing or incomplete job titles
In Power Query (Power BI):
Replaced -1 values in the salary columns with null — these were placeholder values in the original
dataset indicating "not disclosed"
Split the salary range field into separate lower_salary and upper_salary columns
Renamed columns for clarity (e.g., avg_salaryK → readable label)
Removed rows where both salary fields were null after the replacement
After cleaning, the dataset was ready for analysis without significant data loss.
Dashboard Overview
The Power BI dashboard is split into two pages:
Page 1 — Salary & Job Distribution
4 KPI cards: Total Jobs, Total Companies, Total Industries, Avg Salary
Bar chart: Avg Max and Min Salary by State
Bar chart: Salary by Job Title
Pie chart: Top 5 Industries by Job Count
Bar chart: Job Count by State
Treemap: Top 10 Companies by Job Openings
Slicers: Job Title, State
Page 2 — Skills & Education
KPI cards: Avg Rating, Most Demanded Skill, Highest Paying Role, Total States
Pie chart: Average Salary by Degree Level
Map visual: Average Salary by State
Matrix table: Skills Required by Companies for Each Job Title
Both pages are interactive — slicers on either page update all visuals simultaneously.
Key Insights
1. California dominates in both volume (98 job postings) and salary ($157K avg max).
2. Data Scientist is the most listed role, representing the largest share of postings.
3. Python and SQL are required in the overwhelming majority of listings — non-negotiable skills.
4. Biotech & Pharmaceuticals is the top hiring industry with 24 postings, ahead of Enterprise Software
(19).
5. PhD holders earn an average of $134K, compared to $101.5K for roles with no degree requirement — a
32% gap.
6. Machine Learning Engineers consistently appear in the top salary bracket across states.
7. MassMutual is the top company by job openings (8 postings), followed by Takeda Pharmaceuticals (7).
8. AWS, Spark, and Tableau form the secondary skills tier after Python and SQL.
9. Massachusetts and New York are strong hiring hubs outside of California.
3 / 8
Project_Submission_Package.md
2026-05-09
10. Company ratings average 3.72 across all postings — signaling a competitive but not exceptional
employer landscape.
Recommendations
For Job Seekers:
Focus on Python and SQL first — they appear in nearly every listing.
Target California, Massachusetts, and New York for the highest volume of opportunities.
Pursuing a Masters or PhD can meaningfully increase expected salary.
Add cloud skills (AWS) and big data tools (Spark) as secondary differentiators.
For Hiring Companies:
Expand pipelines beyond California to reduce competition and find strong talent in Virginia, Illinois, and
Maryland.
Salary transparency in job descriptions improves applicant quality.
Partnering with universities in high-concentration states (Massachusetts) can build strong talent
pipelines.
Conclusion
This project gave me hands-on experience with the full data analysis workflow — from raw database
extraction to a polished, interactive dashboard. Working with SQL helped me understand how to structure
queries for real analytical questions. Power BI and DAX taught me how to translate those queries into visual
KPIs that non-technical stakeholders can actually use.
The job market findings were clear and consistent: Python, SQL, and location (especially California) are the
biggest drivers of data science hiring and compensation in the US.
