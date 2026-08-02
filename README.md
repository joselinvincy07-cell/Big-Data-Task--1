# 🛒 Task 1 - Big Data Analytics (Sample Superstore Analysis)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the **Sample Superstore** dataset using Python. The objective is to understand sales performance, clean the dataset, create new features, and visualize important business insights.

---

## 🎯 Objectives

- Load and explore the Superstore dataset.
- Perform data cleaning and preprocessing.
- Convert date columns into DateTime format.
- Calculate delivery time for each order.
- Check for missing values.
- Analyze total sales by category.
- Visualize sales distribution.

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📂 Dataset

**Dataset Name:** Sample Superstore

The dataset contains information about:
- Orders
- Customers
- Products
- Sales
- Profit
- Shipping Details

---

## 📋 Steps Performed

### 1. Import Libraries
Imported the required Python libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn

### 2. Load Dataset
Loaded the Sample Superstore CSV file into a Pandas DataFrame.

### 3. Explore the Dataset
- Displayed first five rows
- Checked dataset information
- Generated statistical summary

### 4. Data Preprocessing
- Converted **Order Date** into DateTime format.
- Converted **Ship Date** into DateTime format.

### 5. Feature Engineering
Created a new column:

**Delivery Days = Ship Date − Order Date**

This represents the number of days taken to deliver each order.

### 6. Data Cleaning
Checked for missing (null) values in the dataset.

### 7. Sales Analysis
Calculated total sales for each product category using GroupBy.

### 8. Data Visualization

#### Sales by Category
- Created a Bar Chart
- Compared total sales across categories

#### Sales Distribution
- Created a Histogram
- Observed the distribution of sales values

---

## 📊 Output

The project generates:

- Dataset Information
- Statistical Summary
- Delivery Days Calculation
- Missing Value Report
- Sales by Category
- Bar Chart
- Sales Distribution Histogram

---

## 📈 Key Insights

- Technology, Furniture, and Office Supplies are the main product categories.
- Delivery time is calculated for every order.
- Sales distribution helps identify high and low sales transactions.
- Category-wise sales comparison provides business insights.

---

## 📁 Project Structure

```
Task_1_BDA/
│
├── Task_1_BDA.ipynb
├── task_1_bda.py
├── samplesuperstore.csv
└── README.md
```

---

## ▶️ How to Run

1. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

2. Open the notebook in Jupyter Notebook or Google Colab.

3. Place the dataset in the project folder.

4. Run all cells.

---

## ✅ Results

The project successfully:
- Loaded the dataset
- Cleaned and processed the data
- Calculated delivery days
- Performed category-wise sales analysis
- Generated meaningful visualizations

---
