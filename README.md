# Sales Insights Dashboard — Power BI + SQL (AtliQ Hardware)

A business-focused **Sales Analytics dashboard** built using **Power BI + MySQL**, designed to help leadership track revenue, profit, customer performance, and regional trends using real-world sales data from **AtliQ Hardware**.

This project converts raw transactional data into **interactive visuals + KPI reporting**, enabling faster decision-making and reducing dependency on Excel-based reporting.

---

## 📌 Problem Statement
AtliQ Hardware supplies computer hardware & peripherals across multiple branches in India.  
The Sales Director struggled to track performance due to:

- Declining sales trends
- Manual reporting delays from regional teams
- Excel-heavy data that was hard to interpret quickly

---

## ✅ Solution
Built an end-to-end **Sales Insights Dashboard** in Power BI by pulling data from a **MySQL database**, cleaning it in Power Query, and creating KPI-driven reports with DAX measures.

The dashboard enables stakeholders to:
- Track revenue + profit trends
- Compare market-wise performance
- Identify loss-making regions
- Monitor top customers and products
- Improve data-driven strategy execution

---

## 📊 Key Dashboard Insights
- Total Revenue (4 Years): **₹985M**
- Total Profit Margin: **₹24.7M**
- Profit Margin %: **2.5%**
- Sales Quantity: **₹2M**
- 2020 Revenue: **₹142M** | Sales Qty: **350K** | Profit: **₹2.1M**
- **Delhi NCR** contributed **52.8% of revenue (₹520M)** but only **2.3% profit margin**
- **Bhubaneshwar** showed highest profit margin in 2020: **10.48%**
- **Bengaluru** had lowest profit margin: **-20.8%**
- Top Customer: **Electricalsara Stores (₹413M revenue)**
- Top Product: **Prod318 (₹69M revenue)**

---

## 🧠 Approach (Workflow)
1. Project planning using **AIMS Grid**
2. Extracted data using **MySQL queries**
3. Loaded dataset into Power BI
4. Cleaned & transformed data in **Power Query**
5. Performed ETL: Extract → Transform → Load
6. Created DAX measures for KPIs
7. Standardized multi-currency transactions via conversion logic
8. Data validation checks
9. Data modeling + dashboard build

---

## 🛠 Tech Stack
- **Power BI** (Dashboarding + DAX)
- **MySQL / SQL** (Data extraction + analysis queries)
- **Power Query** (Data cleaning + transformation)
- **ETL + Data Modeling**
- **AIMS Grid** (Project planning)

---

## 🔧 Major Customizations Implemented
- Fixed the **(blank)** products issue by replacing the products table with a **self-modified products mapping**
- Extended transaction table with extra columns such as:
  - Profit margin
  - Cost price
  - Profitability metrics
- Performed **currency normalization** where multiple currencies existed in transactions

---

## 📂 Repository Structure
├── db_dump_version_2.sql
├── sales_insight.sql
├── Atliq-sales insight project.pbix
├── Sales Insights PowerBI Dashboard - Atliq.pdf



## Final result 

#### Dashboard KPI Page

-------
 <img src="https://github.com/NotRamm/Sales-Insight-Dashboard-using-Power-BI/blob/master/Screenshots/Sales%20Insight%20-%20Page%20KPI.png" class="center">
 
 #### Dashboard Performance Insights

-------
 <img src="https://github.com/NotRamm/Sales-Insight-Dashboard-using-Power-BI/blob/master/Screenshots/Sales%20Insight%20-%20Page%20Performance%20Insights.png" class="center">
 

 #### Dashboard Profit Analysis
 
 -----------
 
  <img src="https://github.com/NotRamm/Sales-Insight-Dashboard-using-Power-BI/blob/master/Screenshots/Sales%20Insight%20-%20Page%20Profit%20Analysis.png" class="center">





