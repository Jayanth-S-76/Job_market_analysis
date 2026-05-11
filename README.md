# 📊 Job Market Analysis using SQL & Power BI

## 📌 Project Overview

This project analyzes the **U.S. Data Science Job Market** using real-world job posting data.
The objective was to uncover insights related to:

* Salary trends across states and job roles
* Most in-demand technical skills
* Hiring distribution by industry and company
* Impact of education on compensation
* Geographic hiring patterns across the United States

The project was completed as part of a **Data Analyst Internship Project (2026)** using **SQL, Power BI, Power Query, and DAX**.

---

# 🛠️ Tools & Technologies Used

| Tool        | Purpose                            |
| ----------- | ---------------------------------- |
| SQL         | Data extraction & initial cleaning |
| Power BI    | Dashboard creation & visualization |
| Power Query | Data transformation                |
| DAX         | KPI calculations & measures        |
| Excel/CSV   | Dataset handling                   |

---

# 📂 Dataset Information

* **Total Records:** 742 Job Postings
* **Features:** 42 Columns
* **Domain:** Data Science & Analytics Jobs
* **Region:** United States

The dataset includes:

* Job Titles
* Salary Estimates
* Company Information
* Skills Required
* Industry Details
* Education Requirements
* State & Location Data

---

# 🧹 Data Cleaning Process

## ✅ SQL Cleaning

* Removed duplicate records
* Standardized company names and state abbreviations
* Filtered incomplete job title records

## ✅ Power Query Transformations

* Replaced `-1` salary placeholders with `NULL`
* Split salary ranges into:

  * `lower_salary`
  * `upper_salary`
* Renamed columns for readability
* Removed records with missing salary information

---

# 📈 Dashboard Features

## 📄 Page 1 — Salary & Job Distribution

* KPI Cards:

  * Total Jobs
  * Total Companies
  * Total Industries
  * Average Salary
* Average Salary by State
* Salary by Job Title
* Top Industries by Job Count
* Job Distribution by State
* Top Companies Hiring
* Interactive Slicers

---

## 📄 Page 2 — Skills & Education Insights

* KPI Cards:

  * Average Company Rating
  * Most Demanded Skill
  * Highest Paying Role
  * Total States
* Salary by Degree Level
* State-wise Salary Map
* Skills Matrix by Job Title & Company

---

# 🔍 Key Insights

### 📌 Hiring & Salary Trends

* California recorded the highest number of job postings and highest salary range.
* Data Scientist was the most frequently listed role.
* Machine Learning Engineers consistently appeared among the highest-paying roles.

### 📌 Skill Demand

* Python and SQL were required in the majority of job listings.
* AWS, Spark, and Tableau emerged as valuable secondary skills.

### 📌 Industry Insights

* Biotech & Pharmaceuticals led hiring demand.
* Enterprise Software followed closely behind.

### 📌 Education Impact

* PhD holders earned significantly higher average salaries compared to roles without degree requirements.

---

# 💡 Recommendations

## For Job Seekers

* Prioritize learning:

  * Python
  * SQL
  * Power BI
* Add cloud & big-data tools like:

  * AWS
  * Spark
* Target high-opportunity states such as:

  * California
  * Massachusetts
  * New York

## For Companies

* Expand hiring beyond major tech hubs
* Improve salary transparency
* Build partnerships with universities for talent pipelines

---

# 📊 Dashboard Preview

> Add your dashboard screenshots here

Example:

```md
![Dashboard Screenshot](Screenshots/dashboard1.png)
```

---

# 📁 Project Structure

```bash
Job-Market-Analysis/
│
├── queries.sql
├── dashboard_Job_analysis.pbix
├── Job_Market_Analysis_Presentation.pptx
├── Project_Report.pdf
├── Screenshots/
└── README.md
```

---

# 🚀 How to Run the Project

1. Open `dashboard_Job_analysis.pbix` in Power BI Desktop
2. Load the dataset if required
3. Use slicers to filter by:

   * Job Title
   * State
4. Explore interactive dashboard insights

---

# 🎯 Project Outcome

This project strengthened my practical skills in:

* SQL querying
* Data cleaning
* Power BI dashboard development
* DAX calculations
* Business insight generation
* Data storytelling

The analysis clearly showed that:

> **Python, SQL, and geographic location are the biggest drivers of hiring and salary growth in the U.S. data science market.**

---

# 👨‍💻 Author

## Jayanth S

**Aspiring Data Analyst**
MBA (Finance & Marketing) | B.Com

### Skills

* SQL
* Power BI
* Excel
* DAX
* Power Query
* Data Visualization
* Data Cleaning
* Dashboard Development

---

# ⭐ If you found this project useful, consider giving it a star!
