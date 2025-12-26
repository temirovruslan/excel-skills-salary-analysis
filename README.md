# Project 2 Analysis

## Introduction

This Excel project analyzes the **data science job market** to show  
**which skills pay more**.

The analysis uses real job posting data from **2025**.


---

## 📌 Project Questions

1. Do jobs that require **more skills** pay more?
2. How do **salaries differ by region**?
3. What are the **most common skills** in data jobs?
4. Which skills are linked to **higher pay**?

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
- Loaded job and skill data from `data_salary_all.xlsx`.



#### Load
- Loaded cleaned tables into the workbook.

📊 data_jobs_all  
![2_Project_Analysis_Screenshot3.png](Images/2_Project_Analysis_Screenshot3.png)

🛠️ data_job_skills  
![2_Project_Analysis_Screenshot4.png](Images/2_Project_Analysis_Screenshot4.png)

### 📊 Analysis

Jobs requiring **more skills** tend to have **higher median salaries**,  
especially senior and technical roles.

![2_Project_Analysis_Chart1.png](Images/2_Project_Analysis_Chart1.png)

---

## 2️⃣ Salary by Region



Higher salaries are generally observed in the **United States**,  
especially for senior data roles.

![2_Project_Analysis_Chart2.png](Images/2_Project_Analysis_Chart2.png)

---

## 3️⃣ Top Skills of Data Professionals

### 🔧 Power Pivot

Job and skill tables were connected using `job_id`.

![2_Project_Analysis_Screenshot5.png](Images/2_Project_Analysis_Screenshot5.png)

Power Pivot was used to manage relationships and measures.

![2_Project_Analysis_Screenshot6.png](Images/2_Project_Analysis_Screenshot6.png)

### 📊 Analysis

**SQL and Python** are the most common skills,  
followed by cloud tools like **AWS and Azure**.

![2_Project_Analysis_Chart3.png](Images/2_Project_Analysis_Chart3.png)

---

## 4️⃣ Pay of the Top 10 Skills

### 📈 PivotChart

Median salary was compared with skill frequency.

High-value skills such as **Python, SQL, and Oracle** are linked to higher pay,  
while basic office tools show lower salaries.

![2_Project_Analysis_Chart4.png](Images/2_Project_Analysis_Chart4.png)

---

## Conclusion

This project shows that **specialized technical skills** are strongly linked to higher salaries in data jobs.  
Learning skills like **SQL, Python, and cloud technologies** can significantly improve career and salary potential.
