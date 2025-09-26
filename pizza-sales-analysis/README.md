# Pizza Sales Analysis

This project analyzes a year’s worth of sales data from a fictitious pizza place. The goal is to uncover business insights such as revenue trends, customer ordering patterns, best-selling pizzas, and underperforming menu items.

## Project Structure
The dataset comes from the `Pizza+Place+Sales.zip` archive and contains four CSV files:

- **Orders.csv** → Order IDs, dates, and times
- **Order Details.csv** → Links orders to pizzas with quantities
- **Pizzas.csv** → Pizza sizes and prices
- **Pizza Types.csv** → Pizza names, categories, and ingredients

A data dictionary is also included to describe the datasets.

## Analysis & Key Questions
In this project, I explored questions such as:
- What is the **total revenue** generated?
- How many pizzas were sold (**total quantity**)?
- How many **orders** were placed?
- How many **pizza types** are on the menu?
- What is the **average pizza price**?
- What are the **peak sales hours**?
- Which **day of the week** had the highest sales?
- What are the **Top 5 best-selling pizzas**?
- How do **monthly sales** trend across the year?
- Which pizzas are **underperforming**?

## Tools & Libraries
- **Python**
- **Pandas** → Data cleaning & manipulation  
- **Matplotlib & Seaborn** → Data visualization  
- **Jupyter Notebook** → Interactive analysis  

## Insights & Findings
Some highlights from the analysis:
- Peak sales occur during **noon hours**.
- **Thursdays, Fridays & Saturdays** generate the most revenue.
- The **Top 5 pizzas** dominate sales while some niche pizzas perform poorly.
- There are noticeable **rise and fall alternative trends** in monthly sales.

*(See the notebook for full details and visualizations.)*

## Repository Contents
- `Olagoke_Pizza_Sales_Analysis.ipynb` → Main Jupyter notebook with analysis  
- `data/` → Contains the CSV files  
- `README.md` → Project documentation  

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/olagokeolowu/pizza-sales-analysis.git

