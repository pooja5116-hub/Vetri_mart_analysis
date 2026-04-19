# 🛒 Vetri Mart Power BI Analytics Project

---

## 📌 Project Overview
This project presents an end-to-end Business Intelligence solution for Vetri Mart Pvt Ltd, 
a retail chain operating across Chennai and Tamil Nadu.

The solution leverages Power BI to analyze sales performance, customer behavior, 
inventory management, returns, and delivery operations to support data-driven decision-making.

<img width="1512" height="858" alt="image" src="https://github.com/user-attachments/assets/f5b5c26d-9c97-40e0-893d-af0378370772" />
---

## 🎯 Objective
The objective of this project is to transform raw transactional data into meaningful insights 
through interactive dashboards, enabling management to:
- Track business performance
- Improve customer retention
- Optimize inventory
- Reduce return losses
- Enhance operational efficiency

<img width="1525" height="836" alt="image" src="https://github.com/user-attachments/assets/42d51b6f-6d54-4475-a538-2196212d5b29" />
---

## ❗ Problem Statement
Vetri Mart lacks a centralized analytics system to monitor its operations effectively.

Key challenges include:
- Limited visibility into store-wise sales and profitability  
- Difficulty in analyzing customer behavior and retention  
- Inefficient inventory management leading to stock-outs  
- High return rates with unclear root causes  
- Delivery delays affecting customer satisfaction  

<img width="1512" height="838" alt="image" src="https://github.com/user-attachments/assets/e7d38423-c929-4b16-a94b-718af3937faa" />
---

## 📊 Dataset Description
The dataset consists of 7 tables:

- **Sales_Fact** – Main transactional data (orders, sales, profit)  
- **Customers_Dim** – Customer demographics and segmentation  
- **Products_Dim** – Product details (category, brand, pricing)  
- **Stores_Dim** – Store location and type  
- **Inventory_Fact** – Stock and restocking data  
- **Returns_Fact** – Return transactions and reasons  
- **Suppliers_Dim** – Supplier details and lead time  

---

## 🧹 Data Preparation (Power Query)
Data cleaning and transformation steps:

- Removed duplicates and cleaned text fields  
- Standardized Gender, Category, and City values  
- Converted date and numeric data types  
- Handled missing values (Profit, Delivery Date)  
- Created derived columns:
  - Delivery Days  
  - Discount Value  
- Created validation column:
  - Sales_Check (Correct / Incorrect)


<img width="1386" height="835" alt="image" src="https://github.com/user-attachments/assets/38af8b2e-d461-4a08-a78a-b4e0fa78c4ba" />
---

## 🏗 Data Modeling
- Implemented **Star Schema**
- Central table: **Sales_Fact**
- Connected dimension tables:
  - Customers, Products, Stores, Calendar
- Maintained **One-to-Many relationships**
- Created **Calendar table** for time intelligence
- Avoided many-to-many and bidirectional relationships
- Organized calculations using a **Measures Table**

<img width="1478" height="837" alt="image" src="https://github.com/user-attachments/assets/0317b8c7-f9f1-4893-96ee-9f8f61da1d6d" />
---

## 📈 Analysis (DAX Measures)
Key measures created:

- Total Sales, Total Profit, Profit Margin %  
- Total Orders, Total Quantity  
- Average Order Value  
- Sales YTD, Sales MTD, YoY Growth %  
- Return Rate %  
- SLA Compliance %  
- Customer Metrics (New vs Returning Customers)  

<img width="1551" height="728" alt="image" src="https://github.com/user-attachments/assets/f6561e23-05d7-4add-a04b-aa884d23705e" />
---

## 📊 Dashboards

### 1️⃣ Executive Overview Dashboard
- KPI Cards (Sales, Profit, Orders, Return Rate)  
- Monthly Sales Trend  
- Top Stores by Profit  
- Sales by Region  
- Category Contribution  

<img width="1270" height="713" alt="image" src="https://github.com/user-attachments/assets/8c4bb5b4-2d68-4f0a-8036-5c79130a2280" />
---

### 2️⃣ Customer Insights Dashboard
- New vs Returning Customers  
- Customer Type Contribution  
- Top Customers by Revenue  
- Avg Discount by Customer Type  
- City-wise Demand  

<img width="1277" height="722" alt="image" src="https://github.com/user-attachments/assets/8350a94c-b63e-4b09-b7d6-7d4e2771f622" />
---

### 3️⃣ Inventory & Operations Dashboard
- Stock vs Reorder Level  
- Low Stock Alerts  
- Return Reason Analysis  
- Return Rate by Category  
- Delivery SLA Compliance  
- Delayed Orders Analysis  

<img width="1267" height="712" alt="image" src="https://github.com/user-attachments/assets/f7472bbc-9d2b-41c7-86c2-3e416f268faa" />
---

## 🔍 Key Insights
- Grocery category contributes the highest revenue  
- West region shows the strongest sales performance  
- Returning customers are higher than new customers  
- Some stores have high sales but low profit margins due to discounts  
- Electronics category has higher return rates  
- Stock-out risk observed in multiple products  
- Delivery SLA compliance needs improvement  

<img width="1522" height="837" alt="image" src="https://github.com/user-attachments/assets/6678ba53-e32c-45a6-b972-59755ab40b72" />
---

## 💡 Recommendations
- Optimize discount strategies to improve profit margins  
- Improve packaging and quality checks to reduce returns  
- Focus marketing on high-performing regions and cities  
- Implement loyalty programs to retain customers  
- Improve inventory planning to avoid stock-outs  
- Enhance delivery operations to improve SLA compliance  

<img width="1462" height="831" alt="image" src="https://github.com/user-attachments/assets/cbdea09e-3559-494b-a020-25dd7d01acda" />
---

## 🛠 Tools & Technologies
- Power BI  
- Power Query  
- DAX  
- Excel  

---

## ✨ Advanced Features
- Drillthrough for detailed analysis  
- Tooltip pages for quick insights  
- Bookmarks & Buttons for navigation  
- Field Parameters for dynamic KPI switching  

---

## 🧠 Conclusion
This project demonstrates how raw business data can be transformed into 
actionable insights using Power BI.

The dashboards provide a comprehensive view of business performance and 
help stakeholders make informed decisions to improve profitability, 
customer satisfaction, and operational efficiency.

---

## 👩‍💻 Author
**Pooja L**
📧 Email: your- poojapooja515313@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/pooja-l-9975a02a9/
