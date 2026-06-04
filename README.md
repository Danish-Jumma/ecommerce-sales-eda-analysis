# 📊 E-Commerce Sales Data Analysis (EDA Project)

This project focuses on exploratory data analysis (EDA) of an e-commerce dataset containing product listings, prices, discounts, and sales information. The goal is to extract meaningful insights about pricing strategy, sales behavior, and product performance.

---

## 📌 Project Objectives

- Analyze best-selling products
- Understand relationship between price and sales
- Evaluate impact of discount on sales
- Identify market trends in product listings
- Clean and preprocess real-world messy dataset

---

## 📂 Dataset Overview

The dataset contains the following features:

- Product title
- Product URL
- Price
- Discount percentage
- Number of units sold
- Ranking information
- Category/subcategory details

⚠️ The dataset was messy and required significant cleaning:
- Missing values
- Mixed formats (currency symbols, text labels)
- Inconsistent product titles
- Null-heavy columns

---

## 🧹 Data Cleaning Steps

- Removed irrelevant/empty columns
- Handled missing values using imputation
- Converted price and discount into numeric format
- Extracted numeric values from sales text
- Standardized product titles
- Removed incomplete rows

---

## 📊 Exploratory Data Analysis

### 1. Best Selling Products
Identified top-performing products based on sales volume.

### 2. Price vs Sales Relationship
Analyzed correlation between product price and number of units sold.

### 3. Discount Impact
Studied how discount percentage affects product sales.

### 4. Segment Analysis
Grouped products by:
- Price range
- Discount range  
to understand customer buying behavior.

---

## 📈 Key Insights

- Lower-priced products generally have higher sales volume
- Discounts moderately influence purchasing behavior
- Extremely high discounts do not always guarantee higher sales
- Market shows strong price sensitivity

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📊 Visualizations

The project includes:
- Bar charts (top-selling products)
- Scatter plots (price vs sales)
- Correlation heatmaps
- Group-based comparisons

---

## 🚀 How to Run This Project

```bash
git clone https://github.com/your-username/ecommerce-sales-eda-analysis.git
cd ecommerce-sales-eda-analysis
pip install -r requirements.txt
jupyter notebook
