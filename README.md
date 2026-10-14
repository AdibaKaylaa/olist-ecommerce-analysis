# Olist E-Commerce Analysis

## About the Project

This project uses the Olist Brazilian e-commerce dataset to practice working with real-world data using Python and Pandas.

I explored order and order-item data, checked for data quality issues, analyzed delivery performance and monthly order trends, and combined datasets to calculate order values.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- VS Code
- Git and GitHub

## What I Did

- Explored the orders dataset
- Checked for missing values and duplicate order IDs
- Investigated unusual delivery records
- Converted date columns to datetime format
- Calculated delivery times and delivery delays
- Analyzed late deliveries and extreme delivery times
- Analyzed monthly order volume
- Explored the order items dataset
- Checked prices and freight values
- Calculated total order values
- Combined order and order-item data using `order_id`
- Analyzed monthly order value
- Created visualizations for delivery delays and monthly trends

## Key Findings

- Average delivery time was about 12 days, with a median of 10 days.
- About 6.8% of orders with delivery information arrived later than their estimated delivery date.
- Among late orders, the median delay was 7 days.
- Monthly order volume grew strongly during 2017 and remained relatively stable through most of 2018.
- Monthly order value followed a similar pattern and reached over 1 million during several months.
- Very low order counts near the end of the dataset suggest that the final months may contain incomplete data.

## Dataset

This project uses the public Olist Brazilian E-Commerce dataset.

The raw CSV files are not included in this repository.

