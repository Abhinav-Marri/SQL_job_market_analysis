# SQL Job Market Analysis

A **PostgreSQL-based data analysis project** that explores a real-world **job postings dataset** to identify hiring trends, role demand, skill demand, and time-based market patterns using advanced SQL queries.

This project is inspired by and extends the analysis presented in  
👉 [Luke Barousse – SQL Job Market Analysis Project (YouTube)](https://www.youtube.com/watch?v=7mz73uXD9DA)

---

## 📌 Tech Stack
- **Database:** PostgreSQL  
- **Languages:** SQL  
- **Dataset:** Job Postings Dataset  
  - Source: [Luke Barousse](https://www.lukebarousse.com/)  

---

## 📊 Project Objectives
This project answers key questions about the job market and provides a brief analysis on the obtained results.

---

## ❓ Questions Answered & Insights

---

### 1️⃣ What are the high-paying jobs posted in the first quarter?
This analysis filters job postings from **Q1 (January–March)** and identifies roles with the highest average annual salaries.  
It highlights seasonal hiring trends and compensation patterns early in the year.

---

### 2️⃣ What are the top-paying Cloud Engineer jobs?

#### 🔍 Analysis
- **Russia ($280,000)** appears as the highest-paying Cloud Engineer role in the dataset.
- Multiple listings are marked **“Anywhere”**, offering salaries between **$180K–$204K**.
- This indicates that **remote Cloud Engineer roles can compete with or exceed traditional tech hubs**.

#### 📈 Visualization
<img width="989" height="590" alt="Top Paying Cloud Engineer Jobs by Location" src="https://github.com/user-attachments/assets/8d80e212-239d-4dd1-b925-48370c2e9a58" />

---

### 3️⃣ What skills are most in demand for Cloud Engineers?

#### 🔍 Analysis
- **Core programming and cloud platforms dominate demand.**
- **Python (3126 postings)** is the most in-demand skill:
  - Widely used for automation, DevOps, scripting, and cloud-native development.
- **AWS (3081)** and **Azure (2951)** closely follow:
  - Indicates strong demand across **multiple cloud ecosystems**.
  - Being **multi-cloud capable** is a major advantage.

#### 📈 Visualization
<img width="985" height="590" alt="Top In-Demand Cloud Engineer Skills" src="https://github.com/user-attachments/assets/2dbda82f-715a-4184-99b5-03b2b84ea1df" />

---

### 4️⃣ Which Cloud Engineering skills are associated with higher salaries?

#### 📋 Results
| Skill    | Average Salary (USD) |
|----------|----------------------|
| Rust     | $221,844.00          |
| Outlook  | $195,000.00          |
| C++      | $186,832.33          |
| Splunk  | $182,500.00          |
| Swift   | $180,000.00          |
| MATLAB  | $157,650.00          |
| GitHub  | $154,800.00          |
| MongoDB | $150,342.86          |
| Go      | $145,933.60          |
| Looker  | $137,283.33          |

#### 🔍 Analysis
- High salaries are linked to **skill scarcity and system complexity**, not just popularity.
- **Low-level programming (Rust, C++)**, **observability tools (Splunk)**, and **niche technologies** command premium pay.
- Combining **core cloud skills** with **specialized expertise** significantly boosts earning potential.

---

### 5️⃣ What are the most optimal skills to learn?

*(Balancing demand and salary)*

#### 📋 Results
| Skill       | Demand Count | Average Salary (USD) |
|-------------|--------------|----------------------|
| SQL         | 16           | $128,677.75          |
| Python      | 29           | $111,593.72          |
| NoSQL       | 1            | $79,200.00           |
| Scala       | 4            | $92,600.00           |
| Java        | 6            | $135,925.00          |
| R           | 2            | $107,825.25          |
| Shell       | 1            | $90,000.00           |
| Go          | 5            | $145,933.60          |
| JavaScript  | 7            | $133,924.00          |
| Bash        | 3            | $89,400.00           |

#### 🔍 Analysis
- **Python** has the highest demand but only moderate average salary.
- **SQL** combines strong demand with solid pay.
- High-demand skills are **essential but not differentiators**.
- **Lower-demand, specialized skills (Go, Java)** correlate with **higher salaries**.
- The optimal strategy is to **pair foundational skills with niche or system-level expertise**.

---

## 📌 Key Takeaways
- Cloud Engineer compensation is driven more by **specialization** than raw demand.
- **Remote roles** offer competitive salaries comparable to major tech hubs.
- A strong skill profile combines:
  - Core skills (Python, SQL, Cloud Platforms)
  - Specialized tools and languages (Go, Rust, Observability tools)

---

## 🚀 Future Improvements
- Skill demand vs salary scatter plots
- Company-wise salary analysis
- Regional comparisons
- Query optimization and indexing analysis

---

## 📎 References
- Luke Barousse Dataset & Project  
  - Website: https://www.lukebarousse.com/  
  - YouTube: https://www.youtube.com/watch?v=7mz73uXD9DA
