## Exploratory Data Analysis of Purchase Dataset

This repository contains the code and notebooks for the Exploratory Data Analysis (EDA) of a purchase dataset.

## Project Description:

This project aims to uncover insights and patterns within a purchase dataset using visualization techniques and statistical analysis.

## Dataset Information

* Type: E-commerce Purchase data 
* Source: [Kaggle](https://www.kaggle.com/datasets/raosuny/e-commerce-purchase-dataset/data)
  
## Features:
    date, customer_id, product_category, payment_method, value, time_on_site, clicks_in_site

Notes: 
* Product_category is an id for a category of products (for example clothing, gadgets…).
* Each row is a cart (1-many items) for a customer. assume customers purchase from a single category each time.
* Payment_method can be credit card or Paypal
* Value is the total value for the cart (can include any number of items) time_on_site is in minutes

## Methodology:

* The analysis primarily uses Python libraries like Pandas, NumPy, and Matplotlib for data manipulation and visualization.
* Visualize the findings to better understand data.
  
## Key Findings:

* Number of product categories and their frequency.
* Payment methods and their frequency.
* Amount of sales(in USD) done by every category.
* Time spent per product category in minutes.
* Total amount(in USD) spent per year.
* Average day wise time spent.
* Correlation between number columns('value', 'time_on_site', 'clicks_in_site')

## Project Structure:

The project is organized as follows:

* Data: This directory contains the E-commerce purchase dataset in CSV format.
* Notebooks: This directory contains Jupyter notebooks with the Python code used for data analysis and visualization.
* README.md: This file provides an overview of the project, objectives, and instructions for running the code.
* LICENSE: This project is under the MIT License.

## Contributing: 

Contributions to this project are welcome! If you have ideas for improving the analysis, adding new features, or fixing issues, please open an issue or submit a pull request.

## License: 

This project is licensed under the MIT License. See the LICENSE file for details.
