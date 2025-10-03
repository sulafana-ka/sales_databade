# sales_database
A basic sales analysis by integrating SQL within Python to manage a small database and generate a visualization.

# Project: SQLite Database Analysis with Python 📊

This repository contains the solution for a data analysis task demonstrating the connection between Python and a lightweight SQLite database to generate a basic sales summary and visualization.

# Project Summary

This project involves the full analytical workflow, starting with data access and concluding with visualization:

 1 - Database Creation & Access: Used Python's sqlite3 module to create and connect to a small database file (sales_data.db) containing sales data.

 2 - Data Analysis: Executed a single SQL query (using SUM() and GROUP BY) to aggregate the raw data and calculate the total Revenue and Quantity sold by product.

 3 - Visualization: Generated and saved a Matplotlib bar chart to visually represent the total revenue for each product.

Repository Contents

 - simple_salesdata.ipynb - The Jupyter Notebook containing all the Python code for setup, querying, and plotting.
 - sales_data.db  -	The functional SQLite database file used as the dataset.
 - sales_chart.png -	The generated bar chart visualizing the sales revenue summary.
 - README.md	 - This file.
