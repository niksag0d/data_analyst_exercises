## Task 5 – Churn Prediction Model (Machine Learning)

This task introduces predictive analytics by building a basic churn classification model using scikit‑learn. It reflects a more advanced analyst (close to data scientist) role, where the goal is to predict which customers are likely to churn and to understand the key drivers behind churn.

### **Objectives**

* Explore dataset
* Encode categorical variables
* Build churn model
* Evaluate accuracy & recall
* Generate feature importances
* Provide business summary

### **Data to Download**

Choose one dataset:

* Telco Churn (Kaggle): [https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* Bank Customer Churn: [https://mavenanalytics.io/data-playground/bank-customer-churn](https://mavenanalytics.io/data-playground/bank-customer-churn)
* Financial Churn (OpenDataBay): [https://www.opendatabay.com/data/financial/2ef80a99-467f-468f-b2dc-6851ec8d7a11](https://www.opendatabay.com/data/financial/2ef80a99-467f-468f-b2dc-6851ec8d7a11)

### **Instructions**

**Explore Dataset**

* Identify target column
* Inspect numerical & categorical features

**Clean Data**

* Handle missing values
* One‑hot encode categoricals
* Train/test split (80/20)

**Modeling**

* Train Logistic Regression or Random Forest
* Evaluate:

  * accuracy
  * recall for churn class
  * confusion matrix

**Feature Importance**

* Determine top churn predictors

**Bonus**

* Scoring function → return churn probability
* Business summary → key churn drivers + retention targets

### **Key Questions**

* Which variables best predict churn?
* How well does the model detect at‑risk customers?
* What segments should retention focus on?
