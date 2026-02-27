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

<img width="650" height="480" alt="profit_distribution" src="https://github.com/user-attachments/assets/a0bfaef2-c1d0-4c77-86a2-9905030daa30" />

### Profit by Device Type

- Web and Mobile sales show different patterns:
  - Mobile sales are more evenly distributed.
  - Web sales have more extreme profit values.
- Indicates **different purchasing behavior** depending on the device.

<img width="650" height="480" alt="profit_by_device" src="https://github.com/user-attachments/assets/a276c874-6d24-49e2-89ce-b49cc1180a03" />

### Profit Trends Over Time
- There is a **general increasing trend** in monthly profits.
- Since April 2018, monthly profits exceed 250,000.
- Seasonality is visible; peak profits occurred in **November 2018**.
<img width="650" height="480" alt="profit_by_month" src="https://github.com/user-attachments/assets/8bdd15c8-6e1f-4855-9d56-d48246eabdc5" />

### Profit by Product Category

- Most profitable category: **Fashion**
- Least profitable category: **Electronics**

<img width="550" height="480" alt="profit_by_category" src="https://github.com/user-attachments/assets/dc1997df-15e5-4f5c-bf5a-640c5d0af909" />

### Profit by Product Category & Gender

- Men purchase more in **Auto & Accessories** and **Fashion**.
- Some categories show similar profit patterns for both genders.

<img width="650" height="480" alt="profit_by_category_gender" src="https://github.com/user-attachments/assets/ade32f6d-560a-40ac-8dd5-06dc4cdac1a1" />

## How to Run
1. Clone this repository
2. Install dependencies:

```bash
pip install -r requirements.txt
```
3. Open notebook.ipynb in Jupyter Notebook or Google Colab

## Project Structure
```
profit-analysis-with-seaborn/

- Profit_Analysis_with_Seaborn.ipynb          
- requirements.txt                           
- README.md                                   
```
