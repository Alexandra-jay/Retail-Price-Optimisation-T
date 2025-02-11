# Retail Price Analysis and Prediction

## Overview

This project analyzes and visualizes retail price data using Python. It explores various aspects of pricing, competitor comparisons, and predictive modeling using a Decision Tree Regressor. The project leverages pandas, plotly, and scikit-learn for data manipulation, visualization, and machine learning.

## Features

Exploratory Data Analysis (EDA):

Histogram of total prices

Box plots for unit price, weekday pricing, and holiday pricing

Scatter plot for quantity vs. total price with trendline

Bar chart for average total price by product category

Correlation heatmap of numerical features

## Competitor Price Comparison:

Computes the price difference between unit price and competitor price

Visualizes the average competitor price difference by product category

## Predictive Modeling:

Uses a Decision Tree Regressor to predict total price based on features

Splits the dataset into training and test sets (80-20 split)

Evaluates predictions with a scatter plot comparing actual vs. predicted values

## Installation

To run this project locally, install the required dependencies:

pip install pandas plotly scikit-learn

## Dataset

The project requires a CSV file (retail_price.csv) containing the following columns:

qty: Quantity of items sold

unit_price: Price per unit

total_price: Total price of purchase

product_category_name: Category of the product

weekday: Day of the week

holiday: Whether the purchase was made on a holiday

comp_1: Competitor price

product_score: Product rating score

## Visualizations

The file generates various interactive visualizations using Plotly, including:

Histogram, box plots, scatter plots, bar charts

Correlation heatmap

Prediction vs. actual values for model performance

## Machine Learning Model

Model: Decision Tree Regressor

Features: qty, unit_price, comp_1, product_score, comp_price_diff

Target: total_price

Splits data into training (80%) and testing (20%) sets

Evaluates model predictions using visualization

Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

### License

This project is licensed under the MIT License.
