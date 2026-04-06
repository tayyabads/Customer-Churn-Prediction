# 📊 Churn Risk Analysis Project
## Overview

This project focuses on analyzing customer churn behavior and identifying high-risk customers using **data analysis and machine learning techniques**. The goal is to help businesses proactively take retention actions by predicting which customers are likely to churn.

The workflow includes **data preprocessing, handling class imbalance, model building in Python**, and **interactive dashboard creation in Power BI** for business insights.

---

## Objectives

* Analyze customer churn patterns
* Predict churn probability for each customer
* Identify high-risk (critical) customers
* Provide actionable insights for retention strategies
* Build an interactive dashboard for decision-making

---

## Tools & Technologies Used

### Python (Data Processing & Modeling)

* Pandas & NumPy → Data cleaning and manipulation
* Scikit-learn → Machine learning modeling
* Matplotlib / Seaborn → Exploratory Data Analysis (EDA)

### Power BI (Visualization)

* Interactive dashboard creation
* KPI tracking
* Business-level insights

---

##  Project Workflow

### 1. Data Preprocessing

* Cleaned missing and inconsistent values
* Encoded categorical variables
* Feature selection for better model performance

---

### 2. Handling Class Imbalance

The dataset had:

* **70% = No Churn**
* **30% = Churn**

This imbalance could bias the model toward predicting "No Churn".
 To address this:
* Applied **data balancing techniques (resampling methods)**
* Ensured the model learns patterns from both classes effectively

---

### 3. Model Building (Python)

* Trained classification model to predict **churn probability**
* Generated probability scores for each customer
* Categorized customers into:

  * Low Risk
  * Medium Risk
  * High Risk
  * Critical Risk

---

### 4. Power BI Dashboard 📊

After processing data in Python, the results were visualized using Power BI.

#### Key Dashboard Features:

* **Total Customers:** 7,043
* **Revenue at Risk:** 2.5M+
* **Monthly Revenue Saved:** 143K+
* **Critical Risk Customers:** 1,789

#### Visual Insights:

* Customer Risk Distribution
* Churn Risk by Contract Type
* Revenue at Risk by Internet Service
* Detailed customer-level churn probability table
---

##  Key Insights

* Month-to-month contracts show the **highest churn risk**
* Fiber optic users contribute the **highest revenue at risk**
* A significant portion of customers falls into the **critical risk category**
* Targeted retention strategies can significantly reduce churn

---

##  Retention Strategy

For high-risk customers:

* Immediate outreach
* Offer long-term contract discounts
* Personalized retention campaigns

---

## 📁 Project Structure

```bash
├── data/
├── notebooks/
├── models/
├── powerbi/
├── README.md
```

---

##  Future Improvements

* Use advanced models (XGBoost, Random Forest tuning)
* Deploy model as an API
* Automate dashboard updates
* Integrate real-time data pipeline

---

## Conclusion

This project demonstrates how combining **Python (for analytics & modeling)** and **Power BI (for visualization)** creates a powerful end-to-end solution for churn prediction and business decision-making.

---

## Contact

Feel free to connect or reach out for collaboration!
