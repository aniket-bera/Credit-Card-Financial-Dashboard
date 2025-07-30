# 💳 Credit Card Financial Dashboard using Power BI

Developed by **Aniket Bera**

---

## 📊 Overview

This Power BI project visualizes and analyzes **Credit Card Transaction** and **Customer** data using two interactive dashboards:

1. **Slide 1: Credit Card Transaction Report**
2. **Slide 2: Credit Card Customer Report**

The dashboards are connected to a SQL database, allowing dynamic updates when new data is pushed to the tables. This enables real-time financial insights into credit card performance, customer behavior, and revenue trends.

---

## 🧩 Features & Visuals

### 🔹 Slide 1: Credit Card Transaction Report

**Visuals:**
- 📊 *Bar Charts*:
  - Revenue by Expenditure Type
  - Revenue by Education Level
  - Revenue by Customer Job
  - Revenue by Use Chip Type
  - Customer Acquisition Cost by Card Type
- 📋 *Table*: Card Category-wise Revenue, Transaction Amount, Interest Earned, Annual Fees
- 📈 *Combo Chart*: Quarterly Revenue & Transaction Count
- 🔢 *Cards*:
  - Total Revenue
  - Total Transaction Amount
  - Total Interest
  - Number of Transactions
- 🎛 *Slicers*:
  - Quarter (Q1 - Q4)
  - Gender (Male/Female)
  - Week Start Date
  - Card Type (Platinum, Gold, Silver, Blue)
  - Salary Group (Low, Medium, High)

**DAX Queries Used:**
- `Measure AgeGroup`
- `Measure IncomeGroup`
- `Calculate WEEKNUM`
- `Calculate Current_week_Reveneue`
- `Calculate Previous_week_Reveneue`

---

### 🔹 Slide 2: Credit Card Customer Report

**Visuals:**
- 📈 *Line Chart*: Monthly Revenue vs Gender
- 📊 *Bar Charts*:
  - Age Group Distribution (Male vs Female)
  - Top 5 States
  - Salary Group (Male vs Female)
  - Marital Status (Male vs Female)
  - Dependent Count
  - Educational Level (Male vs Female)
- 📋 *Table*: Customer Job-wise Revenue, Transaction Amount, Income
- 🔢 *Cards*:
  - Total Revenue
  - Total Income
  - Total Interest
  - Average Rating
- 🎛 *Slicers*:
  - Quarter (Q1 - Q4)
  - Gender
  - Week Start Date
  - Transaction Type (Chip, Online, Swipe)
  - Card Category (Platinum, Gold, Silver, Blue)

---

## ⚙️ Project Workflow

### ✅ Step 1: Prepare Data
- Clean and format the `.csv` files for customer and transaction data.

### ✅ Step 2: Import to SQL Database
1. Create SQL tables using appropriate schema.
2. Import the `.csv` data into SQL tables using SQL Server Management Studio or similar tools.
3. Validate the data for consistency.

### ✅ Step 3: Build Power BI Dashboard
- Connect Power BI to the SQL database using DirectQuery.
- Design data models and relationships.
- Create DAX measures, slicers, visuals, and interactive filters.

### ✅ Step 4: Update with New Data
- **To refresh dashboards with new data:**
  1. Push new `.csv` data into the existing SQL tables.
  2. Power BI dashboards will automatically reflect updated metrics and visuals based on the new data.

---

## 🖼️ Dashboard Snapshots

### 📌 Slide 1: Credit Card Transaction Report
![Credit Card Transaction Report](Credit%20Card%20Financial%20Dashboard-Transaction%20Report.jpg)

### 📌 Slide 2: Credit Card Customer Report
![Credit Card Customer Report](Credit%20Card%20Financial%20Dashboard-Customer%20Report.jpg)

---

## 📞 Contact

Feel free to reach out for feedback, suggestions, or collaboration!

- 👤 **Aniket Bera**
- 📧 Email: [aniketbera.ab@gmail.com]
- 💼 LinkedIn: [https://www.linkedin.com/in/your-profile](https://www.linkedin.com/in/aniketbera/)
- 💻 GitHub: [https://github.com/your-github](https://github.com/aniket-bera)

---

> 📌 _This dashboard is a complete end-to-end BI solution combining SQL and Power BI to deliver actionable insights for credit card performance, customer segmentation, and financial KPIs._
