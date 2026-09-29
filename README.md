# Cohort Retention Analysis

## Project Overview

This project performs customer cohort retention analysis using the Online Retail II dataset.

The analysis groups customers based on their first purchase month and tracks their purchasing activity in subsequent months to understand customer retention patterns.

## Objective

- Identify customer cohorts based on first purchase month
- Calculate customer activity across subsequent months
- Calculate cohort retention percentages
- Visualize retention using a cohort heatmap
- Identify important customer retention patterns and insights

## Dataset

Dataset: Online Retail II

The dataset contains online retail transaction information including:

- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

The dataset contains transactions from 2009–2010 and 2010–2011.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning

The following preprocessing steps were performed:

- Converted InvoiceDate into datetime format
- Removed records with missing Customer ID
- Removed cancelled invoices
- Removed transactions with non-positive quantities
- Removed duplicate records
- Combined both yearly datasets

## Cohort Analysis

Customers were grouped according to their first purchase month.

The analysis calculated:

- Cohort Month
- Activity Month
- Cohort Index
- Active Customers
- Retention Percentage

## Retention Formula

Retention Percentage =

Active Customers in a Month / Customers in Month 1 × 100

## Key Insights

- Month 1 retention is 100% because it represents the original cohort month.
- Average Month 2 retention was approximately 21.16%.
- Average Month 3 retention was approximately 21.92%.
- Average Month 4 retention was approximately 21.61%.
- Average Month 11 retention was approximately 14.99%.
- December 2009 was the largest cohort with 955 customers.
- Later cohorts have fewer observation months, so long-term retention should be interpreted carefully.

## Visualization

A cohort retention heatmap was created using Seaborn to visualize customer retention across different cohorts and months.

## Project Files

- Python/Google Colab notebook
- Cleaned dataset
- Cohort retention heatmap
- Task/project report

## Conclusion

The cohort analysis shows how customer retention changes after the first purchase and provides a clear view of customer engagement across different acquisition cohorts.
