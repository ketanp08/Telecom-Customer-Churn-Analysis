# 📉 Telecom Customer Churn Analysis Dashboard

An interactive dashboard that analyses why telecom customers leave, who is most likely to leave, and where churn is concentrated, so the business can design better retention strategies.


---

## 📌 Project Overview

Customer churn is one of the biggest revenue risks for telecom companies. Acquiring a new customer costs far more than retaining an existing one. This project analyses a dataset of **1,800 customers**, of whom **620 churned (34.44%)**, to find the main drivers of churn across contract type, internet service, tenure, age group, location and churn reason.

## 🎯 Objectives

- Calculate overall customer count, churned customers and churn rate
- Find the main reasons customers leave (churn category)
- Compare churn across internet type and contract type
- Analyse churn by age group and customer tenure
- Identify the cities with the highest churn
- Allow filtering by marital status and gender

## 📊 Dashboard Components

| Section | Description |
|---|---|
| **KPI Cards** | Total customers (1,800), churned customers (620), churn rate (34.44%) and a filtered-segment metric |
| **Slicers** | Filter by **Married** (Yes/No) and **Gender** (Female/Male) |
| **Total Churn by Churn Category** | Competitor, Attitude, Dissatisfaction, Price, Other |
| **Churn Rate by Internet Type** | Fiber Optic, Cable, DSL, None |
| **Churn Rate by Contract Type** | Month-to-Month, One Year, Two Year |
| **Churn & Churn Rate by Age Group** | Combo chart (columns + line): 0-20 up to Above 60 |
| **Churn & Churn Rate by Tenure Group** | Combo chart: 0-6 months up to Above 24 months |
| **Top 15 Cities by Total Churn** | Bar chart ranking cities by churned customers |

## 🔍 Key Insights

- **Overall churn rate is 34.44%** (620 of 1,800 customers), which is high and needs attention.
- **Contract type is the strongest driver:** 81% of churned customers were on **Month-to-Month** contracts, versus 14% on One Year and just 5% on Two Year.
- **Fiber Optic customers account for 44% of churn**, followed by Cable (27%) and DSL (20%). Customers with no internet service are only 9%.
- **Competitors are the #1 churn reason**, ahead of attitude, dissatisfaction and price.
- **New customers churn the most:** the 0-6 months tenure group has the highest churn count (~300) and rate (~58%); churn drops sharply with longer tenure.
- **Age:** churned customers are spread fairly evenly across 21-60, but the **Above 60** group has both the highest churn count (~200) and the highest churn rate (~43%).
- **San Diego (55)** and **Los Angeles (30)** are the top cities by churn, far ahead of the rest.

## 💡 Recommendations

- Offer discounts or incentives to move **Month-to-Month** customers onto 1- or 2-year contracts.
- Build an **onboarding and early-engagement programme** for the first 6 months.
- Investigate **Fiber Optic** service quality and pricing versus competitors.
- Create targeted retention plans for **senior customers (60+)**.
- Run focused campaigns in **San Diego and Los Angeles**.
- Track and counter **competitor offers** with competitive plans.

## 🛠️ Tools & Technologies

- **Microsoft Excel** – end-to-end project built entirely in Excel
- **Data cleaning & preparation:** Excel (Power Query / formulas)
- **Analysis:** PivotTables and calculated fields
- **Visualisation:** PivotCharts, combo charts (column + line) and Slicers
- **Key formula:** Churn Rate = Churned Customers ÷ Total Customers × 100

## 🧮 Metrics Defined

| Metric | Definition |
|---|---|
| Total Customers | Count of all customers in the dataset |
| Churned Customers | Customers who left the company |
| Churn Rate | Churned customers ÷ Total customers × 100 |
| Churn Rate by Segment | Churned customers in a segment ÷ total customers in that segment |

## 📁 Repository Structure

```
├── README.md
├── data/
│   └── telecom_churn_data.xlsx
├── dashboard/
│   └── Telecom_Churn_Dashboard.xlsx
└── images/
    └── dashboard.png
```

## ▶️ How to Use

1. Download the dashboard file from the `dashboard/` folder.
2. Open it in Microsoft Excel (enable editing and content so slicers work).
3. Use the **Married** and **Gender** slicers to explore segments.
4. Charts and KPIs update automatically.

## 🚀 Future Improvements

- Add monthly charges and revenue-at-risk analysis
- Predict churn with a machine learning model (logistic regression / random forest)
- Add customer lifetime value (CLV) by segment
- Add payment method and add-on services analysis

## 👤 Author

**Ketan Patil**
Data Analyst | Excel · SQL · Python · Power BI
📍 Pune, India


---

⭐ If you found this project useful, consider giving it a star!
