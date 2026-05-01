# E-Commerce Returns Analysis (Exploratory Data Analysis)

##  Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an e-commerce dataset to understand patterns, trends, and key factors influencing product return behavior.

The goal is to transform raw, messy data into meaningful insights using data cleaning, manipulation, and visualization techniques.

---

##  Problem Statement

High return rates in e-commerce can lead to significant operational and financial losses.

This project aims to:

* Analyze return patterns across categories and regions
* Identify the impact of delivery time on returns
* Detect anomalies and inconsistencies in the dataset
* Generate insights to support better decision-making

---

##  Dataset Description

The dataset contains order-level transactional data with the following features:

* **Order_ID** → Unique order identifier
* **Category** → Product category
* **Zone** → Region of delivery
* **Amount** → Order value
* **Status** → Delivered / Returned
* **Order_Date** → Order placement date
* **Delivery_Date** → Delivery date

---

##  Data Cleaning Process

The dataset contained multiple real-world issues, which were handled as part of EDA:

*  Treated missing values using **mode and 'Unknown' imputation**
*  Standardized inconsistent values (case differences, typos)
*  Removed duplicate records based on **Order_ID**
*  Handled outliers using statistical techniques
*  Removed invalid records (negative delivery durations)

---

##  Feature Engineering

New features were created to enhance analysis:

* **Return_Flag** → Binary indicator (1 = Returned, 0 = Delivered)
* **Delivery_Days** → Number of days taken for delivery
* **Delayed** → Flag for delayed deliveries

---

##  Exploratory Data Analysis

### 🔹 Univariate Analysis

* Distribution of order amounts
* Frequency of product categories
* Delivery time distribution

### 🔹 Bivariate Analysis

* Return rate across categories
* Delivery time vs return behavior
* Relationship between order value and returns

### 🔹 Multivariate Analysis

* Combined analysis of category, region, and returns
* Impact of delivery delays across different categories
* Correlation between numerical variables

---

##  Key Insights

*  Delivery delays are strongly associated with higher return rates
*  Certain product categories exhibit consistently higher returns
*  Regional differences impact both sales and return behavior
*  Outliers in order value can significantly affect analysis
*  Data quality issues (missing, duplicates) can distort insights if not handled

---

##  Business Recommendations

* Improve delivery timelines to reduce return probability
* Focus on quality and expectations in high-return categories
* Monitor region-specific operational performance
* Implement better data validation processes

---

##  Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

##  Project Structure

```
Ecommerce-Returns-EDA/
│
├── data/
├── notebooks/
│   └── eda.ipynb
├── images/
├── README.md
```

---

##  How to Run

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook
```

---

##  Conclusion

This project demonstrates how effective EDA can uncover hidden patterns and provide actionable insights from raw data.

By analyzing delivery performance, product categories, and regional trends, businesses can take data-driven steps to reduce return rates and improve efficiency.

---



Your Name
(Data Analyst | Python | EDA)
