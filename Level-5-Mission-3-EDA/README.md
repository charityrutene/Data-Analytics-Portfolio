# Exploratory Data Analysis: Retail Sales

**Level 5, Mission 3** | Individual project | [Back to portfolio](../README.md)

## Goal
Explore a retail sales dataset to find patterns, trends and outliers.

## Dataset
An Excel workbook of retail transactions with three tables: Sales, Invoice and Product. Provided through Mission Ready. After merging, there were 83,277 rows and 9 columns.

## What I did
1. Loaded each Excel sheet into its own Pandas DataFrame.
2. Created a Sales column (Quantity x UnitPrice) and checked for missing values. There were none.
3. Calculated mean, median, mode and standard deviation.
4. Merged the three tables on InvoiceNo and StockCode.
5. Filtered out zero quantities and checked for outliers with a scatter plot.
6. Built a histogram, a line chart and a correlation heatmap.
7. Grouped sales by product category and built a Country x Category pivot table.

## Key findings
- Quantity and Sales are very strongly correlated (0.98). Unit price has a much weaker effect.
- Most orders are small. The median quantity is 6, but the mean is 13.6, because a few very large orders pull it up.
- Sales are right-skewed. A small number of high-value transactions contribute a lot of revenue.
- Some product categories earn far more than others, and this varies by country.

## What I learned
- How to merge tables and check that the join worked.
- Why outliers matter when you read averages.
- How to explain each chart in plain language.

## Tools
Python, Pandas, Matplotlib, Seaborn, Microsoft Fabric notebooks.

## Files
[Open the notebook](Level-5-Mission-3-EDA-Sales-Dataset.ipynb). The data was provided through Mission Ready, so it is not included here.
