# 📊 Superstore Sales Analysis

## 📌 Introduction
This project analyzes sales and profit data from a retail superstore.  
The goal is to uncover **business insights** such as:
- Which product categories drive the most sales?
- Which regions are most profitable?
- Who are the top customers?
- How do sales trends change over time?

---

## 📂 Dataset
- **File:** Sample - Superstore.csv  
- **Rows:** ~9,994  
- **Columns:** 21  
- **Main Fields:** Order Date, Ship Mode, Category, Sub-Category, Sales, Profit, Region, Customer Name  

---

## 🔧 Data Cleaning
Steps performed:
1. Loaded dataset with correct encoding (`latin1`)
2. Converted `Order Date` to datetime format
3. Removed duplicates
4. Checked and handled missing values
5. Saved cleaned dataset as `Cleaned_Superstore.csv`

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Which categories bring the most sales?
📌 **Insight:** Technology has the highest sales, followed by Furniture and Office Supplies.

### 2. Which regions are most profitable?
📌 **Insight:** The West region contributes the highest profit, while the South region shows weaker profits.

### 3. Who are the top customers?
📌 **Insight:** A small number of customers contribute to a large share of sales.

---

## 📈 Visualizations

### Monthly Sales Trend
![Monthly Sales Trend](screenshots/monthly_sales.png)

### Sales by Category
![Sales by Category](screenshots/category_sales.png)

### Profit by Region
![Profit by Region](screenshots/profit_region.png)

---

## ✅ Conclusion
- Focus marketing efforts on **Technology products** (highest revenue driver).  
- Address profit leakages in **low-performing regions**.  
- Retain and reward **top customers** via loyalty programs.  
- Plan inventory and promotions around **seasonal sales spikes**.  

---

## 🛠️ Tools Used
- Python (Pandas, Matplotlib, Seaborn)  
- Jupyter/Google Colab  
- GitHub for version control  

---

## 📌 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/Srinidhi-200304/Superstore-Sales-Analysis.git
# Superstore-Sales-Analysis
Data analysis project using Python to uncover insights from retail sales data (Superstore dataset).
