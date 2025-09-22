# 📊 Week 7 – Sales Data Analysis Assignment

##  Project Overview
This project analyzes **Coffee Shop Sales data** using Python (Pandas + Matplotlib).  
The objective is to perform **basic data analysis** and create **visualizations** for insights.  

Dataset: `Coffee Shop Sales.xlsx` (from Kaggle)  

---

##  Tasks Completed

###  Task 1: Data Loading & Exploration
- Loaded dataset using **Pandas**.
- Checked for missing values and duplicates.
- Converted dates into proper datetime format.
- Previewed first few rows with `df.head()`.

###  Task 2: Basic Data Analysis
- Computed summary statistics using `.describe()`.
- Calculated:
  - **Total revenue**
  - **Average quantity sold**
  - **Median unit price**
  - **Standard deviation of revenue**
- Performed grouping:
  - Average revenue by `product_category`
  - Sales patterns by `transaction_date`.

### Task 3: Data Visualization
Created 4 plots using **Matplotlib**:
1. **Line Chart** → Revenue trend over time.  
2. **Bar Chart** → Average revenue per product category.  
3. **Histogram** → Distribution of transaction revenue.  
4. **Scatter Plot** → Quantity vs Revenue relationship.  

All plots customized with **titles, labels, and legends**.

###  Task 4: Normalization Findings
- Analyzed dataset against **1NF, 2NF, and 3NF**.
- Identified redundancy in product and store information.
- Recommendations:
  - Separate **Transactions**, **Products**, **Stores**, and **Sales** tables.
  - Create lookup tables for categories/types.
  - Index foreign keys for performance.



# Tools Used
- **Python 3**
- **Pandas** → Data analysis  
- **Matplotlib / Seaborn** → Visualizations  
- **Jupyter Notebook (Kaggle)** → Development environment  

