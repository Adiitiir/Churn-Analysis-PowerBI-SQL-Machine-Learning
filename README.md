# Customer Churn Analysis with SQL Server, Power BI, and Python

This repository contains a complete project to perform **customer churn analysis** using SQL Server, Power BI, and Python. It includes the entire ETL process, database setup, data modeling, machine learning, and visualization steps to analyze and predict customer churn effectively.

---

## Project Goals
The goals of this project are as follows:
1. **Analyze Customer Data**: Gain insights into customer behavior at all available levels of granularity.
2. **Study Churn Profiles**: Identify patterns and profiles for implementing targeted marketing campaigns.
3. **Predict Future Churn**: Build a model to predict customer churn for proactive business strategies.

---

## Metrics
The key metrics required for this project include:
- **Total Customers**: The overall number of customers at any given time.
- **Total Churn**: The count of customers who have churned during a specific period.
- **Churn Rate**: The percentage of customers who churned out of the total customers.
- **New Joiners**: The count of new customers who joined within the same period.

---

## Features
1. **ETL Process in SQL Server**: Extract, transform, and load (ETL) data into a SQL Server database.
2. **Data Cleaning**: Clean and prepare raw customer data using SQL queries.
3. **Power BI Transformations**: Transform data within Power BI for better visualization and insights.
4. **Data Visualization in Power BI**: Create dynamic and interactive dashboards to analyze customer churn.
5. **Machine Learning Model**: Build and train a Random Forest model in Python to predict customer churn.
6. **Predicted Data Integration**: Use the predictions from the ML model in Power BI to create a churn profile visualization.


---

## Project Workflow
### 1. SQL Server
- **ETL Process**: Extract raw data and load it into the database.
- **Data Cleaning**: Use SQL scripts to clean, format, and prepare data for analysis.
- **Views**: Create views to simplify Power BI integration.

### 2. Power BI
- **Data Modeling**: Transform and integrate data using Power BI's Power Query Editor.
- **Visualization**: Build dynamic charts, tables, and filters for interactive dashboards.
- **Enhancements**: Add tooltips, slicers, and drill-through pages for deeper insights.

### 3. Machine Learning (Python)
- **Random Forest Model**:
  - Train a model to predict customer churn using customer features.
  - Evaluate the model using metrics like accuracy, precision, recall, and F1 score.
- **Predictions**: Generate predictions for unseen data and integrate them back into Power BI.

### 4. Predicted Churn Profile
- **Dashboard Page**: Create a new page in Power BI to visualize churn predictions and customer profiles.

---

## Results
- **Churn Analysis Dashboard**: Provides insights into customer behavior, trends, and churn rates.
- **Machine Learning Integration**: Predicts customer churn and displays profiles of high-risk customers.


