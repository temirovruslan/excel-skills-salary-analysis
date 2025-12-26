# Project 2 Analysis

## Introduction

This Excel project looks at the **data science job market**.  
The goal is simple: understand **which skills are paid better** and **why**.

The analysis is based on real job postings from **2025**.

---

## 📌 Project Questions

In this project, I focus on four questions:

1. Do jobs that ask for **more skills** usually pay more?
2. How do **salaries change by country or region**?
3. What skills appear **most often** in data jobs?
4. Which skills are connected to **higher salaries**?

---

## 🛠 Excel Skills Used

- Pivot Tables  
- Pivot Charts  
- DAX  
- Power Query  
- Power Pivot  

---

## 1️⃣ Do More Skills Lead to Higher Pay?

### 🔍 Power Query (ETL)

#### Extract
- Job and skill data was loaded from `data_salary_all.xlsx`.

#### Load
- Cleaned tables were loaded into the workbook.

📊 data_jobs_all  
![2_Project_Analysis_Screenshot3.png](Images/2_Project_Analysis_Screenshot3.png)

🛠️ data_job_skills  
![2_Project_Analysis_Screenshot4.png](Images/2_Project_Analysis_Screenshot4.png)

### 📊 Analysis

Jobs that require **more skills** usually show **higher median salaries**.  
This is especially clear for senior and technical roles.

![2_Project_Analysis_Chart1.png](Images/2_Project_Analysis_Chart1.png)

---

## 2️⃣ Salary by Region

Salaries are generally **higher in the United States**,  
especially for senior data positions.

![2_Project_Analysis_Chart2.png](Images/2_Project_Analysis_Chart2.png)

---

## 3️⃣ Top Skills of Data Professionals

### 🔧 Power Pivot

Job and skill tables were connected using `job_id`.

![2_Project_Analysis_Screenshot5.png](Images/2_Project_Analysis_Screenshot5.png)

Power Pivot was used to manage table relationships and calculations.

![2_Project_Analysis_Screenshot6.png](Images/2_Project_Analysis_Screenshot6.png)

### 📊 Analysis

**SQL and Python** appear most often in data jobs.  
Cloud tools like **AWS and Azure** are also very common.

![2_Project_Analysis_Chart3.png](Images/2_Project_Analysis_Chart3.png)

---

## 4️⃣ Pay of the Top 10 Skills

### 📈 PivotChart

Median salary was compared with how often each skill appears.

Skills like **Python, SQL, and Oracle** are linked to higher pay,  
while basic office tools are linked to lower salaries.

![2_Project_Analysis_Chart4.png](Images/2_Project_Analysis_Chart4.png)

---

## Conclusion

This project shows that **technical and specialized skills** matter a lot in data jobs.  
Learning skills like **SQL, Python, and cloud tools** can help you earn more and grow faster in your career.
