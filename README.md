# End-to-End Data Analytics Project (Python + SQL)

[![Project Banner](project_banner.png)](https://yourusername.github.io/data-analytics-project/)

## 📊 Project Overview

This repository contains an end-to-end data analytics project that demonstrates a complete workflow from data acquisition to analysis and visualization using Python and SQL. The project analyzes sales data to extract meaningful business insights through advanced SQL queries.

### [View Live Demo](https://yourusername.github.io/data-analytics-project/)

## 🔄 Project Pipeline

1. **Data Collection**: Downloaded dataset from Kaggle API
2. **Data Cleaning**: Used Python (Pandas) to preprocess the data
3. **Data Loading**: Loaded clean data into Microsoft SQL Server
4. **SQL Analysis**: Performed complex queries to answer business questions
5. **Visualization**: Created interactive visualizations of key insights

## 🛠️ Technologies Used

- **Python**: Data preprocessing with Pandas and NumPy in Jupyter Notebook
- **SQL**: Microsoft SQL Server for data storage and analysis
- **Front-end**: HTML, CSS, JavaScript for project website
- **Visualization**: Chart.js for interactive data visualizations

## 📈 Key Analyses

This project answers several important business questions through SQL analysis:

1. **Top Revenue Products**: Identified the top 10 highest revenue-generating products
2. **Regional Analysis**: Found top 5 highest-selling products in each region
3. **Growth Comparison**: Compared month-over-month growth between 2022 and 2023
4. **Seasonal Patterns**: Determined which months had highest sales for each category
5. **Subcategory Growth**: Identified subcategories with highest profit growth year-over-year

## 📁 Repository Structure

```
data-analytics-project/
├── data/
│   ├── raw/             # Original data files
│   │   └── retail-orders.zip
│   └── processed/       # Cleaned and transformed data
├── notebooks/
│   ├── .ipynb_checkpoints/
│   └── Orders_data_analysis.ipynb
├── sql/
│   ├── schema.sql       # Database schema creation
│   └── SQLQuery1.sql    # Your existing SQL query
├── src/
│   └── scripts.js       # Your JavaScript file
├── static/
│   └── styles.css       # Your CSS file
├── docs/
│   └── Data_Analysis_Project.drawio  # Documentation diagram
└── index.html           # Project homepage
