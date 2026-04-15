# 🛒 Grocery Demand & Operations Analysis

## 📌 Project Overview

This project focuses on analyzing grocery order data to uncover demand patterns, customer behavior, and operational inefficiencies in a delivery-based system.

The goal is to use **SQL-based data analysis** to generate actionable insights that can improve business performance, optimize delivery operations, and enhance customer experience.

---

## 🎯 Objectives

* Identify top-selling products and revenue drivers
* Analyze peak order times and demand patterns
* Evaluate delivery performance across cities
* Measure cancellation rates and detect problem areas
* Generate business insights to improve operations

---

## 🛠 Tools & Technologies

* SQL (SQLite)
* Excel (for basic data viewing)

---

## 📂 Dataset Description

The dataset contains grocery order-level data with the following fields:

| Column Name   | Description                        |
| ------------- | ---------------------------------- |
| order_id      | Unique order identifier            |
| product_name  | Name of the product                |
| category      | Product category                   |
| price         | Price per unit                     |
| quantity      | Quantity ordered                   |
| order_time    | Time when order was placed         |
| delivery_time | Time when order was delivered      |
| city          | Order location                     |
| status        | Order status (delivered/cancelled) |

---

## 📊 Key Analysis Performed

### 1. Revenue Analysis

* Total revenue calculation
* Top products by revenue
* Category-wise revenue contribution

### 2. Demand Analysis

* Frequently ordered products
* Order distribution across cities

### 3. Time-Based Analysis

* Peak order hours
* Daily revenue trends

### 4. Operations Analysis

* Average delivery time
* City-wise delivery performance
* Delivery delay classification

### 5. Cancellation Analysis

* Cancellation rate by city
* Most cancelled products

---

## 🔍 Key Insights

* Peak order demand occurs during evening hours (6 PM – 9 PM), indicating high customer activity during this period
* Certain cities exhibit higher delivery times, suggesting logistical inefficiencies
* A small number of products contribute significantly to total revenue
* High cancellation rates for specific products may indicate stock or supply issues
* Delivery delays are a key operational challenge affecting customer experience

---

## 💡 Business Recommendations

* Increase delivery workforce during peak hours to reduce delays
* Improve warehouse and logistics management in high-delay cities
* Maintain higher inventory levels for fast-moving products
* Investigate causes of high cancellation rates and address supply issues
* Implement better routing or dispatch systems to optimize delivery time

---

## 📁 Project Structure

```
grocery-demand-analysis/
│
├── data/
│   └── orders.csv
│
├── sql/
│   └── analysis.sql
│
├── README.md
```

---

## 🚀 How to Use This Project

1. Load the dataset (`orders.csv`) into SQLite
2. Execute queries from `analysis.sql`
3. Analyze results to derive insights

---

## 📈 Outcome

This project demonstrates how **SQL can be used to solve real-world business problems** by analyzing data and generating actionable insights for improving operations and decision-making.

---

## 🙌 Future Improvements

* Build an interactive dashboard (React / Power BI)
* Add predictive analysis for demand forecasting
* Incorporate real-time data processing

---



