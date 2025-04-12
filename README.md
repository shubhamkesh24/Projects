# 🛒 Supermarket Sales Analysis

A data analysis and visualization project focused on uncovering key insights from supermarket sales data using Python.

---

## 📌 Introduction

In this project, we explore and visualize transactional sales data from a supermarket. The goal is to discover actionable insights, identify patterns, and understand factors impacting business performance.

---

## 🧪 Data Exploration & Cleaning

### 📥 Importing the Data
- Dataset includes: `Date`, `Unit Price`, `Quantity`, `Gross Income`, `Tax`, and more.

### 📊 Initial Data Check
- Previewed the dataset using `.head()` and inspected data types and structure.

### 🔍 Data Types & Conversion
- Converted the `'Date'` column from `object` to `datetime` for time-based analysis.

### 🧹 Handling Missing Values
- `'Unit Price'`: Filled with **mean**.
- `'Quantity'`: Filled with **mode**.
- Remaining null values dropped for dataset integrity.

### 📉 Statistical Summary
- Generated descriptive statistics to understand distributions: `mean`, `median`, `std`, etc.

### 🔄 Converting Non-Numeric Columns
- Encoded categorical variables where required for numerical analysis.

### 📈 Correlation Matrix
- Visualized relationships between features using a **correlation heatmap**.

---

## 🔍 Exploratory Data Analysis (EDA)

### 🔴 Tax vs. Gross Income
- Plotted regression line to examine how `'Tax 5%'` affects `'Gross Income'`.

### 🟢 Quantity vs. Cost of Goods Sold (COGS)
- Analyzed the relationship between sales volume and COGS.

### 🔵 Unit Price vs. Gross Income
- Explored pricing impact on gross income through regression analysis.

### 📉 Rating Distribution
- Plotted histogram of customer ratings to gauge satisfaction trends.

### 🌟 Mean Rating
- Highlighted **average customer rating** using a vertical mean line.

### 📊 Histograms for All Variables
- Visualized distributions of all numerical columns to detect skewness and outliers.

---

## 🧰 Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📁 Project Structure

