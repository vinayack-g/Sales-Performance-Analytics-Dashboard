# Sales Performance Analytics Dashboard

## Overview

The **Sales Performance Analytics Dashboard** is an interactive data visualization project developed during my **Data Analytics Internship at 42 Learn**. The project demonstrates how retail sales data can be transformed into meaningful business insights using Tableau.

Before building the dashboard, the datasets were prepared using **Python** in the **Google Colab** environment. Libraries such as **Pandas** and **NumPy** were used to inspect, organize, validate, and preprocess the data before importing it into Tableau for visualization.

The final dashboard provides an interactive view of sales performance, profit, quantity, customer segments, product categories, shipping methods, and regional trends to support business analysis and decision-making.

---

## Project Objectives

* Analyze retail sales data using Tableau.
* Preprocess datasets using Python.
* Create interactive dashboards for business reporting.
* Compare sales and profit across categories and regions.
* Present business insights through effective data visualization.

---

## Features

* Interactive Tableau dashboard
* Sales performance analysis
* Profit analysis
* Quantity analysis
* Category and sub-category comparison
* Customer segment analysis
* Ship mode analysis
* Regional and state-wise sales visualization
* Dynamic filters for interactive exploration

---

## Technologies Used

* Tableau Public
* Python
* Pandas
* NumPy
* Google Colab
* Microsoft Excel
* CSV Datasets

---

## Repository Structure

```text
Sales-Performance-Analytics-Dashboard/
│
├── Dashboard/
│   └── SUPER STORE INTERACTIVE DASHBOARD.twbx
│
├── Data/
│   ├── Retail_store_order_details.xlsx
│   └── Retail_store_product_details.csv
│
├── Presentation/
│   └── Internship_Presentation.pptx
│
├── Images/
│   └── dashboard_preview.png
│
├── LICENSE
└── README.md
```

---

## Dataset

This project uses two retail datasets.

### Retail Store Order Details

The order dataset contains:

* Order ID
* Order Date
* Ship Date
* Customer ID
* Customer Name
* Segment
* Country
* City
* State
* Region
* Sales
* Quantity
* Discount
* Profit

### Retail Store Product Details

The product dataset contains:

* Product ID
* Category
* Sub-Category
* Product Name

The datasets are connected using the **Product ID** field to create a complete sales performance analysis.

---

## Data Preparation

The datasets were preprocessed in **Google Colab** using **Python**, **Pandas**, and **NumPy** before being imported into Tableau.

The preprocessing workflow included:

* Loading datasets using Pandas.
* Inspecting column names and data structure.
* Verifying data types for each field.
* Checking for missing or inconsistent values.
* Reviewing duplicate records and validating dataset consistency.
* Using NumPy for numerical operations and data validation.
* Organizing the data into a structured format suitable for visualization.
* Exporting the processed datasets for Tableau.

This preprocessing process helped ensure that the dashboard was built on accurate and well-structured data.

---

## Dashboard Highlights

The interactive dashboard provides visual analysis for:

* Sales by Category
* Sales by Sub-Category
* Profit Analysis
* Quantity Analysis
* Customer Segment Performance
* Ship Mode Distribution
* Regional Sales Analysis
* State-wise Sales Comparison

Interactive filters allow users to explore different business perspectives and gain deeper insights from the data.

---

## Tableau Public Dashboard

The interactive dashboard is also available on Tableau Public.

**Dashboard Link:**

https://public.tableau.com/views/SUPERSTOREINTERACTIVEDASHBOARD_17177669716190/Dashboard1

---

## Learning Outcomes

This project provided practical experience in:

* Data cleaning using Python
* Data preprocessing with Pandas
* Numerical data handling with NumPy
* Working in Google Colab
* Tableau dashboard development
* Business intelligence concepts
* Interactive data visualization
* Retail sales analysis

---

## How to Use

1. Clone or download this repository.
2. Open the `SUPER STORE INTERACTIVE DASHBOARD.twbx` file using Tableau Desktop or Tableau Public.
3. Explore the dashboard using the available interactive filters.
4. View the online dashboard through the Tableau Public link provided above.

---

## Author

**Gunndebommu Lakkshmii Vinayack**

Bachelor of Technology in Computer Science and Engineering

PACE Institute of Technology and Sciences

---

## License

This project is licensed under the **MIT License**.
