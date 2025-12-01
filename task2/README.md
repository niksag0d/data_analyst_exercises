## Task 2 – E-commerce Data Cleaning & Ad Hoc Analysis

This task simulates real-world messy e-commerce transaction data. The goal is to clean the dataset and produce key sales insights.

### **Objectives**

* Load CSV data
* Identify missing/invalid values
* Remove invalid rows
* Create revenue column
* Compute top products & top countries
* Create monthly revenue trends
* Visualize time series

### **Data to Download**

UCI Online Retail dataset: [https://archive.ics.uci.edu/dataset/352/online%2Bretail](https://archive.ics.uci.edu/dataset/352/online%2Bretail)

### **Instructions**

**Inspect Dirty Data**

* Count missing values per column
* Check if `Quantity` or `UnitPrice` ≤ 0

**Clean Data**

* Remove rows missing `CustomerID`
* Remove rows with invalid Quantity/UnitPrice
* Create new column: `Revenue = Quantity * UnitPrice`

**Sales Analysis**

* Total revenue
* Top‑10 products by revenue
* Top‑10 countries by revenue

**Bonus**

* Convert `InvoiceDate` → datetime
* Create monthly revenue (groupby year/month)
* Plot monthly revenue time series

### **Key Questions**

* Which products generate the most revenue?
* Which countries are most valuable?
* How do monthly sales evolve?
