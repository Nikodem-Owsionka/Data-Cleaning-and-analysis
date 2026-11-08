# Cafe sales data cleaning and analysis

## Overview

This project uses Python to explore cafe sales data and extract insights from transactional data. It focuses on data cleaning and data visualisation using Pandas and Matplotlib

## Objectives

- Handle missing values and prepare data for analysis
- Investigate monthly and weekly sales trends
- Investigate sales performance across different products
- Visualise findings to identify any patterns and differences

## Dataset

The dataset contains cafe transaction records, including the following variables:

| Column | Description |
|---|---|
| Transaction ID | A unique identifier for each transaction |
| Item | The name of the product purchased |
| Quantity | Number of units purchased |
| Price Per Unit | Price of an individual item |
| Total Spent | Total amount spent on the transaction |
| Payment method | The method of payment used |
| Location | The location where the transaction occured |
| Transaction Date | Date of the transaction |

## Libraries needed

- Pandas
- NumPy
- Matplotlib
- random

## Data Cleaning

<img width="374" height="37" alt="image" src="https://github.com/user-attachments/assets/a5402516-f356-461c-9e13-747145f68e6f" />

- Initial dataset contained missing values, I used the above relationship to calculate them
- Every Item had its corresponding Price Per Unit which i used to find any missing entries in the 'Item' column
- Any missing rows that didnt have enough information to be be recovered using these methods were left as 'NA'
- Changing the data types of columns to the most suitable one

Additional checks were performed to identify missing values and assess data before proceeding with analysis.

## Exploratory Data Analysis

- Calculated and used a bar graph to display the Total daily sales and the Average daily sales for each day of the week to identify the strongest and weakest performing days

- Calculated and visualised the weekly sales of the Cafe to see how sales varied during the year and to identify any possible trends

- Calculated and used a bar graph to display the total sales for each month

- Examined the total quantity sold of each item for the year to identify the most popular product

- Calculated and used a bar graph to display the total revenue generated from each product for the year

### Key Findings

- Thursday has the highest total and average sales for the year
- Wednesday has the lowest total and average sales for the year
- June was the highest performing month
- February was the lowest performing month
- Coffee was the most popular item but salad generated the most revenue

