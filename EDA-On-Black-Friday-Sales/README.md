# Black Friday Sales Analysis By Madireddy Bharath Kumar Reddy

## Overview

This project contains a detailed exploratory data analysis (EDA) of the Black Friday sales dataset. The analysis includes various statistical and visual techniques to understand the data better and derive meaningful insights about the sales, customer demographics, and product performance.

## Dataset

The dataset used in this analysis is the Black Friday sales dataset. It contains information on transactions made during Black Friday, including details about customers, products, and purchases.

## File Structure

- `BlackFriday.csv`: The dataset file.
- `black_friday_sales_analysis.ipynb`: Jupyter Notebook containing the EDA code.
- `README.md`: This readme file.

## Analysis Steps

### 1. Importing Required Libraries

We start by importing necessary libraries such as pandas, seaborn, and numpy.

### 2. Loading the Dataset

Load the dataset using pandas.

### 3. Initial Data Exploration

- Display the first five rows of the dataset.
- Get information about the dataset (data types, non-null counts, etc.).
- Display the number of unique values in each column.
- Describe the dataset to get statistical summaries.

### 4. Handling Missing Values

- Check for missing values.
- Drop columns with a significant number of missing values.

### 5. Detailed Column Analysis

- Analyze unique users, products, genders, age ranges, occupations, city categories, stay duration in current city, marital status, and product categories.
- Calculate mean purchase value.

### 6. Univariate Analysis

- Gender ratio analysis (bar and pie charts).
- City category distribution (pie chart).
- Purchase column analysis (box plot).
- Marital status distribution (pie chart).
- Occupation distribution (bar chart).
- Stay duration in current city distribution (bar chart).

### 7. Bivariate Analysis

- Purchase distribution by age (bar chart).
- Number of products purchased by age (bar chart).
- Percentage of purchase by gender (pie chart).
- Top 10 product IDs by quantity (bar chart).

### 8. Multicolumn Analysis

- Age and gender analysis (count plots).
- Gender and marital status analysis (count plots).
- City category and age analysis (count plots).
- Marital status and city category analysis (count plots).
- City category and gender analysis (count plots).
- Stay duration in current city and gender analysis (count plots).
- Stay duration in current city and marital status analysis (count plots).

### 9. Combining Gender and Marital Status

- Create a new column combining gender and marital status.
- Analyze combined gender and marital status with city category and age (count plots).

## Conclusion

This analysis provides insights into various aspects of the Black Friday sales data, including customer demographics, purchase behaviors, and product performance. The visualizations and statistical summaries help in understanding the data better and can be used to make informed business decisions.
