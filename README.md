# Customer_Shopping_Analysis_SQL
# 🛍️ Customer Shopping Behavior Analysis
# Data Analysis (PostgreSQL)

### 📌 Project Overview
This file contains SQL queries written in PostgreSQL
to analyze customer shopping behavior across multiple
shopping malls in Istanbul, Turkey. The cleaned dataset
from Python was imported into PostgreSQL and analyzed
by answering 10 key business questions.

---

### 👩‍💻 Author
**Mehwish Nisha Khan**

---

### 🛠️ Tools Used
- **PostgreSQL** — database and querying

---

### 📂 Dataset
- **Table Name:** customers
- **Total Rows:** 99,457
- **Total Columns:** 12

---

### 📊 SQL Concepts Used
| Concept | Used In |
|---------|---------|
| GROUP BY & ORDER BY | Q1, Q2, Q3, Q4, Q5 |
| ROUND & Aggregate Functions | All Queries |
| Subqueries | Q6, Q7 |
| RANK() Window Function | Q6, Q8 |
| ROW_NUMBER() Window Function | Q10 |
| CTE (Common Table Expression) | Q9 |
| Running Total | Q9 |
| PARTITION BY | Q6, Q10 |

---

### ❓ Business Questions & Findings

**Q1. Which product category contributes the most to overall revenue?**
- 🔍 Finding: **Clothing** contributes the most to overall
revenue with a total of **113,996,791.04**

---

**Q2. Which shopping mall is the top performing location in terms of total sales?**
- 🔍 Finding: **Mall of Istanbul** is the top performing
mall with total sales of **50,872,481.68**

---

**Q3. What is the most preferred payment method among customers?**
- 🔍 Finding: **Cash** is the most preferred payment method,
followed by Credit Card and Debit Card

---

**Q4. Which gender segment drives higher purchasing power and what is their average spending?**
- 🔍 Finding: **Females** have the highest purchasing power
however their average spending of **2,525.25** is
slightly lower than males

---

**Q5. Which age group represents the most valuable customer segment based on total and average spending?**
- 🔍 Finding: **Middle Aged** customers represent the most
valuable customer segment in terms of total spending

---

**Q6. What is the top purchasing category for each gender?**
- 🔍 Finding: **Clothing** is the top purchasing category
for both Male and Female customers

---

**Q7. Which shopping mall attracts the highest number of young adult customers?**
- 🔍 Finding: **Mall of Istanbul** attracts the highest
number of Young Adult customers with **2,382** customers

---

**Q8. How do shopping malls rank against each other in terms of total revenue?**
- 🔍 Finding: **Mall of Istanbul** ranks 1st, followed
closely by **Kanyon Mall** in 2nd place

---

**Q9. What is the running total of revenue generated day by day?**
- 🔍 Finding: Running total shows consistent revenue
growth day by day across the entire period

---

**Q10. Who is the top spending customer in each age group?**
- 🔍 Finding: ROW_NUMBER() was used instead of RANK()
because multiple customers had similar revenue within
the same age group — ensuring exactly one top customer
is returned per age group

---

### 💡 Key Business Insights
- Clothing is the most dominant product category
- Mall of Istanbul is the best performing location
- Female customers are the biggest spenders overall
- Middle Aged customers are the most valuable segment
- Cash is the most preferred payment method
- Young Adults prefer Mall of Istanbul the most

---

### 🚀 Project Workflow
