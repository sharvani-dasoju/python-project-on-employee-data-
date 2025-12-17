# 📊 Employee Data Analysis using Python

## 📌 Project Overview

This project demonstrates an **end-to-end employee data analysis workflow** using **Python (Pandas & NumPy)**. Multiple employee-related datasets are combined, cleaned, and analyzed to generate meaningful business insights.

This repository is ideal for:

* 📈 Data Analyst portfolio
* 🧑‍💼 HR & workforce analytics use cases
* 🐍 Demonstrating Python data wrangling skills

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Jupyter Notebook** – Development environment

---

## 📂 Input Datasets

### 1️⃣ Employee Master Data

Stores basic employee details.

**Columns:**

* `ID` – Unique employee identifier
* `Name` – Employee name
* `Gender` – Gender of employee

---

### 2️⃣ Seniority Data

Represents employee designation levels.

**Columns:**

* `ID` – Employee ID
* `Designation Level` – Seniority level (2 or 3)

---

### 3️⃣ Project Cost Data

Contains project-wise cost incurred by employees.

**Columns:**

* `ID` – Employee ID
* `Project Cost` – Cost of project assigned

---

### 4️⃣ Bonus Data

Stores bonus information.

**Columns:**

* `ID` – Employee ID
* `Bonus` – Bonus amount

---

### 5️⃣ City Data

Contains employee location details.

**Columns:**

* `ID` – Employee ID
* `City` – City name

---

## 🔄 Data Analysis Workflow

### Step 1: DataFrame Creation

All datasets are converted into Pandas DataFrames for structured processing.

---

### Step 2: Data Merging

All DataFrames are merged on the common column `ID` to create a **consolidated employee dataset**.

**Final dataset includes:**

* Employee details
* Designation level
* Project cost
* Bonus
* City

---

### Step 3: Total Project Cost Calculation

* Grouped data by `ID`
* Calculated **total project cost per employee**

This helps identify high-cost employees and resource utilization.

---

### Step 4: Conditional Analysis

✔️ **Employees with Designation Level = 2**
✔️ **Employees whose city name contains the letter "o"** (case-insensitive)

---

## 📤 Output

* 📋 Consolidated employee dataset
* 💰 Total project cost per employee
* 🔍 Filtered employee lists based on designation and city

---

## 📈 Business Insights

* Enables cost-based employee evaluation
* Helps HR teams analyze workforce distribution
* Demonstrates multi-table data integration

---

## 🎯 Key Learnings

* Data merging & joins using Pandas
* Grouping and aggregation techniques
* Conditional filtering
* Real-world HR analytics use case

---

## 🚀 Conclusion

This project showcases a **complete Python-based data analysis pipeline**, making it a strong addition to a GitHub portfolio—especially for professionals transitioning into **data analytics roles**.

---

⭐ *If you found this project helpful, feel free to fork and enhance it!*

