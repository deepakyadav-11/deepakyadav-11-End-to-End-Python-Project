# Retail Orders Analysis Project

## Overview

This project involves an end-to-end data analysis of a retail orders dataset. The goal is to extract valuable insights that can help drive business decisions. The project utilizes Python for data cleaning and transformation, followed by SQL for querying the data.

## Table of Contents

- [Project Objectives](#project-objectives)
- [Dataset](#dataset)
- [Data Cleaning & Transformation](#data-cleaning--transformation)
- [Data Analysis](#data-analysis)
- [Insights](#insights)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Conclusion](#conclusion)

## Project Objectives

- Clean and prepare the dataset for analysis.
- Generate new metrics like discount, sale price, and profit.
- Perform SQL queries to uncover key business insights.

## Dataset

The dataset used in this project is sourced from Kaggle: [Retail Orders Dataset](https://www.kaggle.com/ankitbansal06/retail-orders).

## Data Cleaning & Transformation

The data cleaning process included:
- Replacing spaces in column names with underscores.
- Converting all column names to lowercase.
- Calculating additional columns:
  - **Discount**: `list_price * discount_percent * 0.01`
  - **Sale Price**: `list_price - discount`
  - **Profit**: `sale_price - cost_price`

## Data Analysis

The analysis was conducted using SQL queries. Key analyses include:
- Identifying the top 10 highest revenue-generating products.
- Analyzing the top 5 highest selling products in each region.
- Month-over-month sales growth comparison between 2022 and 2023.
- Determining the best-performing months for each product category.
- Finding the sub-categories with the highest profit growth in 2023 compared to 2022.

## Insights

- The top 10 products account for a significant portion of the total revenue.
- Regional performance varies, with certain products dominating specific regions.
- Sales growth trends indicate significant differences between 2022 and 2023.
- Certain months consistently outperform others in specific categories.
- Some sub-categories have seen tremendous profit growth, indicating potential areas for business focus.

## Technologies Used

- **Python**: Data cleaning and transformation
- **Pandas**: Data manipulation
- **PySpark**: Creating Spark DataFrames
- **SQL**: Data querying and analysis
- **Jupyter Notebook**: Code development and exploration


Conclusion
This project demonstrates the power of Python and SQL in transforming raw data into actionable business insights. The analysis reveals key trends and growth opportunities within the retail dataset.

Feel free to explore the code and reach out if you have any questions or feedback!
