# 🪔 Diwali Sales Analysis

> Diwali Sales Analysis using Exploratory Data Analysis (EDA) with Python

## 📌 Project Overview

This project focuses on analyzing Diwali sales data using Exploratory Data Analysis (EDA) in Python.

The analysis explores customer demographics, purchasing behavior, sales amount, orders, occupations, states, and product categories to identify meaningful patterns and insights.

## 🎯 Objectives

- Understand customer purchasing behavior
- Analyze sales based on gender and age group
- Analyze sales across different states
- Understand purchasing patterns by marital status
- Analyze sales by occupation
- Identify popular product categories
- Analyze product-wise order trends
- Perform data cleaning and preprocessing
- Visualize important patterns using charts

## 🛠️ Tools & Technologies

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

## 📊 Dataset

The project uses the **Diwali Sales Data.csv** dataset.

### Dataset Features

- `User_ID` – Customer ID
- `Cust_name` – Customer name
- `Product_ID` – Product ID
- `Gender` – Customer gender
- `Age Group` – Customer age group
- `Age` – Customer age
- `Marital_Status` – Marital status
- `State` – Customer state
- `Zone` – Geographical zone
- `Occupation` – Customer occupation
- `Product_Category` – Product category
- `Orders` – Number of orders
- `Amount` – Purchase amount

## 🧹 Data Cleaning & Preprocessing

The following steps were performed:

- Checked dataset structure using `shape()` and `info()`
- Removed unnecessary columns
- Checked missing values
- Removed rows containing missing values
- Converted the `Amount` column from float to integer
- Checked column names and data types
- Used `describe()` for statistical analysis

The dataset initially contained **11,251 rows and 15 columns**. After removing two unnecessary columns and 12 rows with missing `Amount` values, the final dataset contained **11,239 rows and 13 columns**.

## 🔍 Exploratory Data Analysis

The project analyzes:

### 👥 Gender Analysis
- Customer count by gender
- Total purchase amount by gender

### 🎂 Age Analysis
- Customer distribution by age group
- Purchase behavior across age groups

### 💍 Marital Status Analysis
- Customer distribution by marital status
- Purchase amount by marital status and gender

### 📍 State Analysis
- Total sales by state
- Identification of states with higher sales and orders

### 💼 Occupation Analysis
- Customer distribution by occupation
- Purchase amount by occupation

### 🛍️ Product Category Analysis
- Customer/order distribution by product category
- Total purchase amount by product category

### 📦 Product Analysis
- Analysis of product-wise order trends
- Identification of highly ordered products

## 📈 Data Visualization

The analysis uses:

- Bar Charts
- Count Plots
- Seaborn Visualizations
- Matplotlib Charts

These visualizations help understand customer demographics, sales patterns, occupations, states, and product categories.

## 💡 Key Insights

The analysis indicates that:

- Female customers contribute a higher purchase amount than male customers.
- The **26–35 age group** shows strong purchasing activity.
- **Uttar Pradesh, Maharashtra, and Karnataka** are among the states with higher orders and sales.
- Married female customers show higher purchasing activity.
- Customers working in **IT, Healthcare, and Aviation** contribute significantly to sales.
- **Food, Clothing, and Electronics** are among the major product categories.

## 📂 Project Structure

```text
Python_Diwali_Sales_Analysis/
│
├── Diwali_sales_Analysis.ipynb
├── Diwali Sales Data.csv
└── README.md
