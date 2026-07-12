# Pizza-Place-Sales-Analysis


## Project Overview

This project analyzes a pizza sales dataset using **Python** and the **Pandas** library to uncover valuable business insights. The analysis focuses on sales performance, customer ordering patterns, revenue generation, and product performance to support data-driven business decisions.

## Objectives

The objectives of this project are to:

* Merge multiple datasets into a single DataFrame.
* Perform data cleaning and preprocessing.
* Conduct exploratory data analysis (EDA).
* Answer key business questions using Python.
* Visualize trends and sales patterns.

## Dataset

The project uses four related CSV files:

* `orders.csv` – Contains order IDs, dates, and times.
* `order_details.csv` – Contains details of each order, including pizza IDs and quantities.
* `pizzas.csv` – Contains pizza sizes and prices.
* `pizza_types.csv` – Contains pizza names, categories, and ingredients.

These datasets were merged using their common keys:

* `order_id`
* `pizza_id`
* `pizza_type_id`

## Tools and Libraries

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## Data Preparation

The following preprocessing steps were performed:

* Imported the four CSV datasets.
* Merged the datasets into a single DataFrame.
* Converted the `date` column to the appropriate datetime format.
* Created a `Revenue` column by multiplying quantity by price.
* Extracted additional features such as month, day of the week, and hour of the day.
* Checked for missing values, duplicates, and data types before analysis.

## Business Questions Answered

The analysis answered the following business questions:

1. What is the total revenue generated?
2. What is the total quantity of pizzas sold?
3. How many customer orders were placed?
4. How many pizza types are available?
5. What is the average price of a pizza?
6. What are the peak hours of sales?
7. Which day of the week generates the highest sales?
8. What are the top five bestselling pizzas?
9. How do sales vary across different months?
10. Which pizza types perform poorly on the menu?

## Key Insights

Some of the insights obtained from the analysis include:

* The business generated significant revenue from pizza sales during the period analyzed.
* Customer orders peak during lunch and evening hours.
* Sales vary across the days of the week, with one day generating the highest revenue.
* A small number of pizza types account for a large share of total sales.
* Some pizzas consistently record low sales and may require menu review or promotional strategies.
* Monthly sales show noticeable fluctuations that can help with demand forecasting and inventory planning.

## How to Run the Project

1. Download this repository.
2. Install the required libraries:

pip install pandas matplotlib


3. Open the Jupyter Notebook.
4. Ensure all four CSV files are located in the project directory.
5. Run the notebook cells sequentially to reproduce the analysis.

## Project Structure

Pizza-Sales-Analysis/
── orders.csv
── order_details.csv
── pizzas.csv
── pizza_types.csv
── Pizza_Sales_Analysis.ipynb
── README.md

## Conclusion

This project demonstrates how Python can be used to clean, merge, analyze, and visualize transactional sales data. The insights generated can help businesses understand customer behavior, identify high-performing products, optimize inventory, and improve overall decision-making.

## Author

**Oluwatimileyin Gabriel**
