# Supply Chain Analysis

An end-to-end **Supply Chain Analysis project using Python** to identify delivery delays, operational bottlenecks, profitability patterns, and factors associated with late deliveries.

## 🎯 Objective

The overall objective of this project is to use data-driven analysis and predictive modeling to **reduce delivery delays, identify supply-chain bottlenecks, and support better operational decisions**.

## 📌 Project Overview

This project analyzes **172K+ completed orders** to understand supply-chain performance and identify opportunities to improve delivery reliability and profitability.

The analysis covers:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Delivery delay analysis
* Profitability analysis
* Regional and shipping-mode bottlenecks
* Time-based analysis
* Root-cause analysis
* Late-delivery prediction using Random Forest

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🔍 Key KPIs

| KPI                   |   Value |
| --------------------- | ------: |
| Total Orders          | 172,765 |
| Delayed Orders        |  94,523 |
| Late Delivery Rate    |  54.71% |
| On-Time Delivery Rate |  45.29% |
| 90th Percentile Delay |  3 Days |
| Profitable Orders     |  80.66% |
| Loss-Making Orders    |  18.69% |

## 📊 Key Insights

* **54.71% of orders were delayed**, making delivery reliability the biggest operational issue.
* **One-day delays were the most common**, accounting for approximately 31% of orders.
* **Shipping mode was one of the strongest differentiators** in delivery performance.
* First Class showed a **100% observed delay rate**, while Second Class was around **80%**.
* **Central Africa** had the highest regional delay rate at approximately **58.7%**.
* Customer segments showed relatively similar delay rates, suggesting they are not a major driver of delays.
* Monthly, weekday, and hourly patterns showed comparatively smaller differences.
* Around **18.7% of orders were loss-making**.

## 🤖 Machine Learning

A **Random Forest Classifier** was developed to predict late-delivery risk.

### Model Performance

* Accuracy: **74%**
* Precision: **79%**
* Recall: **75%**

The model demonstrates the potential to identify high-risk shipments before they become delayed.

## 💡 Business Recommendations

1. Investigate the poor performance of **First Class and Second Class shipping**.
2. Develop a **high-risk shipment alert system** using the prediction model.
3. Focus on reducing the large volume of **one-day delays**.
4. Create region-specific logistics strategies, particularly for **Central Africa**.
5. Investigate payment-review and payment-related operational bottlenecks.
6. Analyze **Region × Shipping Mode** combinations to identify high-risk routes.
7. Combine delivery-risk predictions with profitability when selecting shipping options.
8. Use more realistic delivery promises based on historical operational performance.

```

**If you found this project useful, feel free to star the repository. 😊**

**Vachaspati Mishra**
