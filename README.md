# 🛒 Amazon Product Sales Analysis

## 📘 Introduction
This project focuses on analyzing **Amazon product sales data** to uncover key **trends, customer behavior, and product performance**.  
By applying **data cleaning**, **feature engineering**, and **visualization** techniques, it provides **actionable insights** that empower data-driven decision-making in the e-commerce domain.

---

## 🏢 Business Context
E-commerce platforms like **Amazon** generate vast amounts of sales and operational data every day.  
Analyzing this data enables businesses to:

- 📦 Identify **top-performing products** and **categories**  
- 📅 Detect **seasonal demand patterns**  
- 👥 Understand **customer preferences** and **regional sales performance**  
- 💰 Optimize **pricing, inventory, and marketing** strategies  

By leveraging such insights, sellers can **maximize profitability**, **reduce inefficiencies**, and **improve customer satisfaction** across marketplaces.

---

## 📊 Dataset Description
The dataset contains **order-level transaction data** with attributes such as:

- **Order Details:** Order ID, Order Date  
- **Product Info:** SKU, Product Category  
- **Sales Metrics:** Quantity (Qty), Revenue (Amount)  
- **Logistics:** Courier Status, Fulfillment Type  
- **Sales Channel:** Amazon, Flipkart, etc.  
- **Customer Info:** Region, Shipping Details  

---

## 🧮 Additional Feature Engineering
To enhance the quality and depth of analysis, the following **derived metrics** were created:

| Metric | Description |
|--------|--------------|
| 💰 **Revenue_per_Product** | Total revenue contribution per product |
| 📦 **Average_Sales_per_Order** | Average order quantity per transaction |
| 📈 **Total_Quantity_Sold** | Total units sold per SKU |
| 💹 **Profit_Proxy** | Estimated profitability indicator |
| 🔢 **Profit_Margin_Proxy** | Ratio-based profit margin measure |

---

## ⚙️ Methods & Data Preparation

### 1️⃣ Data Cleaning
- Removed duplicates and unnecessary columns  
- Handled missing values using **median** (numeric) and **mode** (categorical)  
- Standardized column names and formats (dates, currency, categories)  

### 2️⃣ Feature Engineering
- Generated **new calculated metrics** (revenue, profit proxies, quantity totals)  
- Aggregated data at multiple levels — **product**, **category**, and **region**  
- Created summary tables to support visual analytics  

### 3️⃣ Exploratory Data Analysis (EDA)
- Conducted **correlation and trend analysis** to reveal business insights  
- Examined **seasonal patterns**, **regional variations**, and **sales drivers**

---

## 📈 Key Visualizations & Insights

### 🏆 Top Products & Categories  
Bar and lollipop charts showing which products and categories drive the most revenue.

### 📅 Sales Trends Over Time  
Line plots illustrating **daily**, **monthly**, and **quarterly** performance trends.

### 🌍 Domestic vs. International Revenue  
Pie charts and treemaps visualizing global sales distribution and market reach.

### 🗺️ Regional Analysis  
State-wise and city-level heatmaps highlighting **high-performing zones** and **customer clusters**.

### 🔥 Correlation Heatmaps  
Visual exploration of **relationships between sales, revenue, and profitability** metrics.

---

## 🖼️ Sample Insights & Dashboards
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/1.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/2.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/3.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/4.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/5.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/6.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/7.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/8.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/9.png)
![image alt](https://github.com/OmPatil2806/Products-Sales-Analysis/blob/main/10.png)
## 🛠 Tech Stack

| Component | Tools Used |
|------------|-------------|
| **Language** | Python 🐍 |
| **Libraries** | pandas, NumPy, Matplotlib, Seaborn, Plotly |
| **Visualization Tools** | Matplotlib, Plotly, Seaborn |
| **Environment** | Jupyter Notebook / PyCharm |
| **Task Type** | Exploratory Data Analysis & Visualization |

---

## 💡 Business Value
- Enables **data-driven pricing, inventory, and marketing** strategies.  
- Helps identify **high-value products**, **sales channels**, and **regions**.  
- Empowers e-commerce teams to **forecast trends** and **allocate resources efficiently**.  

---

## 🚀 Future Enhancements
🔹 Integrate **machine learning models** for demand forecasting and price optimization.  
🔹 Develop an **interactive Streamlit dashboard** for real-time sales tracking.  
🔹 Incorporate **live API data** from marketplaces for up-to-date analysis.  
🔹 Add **customer segmentation models** for personalized marketing insights.  

---

## 👨‍💻 Author: Om Patil
💡 **Data Science & Machine Learning Enthusiast**  
🔗 [Connect on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)



