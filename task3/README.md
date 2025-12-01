## Task 3 – SQL + Python Marketing Segment Report

In this task you work with a relational database. You'll import a dataset, write SQL queries, and process results further in Python.

### **Objectives**

* Import customer data into MariaDB/SQLite
* Write segmentation SQL queries
* Compute churn, average balance, and customer counts
* Pull SQL results into pandas
* Create pivot tables & charts
* Write marketing recommendations

### **Data to Download**

Bank Customer Churn dataset: [https://mavenanalytics.io/data-playground/bank-customer-churn](https://mavenanalytics.io/data-playground/bank-customer-churn)

### **Instructions**

**Import Data**

* Use `LOAD DATA INFILE`, `INSERT`, or `pandas.to_sql()`

**SQL Query Must Produce**

* number of customers per segment
* churn count & churn rate
* average balance

**Python Stage**

* Load SQL results into pandas
* Create pivot tables
* Plot churn % by segment

**Bonus Marketing Report**
Choose 2–3 segments with:

* large population
* high churn
* or high average balance

Write short justification.

### **Key Questions**

* Which segments have the highest churn?
* Which have high value but poor retention?
* Which should marketing focus on?
