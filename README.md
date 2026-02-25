# Profit Analysis with Seaborn

## Project Overview
This project explores sales data using Python (Pandas, NumPy) and visualizations (Seaborn, Matplotlib). 
The goal is to analyze the distribution of profits, compare sales across devices, monitor profit trends over time, 
and investigate revenue patterns by product category and customer gender.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset
The dataset contains 51,290 records of sales with the following key columns:
- `order_date`: date of the order
- `profit`: profit per order
- `device_type`: Web or Mobile
- `product_category`: category of the product
- `gender`: gender of the customer

## Analysis & Key Insights

### Profit Distribution
- The distribution of profit is **right-skewed**, with most orders generating moderate profit.
- Peaks are found in the ranges **10–40** and **120–130**.
- There are a few high-profit outliers.

### Profit by Device Type
- Web and Mobile sales show different patterns:
  - Mobile sales are more evenly distributed.
  - Web sales have more extreme profit values.
- Indicates **different purchasing behavior** depending on the device.

### Profit Trends Over Time
- There is a **general increasing trend** in monthly profits.
- Since April 2018, monthly profits exceed 250,000.
- Seasonality is visible; peak profits occurred in **November 2018**.

### Profit by Product Category
- Most profitable category: **Fashion**
- Least profitable category: **Electronics**

### Profit by Product Category & Gender
- Men purchase more in **Auto & Accessories** and **Fashion**.
- Some categories show similar profit patterns for both genders.

## How to Run
1. Clone this repository
2. Install dependencies:

```bash
pip install -r requirements.txt
```
3. Open notebook.ipynb in Jupyter Notebook or Google Colab

## Project Structure

profit-analysis-with-seaborn/
- Profit_Analysis_with_Seaborn.ipynb          
- requirements.txt                           
- README.md                                   
