# Amazon India Sales Analysis

##### **Project Type:** Data Science
##### **Industry:** E-Commerce
##### **Contribution:** Individual
##### **Project Domain:** Sales Analysis & Prediction

## 1. Project Overview

The **Amazon India Sales Analysis Project** focuses on analyzing Amazon India sales data from March to June 2022 using Python, Machine Learning, and Power BI.

The main objective is to explore sales data, identify sales trends, analyze product categories, understand state-wise sales performance, and extract meaningful business insights.

The project includes data cleaning, preprocessing, Exploratory Data Analysis (EDA), feature engineering, Machine Learning model development, and interactive dashboard creation using Power BI.

## 2. Project Objectives

- Explore and understand the Amazon India sales dataset.
- Clean and preprocess the sales data.
- Handle missing values and duplicate records.
- Perform Exploratory Data Analysis (EDA).
- Analyze sales trends and product category performance.
- Identify top-performing states and categories.
- Perform feature engineering.
- Build a Machine Learning model for sales prediction.
- Create an interactive Power BI dashboard.
- Extract meaningful business insights from the data.

## 3. Dataset Description

The project uses the Amazon India Sales Dataset containing order and sales information from March to June 2022.

The dataset includes information related to product categories, order details, sales amounts, quantities, fulfilment methods, shipping details, and customer locations.

**Dataset Information:**

- Dataset Source: Amazon Sale Report
- Dataset Period: March – June 2022
- Original Dataset: Approximately 128,975 records
- Cleaned Dataset: 51,334 records
- Total Sales Amount: ₹32,415,986.10

## 4. Technologies and Libraries Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Google Colab | Development environment |
| Pandas | Data cleaning and processing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning |
| Power BI | Interactive dashboard development |

## 5. Project Workflow

1. **Data Loading:** Import the Amazon sales dataset using Pandas.
2. **Data Inspection:** Examine dataset structure, columns, data types, and missing values.
3. **Data Cleaning:** Clean and preprocess the dataset.
4. **Missing Value Handling:** Identify and handle missing values.
5. **Duplicate Analysis:** Check and handle duplicate records.
6. **Feature Engineering:** Create additional features for analysis and model development.
7. **Exploratory Data Analysis:** Analyze sales patterns and trends.
8. **Product Analysis:** Analyze category-wise sales performance.
9. **Geographical Analysis:** Explore state-wise sales distribution.
10. **Machine Learning:** Develop a Random Forest Regression model.
11. **Model Evaluation:** Evaluate model performance using regression metrics.
12. **Data Visualization:** Create charts and visualizations.
13. **Dashboard Development:** Build an interactive Power BI dashboard.
14. **Business Insights:** Identify key findings from the analysis.

## 6. Data Cleaning and Preprocessing Summary

| Operation | Description |
|---|---|
| Data Inspection | Examined dataset structure and data types |
| Data Cleaning | Cleaned and processed raw sales data |
| Missing Values | Identified and handled missing values |
| Duplicate Analysis | Checked and handled duplicate records |
| Data Preprocessing | Prepared data for analysis and model development |
| Feature Engineering | Created additional features |
| Data Export | Exported cleaned dataset for further analysis |

After preprocessing, the cleaned dataset contains **51,334 records** for further analysis.

## 7. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand sales performance, product categories, geographical distribution, and sales trends.

The analysis includes:

- Sales trend analysis
- Category-wise sales analysis
- Product performance analysis
- State-wise sales analysis
- Order quantity analysis
- Fulfilment analysis
- Statistical analysis
- Correlation analysis
- Data visualization

## 8. Machine Learning

A **Random Forest Regressor** was implemented to predict sales amounts using selected features from the dataset.

### Model Evaluation

| Evaluation Metric | Result |
|---|---:|
| R² Score | 0.4285 |
| MAE | ₹143.82 |
| MSE | 43,490.84 |
| RMSE | ₹208.54 |

The model was evaluated using regression metrics to understand its predictive performance.

### Feature Importance

Feature importance analysis was performed to identify the features contributing most to the model's predictions.

The analysis highlighted Category_Set and other selected features as important contributors to the model.

## 9. Power BI Dashboard

The Power BI dashboard was developed to visualize sales performance and provide an interactive overview of the analysis.

### Dashboard Preview

<!-- Dashboard Screenshot -->

![Amazon India Sales Dashboard](images/dashboard.png)

### Dashboard Features

- Total Sales Amount
- Total Orders
- Total Quantity
- Average Order Value
- Sales Trend Analysis
- Category-wise Sales
- State-wise Sales
- Top Categories by Sales
- Machine Learning Prediction Summary
- Key Business Insights
- Interactive Slicers and Filters

## 10. Key Business Insights

Based on the analysis, the following insights were identified:

- **Total Sales:** ₹32.42 Million
- **Total Orders:** 51,076
- **Total Quantity Sold:** 49,357
- **Top Category:** Set
- **Top State:** Maharashtra
- **Most Common Fulfilment:** Amazon

The analysis provides an overview of sales performance, product category distribution, and geographical sales patterns.

## 11. Project Structure

```text
Amazon_India_Sales_Analysis/
│
├── Dataset/
│   ├── Amazon Sale Report.csv
│   └── Amazon_India_Sales_Cleaned.csv
│
├── images/
│   └── dashboard.png
│
├── Amazon_India_Sales_Analysis.ipynb
├── Amazon_India_Sales_Dashboard.pbix
└── README.md
```

## 12. Conclusion

The Amazon India Sales Analysis project demonstrates the application of Data Science techniques to analyze retail sales data.

The project involved data cleaning, preprocessing, Exploratory Data Analysis, feature engineering, Machine Learning, and data visualization.

The Random Forest Regression model was developed to explore sales prediction, while the Power BI dashboard provides an interactive visualization of sales performance and business insights.

This project provided practical experience in data analysis, Machine Learning, data visualization, and extracting meaningful insights from real-world sales data.

## Author

**Ayesha Nikhat**

- GitHub: https://github.com/ayeshanikhat12
- LinkedIn: https://www.linkedin.com/in/ayesha-nikhat-12a4aa305/