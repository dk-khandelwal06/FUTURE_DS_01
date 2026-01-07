# 📊 Business Sales Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Domain](https://img.shields.io/badge/Domain-Data%20Science%20%26%20Analytics-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🚀 Project Overview

This project is developed as part of the **Data Science & Analytics Internship at Future Interns**.  
The objective of this task is to analyze **e-commerce sales data** and design a **professional, interactive Power BI dashboard** that helps business stakeholders understand performance, trends, and opportunities.

The dashboard focuses on **business storytelling**, enabling managers and decision-makers to take data-driven actions rather than just viewing numbers.

---

## 🎯 Business Objectives

The dashboard answers the following key business questions:

- 💰 What is the **overall revenue, profit, and order volume**?
- 📈 How do **sales and profits trend over time**?
- 🧩 Which **categories and sub-categories** drive the most revenue?
- 🌍 Which **regions and states** perform best?
- ⚖️ How does **sales compare with profit** across categories?
- 👥 Which **customer segments** contribute the most revenue?

---

## 📄 Dashboard Pages Overview

### 🔹 Page 1: Executive Sales Overview
Designed for **top-level management** to get a quick snapshot of business performance.

**Key Visuals & KPIs:**
- 📌 Total Revenue  
- 🧾 Number of Orders  
- 💵 Net Profit  
- 📦 Units Sold  
- 📊 Average Order Value (AOV)  
- 📈 Monthly Revenue Trend by Year  
- 📉 Monthly Profit Trend by Year  
- 🧩 Revenue by Sub-Category and Category  
- 🍩 Category-wise Revenue Share  
- 🌍 Regional Revenue Distribution  
- 🎛️ Year Slicer for dynamic filtering  

---

### 🔹 Page 2: Detailed Insights & Analysis
Designed for **business analysts and operations teams** for deeper insights.

**Key Visuals:**
- 🏆 Top States by Revenue  
- 👥 Revenue Contribution by Customer Segment  
- 🗺️ Geographic Distribution of Revenue (U.S.)  
- ⏱️ Revenue Trend Over Time (Daily Granularity)  

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop** – Dashboard creation & visualization  
- **Python (Pandas)** – Data cleaning & preprocessing  
- **CSV / Excel Dataset**  
- **DAX (Data Analysis Expressions)** – KPI calculations  

---

## 📐 Key DAX Measures Used

```DAX
Total Revenue = SUM(Sales[Sales])

Total Orders = DISTINCTCOUNT(Sales[Order_ID])

Net Profit = SUM(Sales[Profit])

Units Sold = SUM(Sales[Quantity])

AOV = DIVIDE([Total Revenue], [Total Orders])
```

---

## 🎨 Dashboard Design & Theme

- 🌙 Dark Mode dashboard for a premium, modern look

- 🎯 Clean and minimal layout for better readability

- 🎨 Consistent color palette across all visuals

- 📊 Focus on clarity, insights, and decision-making

---

## 📁 Repository Structure

FUTURE_DS_01/
│
├── Dataset/
│   └── FUTURE_DS_01_Dataset.csv
│
├── Dashboard/
│   └── Sales_Dashboard.pbix
│
├── Screenshots/
│   ├── Page1_Overview.png
│   └── Page2_Insights.png
│
└── README.md

---

## 🔑 Key Insights & Findings

- 📈 Revenue shows an upward trend with noticeable peaks in later months

- 🏆 Technology category generates the highest revenue

- 🌍 West region and California state are top performers

- ⚖️ Higher sales do not always guarantee higher profit

- 👥 Consumer segment contributes the largest share of revenue

---

## 🏁 Conclusion

This project demonstrates the ability to:

- Transform raw data into **actionable business insights**

- Design **executive-level dashboards**

- Apply **data analytics, visualization, and storytelling principles**

The dashboard is suitable for **real-world business decision-making** and reflects practical analytical thinking.

---

## 🙌 Acknowledgment

This project was completed as part of the
Future Interns – Data Science & Analytics Internship Program.
