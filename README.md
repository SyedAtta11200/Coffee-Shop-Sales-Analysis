# Coffee Shop Sales Analysis and ARIMA Model Implementation

## Table of Contents
- [Introduction](#introduction)
- [Data Overview](#data-overview)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [ARIMA Model Implementation](#arima-model-implementation)
- [Power BI Dashboard](#power-bi-dashboard)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)

## Introduction
This project involves analyzing sales data from a coffee shop and implementing an ARIMA model to forecast future sales. Additionally, a Power BI dashboard is created to visualize various sales metrics such as trends, product performance, and store location performance. The insights gathered from this analysis aim to help the coffee shop optimize its operations and make data-driven decisions.

## Data Overview
The dataset consists of coffee shop transaction records with columns such as:
- Transaction Date
- Product Category
- Store Location
- Quantity Sold
- Total Sales Value

## Data Preprocessing
The following steps were performed during data preprocessing:
1. **Load Data**: The dataset was loaded into a Pandas DataFrame.
2. **Convert Data Types**: Appropriate data types were assigned, particularly ensuring the transaction date was in `datetime` format.

## Exploratory Data Analysis
Exploratory data analysis was conducted to uncover patterns and insights from the sales data:
- **Time Series Plot**: A time series plot was created to visualize transaction quantities over time, identifying trends or seasonality.
- **Sales by Category**: A bar chart was generated to show the distribution of sales across different product categories.
- **Sales by Store Location**: Another bar chart was used to analyze sales distribution across various store locations.

## ARIMA Model Implementation
An ARIMA model was implemented to forecast future sales:
1. **Train-Test Split**: The dataset was split into training and test sets.
2. **Fit ARIMA Model**: The ARIMA model was fitted on the training data to capture time series trends.
3. **Forecasting**: The model was used to forecast sales on the test data.
4. **Plot Results**: A plot compared the actual vs. predicted sales values.
5. **Model Evaluation**: The performance of the model was evaluated using the Mean Squared Error (MSE) metric.

## Power BI Dashboard
The Power BI dashboard provided visualizations to showcase the key insights:
- **Sales by Product Category**: A bar chart visualized total sales by category.
- **Product Percentage Distribution**: A donut chart displayed the contribution of each product to total sales.
- **Sales by Store Location**: A bar chart highlighted sales performance across store locations.
- **Date Slicers and Filters**: Slicers were added to filter by product category, store location, and transaction date for detailed insights.

## Conclusion
The analysis of the coffee shop sales data led to several important insights, including identifying top-performing products, understanding seasonal sales patterns, and assessing store-level performance. The ARIMA model provided reasonably accurate sales forecasts, helping the shop plan for future demand.

To increase profitability, the following strategies are recommended:
1. **Increase Promotion and Marketing**: Focus on promoting top-selling products like Barista Espresso and Gourmet Brewed Coffee.
2. **Optimize Pricing**: Reevaluate the pricing strategy for high-impact products.
3. **Inventory Management**: Ensure high-demand products are always in stock.
4. **Customer Feedback**: Gather feedback on top products to further improve their appeal.
5. **Cross-Selling**: Bundle popular products with other items to boost sales.

## Technologies Used
- **Python** (Pandas, ARIMA modeling)
- **Power BI** (Data visualization)

## Setup Instructions
1. Clone the repository:
   ```bash
    git clone https://github.com/your-username/Coffee-Shop-Sales-Analysis.git

   ```
2.Navigate to the project folder:
 ```bash
 cd Coffee-Shop-Sales-Analysis
   ```
3.Install required Python packages:
 ```bash
 pip install -r requirements.txt
   ```
4.Open Power BI and load the provided .pbix file to view the dashboard.

   
