# DataScienceCourse4_Assignment1
**Netflix Originals Data Exploration and Analysis — DS PGC Course 4 Assignment 1**

---

## 📘 Assignment Overview
Analyze the **Netflix Originals** dataset to extract insights about genres, runtime, IMDb scores, languages, and premiere dates using SQL queries.  
The assignment contains 10 tasks covering filtering, aggregation, sorting, date handling, and schema constraints.

---

## 🧩 Tasks (summary)
1. Retrieve originals with `IMDBScore > 7`, `Runtime > 100`, language `English` or `Spanish`.  
2. Count titles per language and show languages with > 5 titles.  
3. Top 3 longest Hindi movies sorted by IMDb score (desc).  
4. Titles containing `"House"` with `IMDBScore > 6`.  
5. Originals released between 2018–2020 in `English`, `Spanish`, or `Hindi`.  
6. Movies with `Runtime < 60` OR `IMDBScore < 5`, sorted by `Premiere_Date`.  
7. Average IMDb score per genre where genre has at least 10 movies.  
8. Top 5 most common runtimes.  
9. Titles released in 2020 grouped by language with counts.  
10. Create a table enforcing `IMDBScore BETWEEN 0 AND 10` and `Runtime > 30`.

---

## 🧰 Tools & Approach
- Tool: **MySQL / MariaDB** (or any SQL engine that supports `CHECK` constraints and date functions).  
- Approach: clean/convert date strings to `DATE`, use `WHERE`, `GROUP BY … HAVING`, `ORDER BY`, `LIMIT`, `COUNT`, `AVG`, `CREATE TABLE … CHECK`, and `STR_TO_DATE()` where needed.  
- Deliverables: SQL script / .sql file (queries for all tasks) and a short notes file explaining assumptions.

---

## 📂 Files included
- `DataScienceCourse4Assignment1Question.pdf` — assignment brief.  
- `DataScienceCourse4Assignment1Solution.pdf` — solution file with all SQL queries and notes.

---

## 🧭 How to review
1. Download the solution PDF and open it.  
2. Copy each query into your SQL client (MySQL Workbench / phpMyAdmin / DBeaver).  
3. Run queries against the `Netflix_Originals` table (adjust date parsing if needed).  
4. Verify results match the assignment requirements.

---

## 👤 Author
**Utkarsh Anand** — DS PGC Course 4
