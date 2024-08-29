# Diwali Sales EDA Analysis Using Python

## Introduction
Diwali, also known as the Festival of Lights, is one of the most celebrated festivals in India, and a significant surge in consumer spending marks it. This project leverages Python and Exploratory Data Analysis (EDA) techniques to analyze Diwali sales data. The goal is to uncover valuable insights that can drive strategic decisions to boost sales and enhance customer experiences during this festive season. By examining factors such as gender, age, location, marital status, occupation, and product categories, the project aims to provide a data-driven foundation for optimizing sales strategies.

## Objective
The objective of this project is to analyze Diwali sales data to uncover insights into customer demographics, purchasing behaviour, and product preferences. These insights will guide strategic decisions to enhance revenue and customer experience during the Diwali season.

## Project Overview
Diwali is one of the most significant festivals in India, marked by a substantial increase in consumer spending across various product categories. To capitalize on this opportunity, it is crucial to understand the customer base and their preferences. This project analyzes Diwali sales data to provide actionable insights that can help optimize sales strategies and improve the overall shopping experience.

This repository contains Python code and data files used to perform EDA on several aspects of Diwali sales, including:

### 1. Gender Analysis
- **Objective:** To understand the distribution of sales by gender.
- **Method:** We use bar charts to visualize the count of purchases by gender and analyze the total sales amount contributed by each gender.
- **Insights:** The analysis revealed that females constitute the majority of buyers and have a higher purchasing power compared to males during the Diwali season.

### 2. Age Analysis
- **Objective:** To analyze the age groups of customers and their purchasing patterns.
- **Method:** We group the data by age groups and visualize it using count plots and bar plots to examine the total amount spent by each age group.
- **Insights:** The age group of 26-35 years emerged as the most active buyers, particularly among females.

### 3. State Analysis
- **Objective:** To identify sales trends across different states or regions.
- **Method:** We group the data by state and analyze the total number of orders and sales amount. The results are visualized using bar charts.
- **Insights:** Uttar Pradesh, Maharashtra, and Karnataka are the top states in terms of the number of orders and total sales, indicating a strong consumer base in these regions.

### 4. Marital Status Analysis
- **Objective:** To explore the impact of marital status on sales.
- **Method:** We examine the distribution of sales among married and unmarried customers, with a focus on gender-based differences. This is visualized using count plots and bar charts.
- **Insights:** Married women are the most significant contributors to Diwali sales, reflecting their higher purchasing power during the festive season.

### 5. Occupation Analysis
- **Objective:** To examine the relationship between customer occupation and purchasing behaviour.
- **Method:** The data is grouped by occupation, and we analyze the total amount spent by each occupational group. The results are displayed using bar plots.
- **Insights:** Customers working in the IT, Healthcare, and Aviation sectors are the most active buyers, suggesting a higher disposable income in these industries.

### 6. Product Category Analysis
- **Objective:** To analyze the popularity of different product categories during Diwali.
- **Method:** We categorize the sales data by product categories and visualize the data using count plots and bar charts to determine which categories are the most popular.
- **Insights:** The Food, Clothing, and Electronics categories dominate Diwali sales, indicating a high demand for these products during the festive season.

## Data Description
The dataset used in this analysis consists of various features including:
- **User_ID:** Unique identifier for each customer.
- **Cust_name:** Name of the customer.
- **Product_ID:** Unique identifier for each product.
- **Gender:** Gender of the customer.
- **Age Group:** Age group of the customer.
- **Age:** Exact age of the customer.
- **Marital_Status:** Marital status of the customer.
- **State:** State where the customer resides.
- **Zone:** Geographic zone of the state.
- **Occupation:** Occupation of the customer.
- **Product_Category:** Category of the purchased product.
- **Orders:** Number of orders placed by the customer.
- **Amount:** Total amount spent by the customer.

## Methodology
1. **Data Preprocessing:** 
   - Import the required libraries (NumPy, Pandas, Matplotlib, Seaborn).
   - Load the dataset and perform initial inspections (e.g., checking the shape, data types, and basic statistics).
   - Handle missing values by dropping unnecessary columns and filling or removing null values.
   - Convert data types where necessary to facilitate analysis.

2. **Exploratory Data Analysis (EDA):**
   - Perform EDA on each aspect (Gender, Age, State, Marital Status, Occupation, Product Category).
   - Use various visualization techniques (bar charts, count plots) to uncover patterns and trends in the data.
   - Summarize the findings for each analysis to inform strategic decisions.

## Tools Used
- **Python Libraries:**
  - `NumPy` for numerical operations.
  - `Pandas` for data manipulation and analysis.
  - `Matplotlib` and `Seaborn` for data visualization.

## Results and Conclusions
The EDA provides valuable insights into the purchasing behavior of customers during Diwali, highlighting key areas where businesses can focus their efforts to maximize sales. By understanding the demographic factors that influence buying decisions, companies can tailor their marketing strategies, product offerings, and customer service to better meet the needs of their target audience.
