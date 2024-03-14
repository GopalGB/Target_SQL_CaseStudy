# Target Data Analysis Project

This repository contains the code and analysis for the Target data analysis project. The project aims to analyze a dataset provided by Target to extract valuable insights and provide actionable recommendations.

## Dataset Overview

The dataset consists of 8 CSV files containing information about customers, sellers, orders, payments, reviews, products, and geolocations. Below is a brief description of each file:

1. `customers.csv`: Information about customers including unique IDs, zip codes, cities, and states.
2. `sellers.csv`: Information about sellers including unique IDs, zip codes, cities, and states.
3. `order_items.csv`: Details of orders including order IDs, product IDs, prices, and shipping information.
4. `geolocations.csv`: Geolocation data including zip codes, latitude, longitude, cities, and states.
5. `payments.csv`: Payment details including order IDs, payment methods, installments, and payment values.
6. `orders.csv`: Order information such as order IDs, customer IDs, statuses, timestamps, and delivery dates.
7. `reviews.csv`: Customer reviews including review IDs, order IDs, scores, comments, and timestamps.
8. `products.csv`: Product information including IDs, categories, descriptions, dimensions, and weights.

## Analysis Tasks

### 1. Data Exploration

1.1. Data types of all columns in the "customers" table.

1.2. Time range of orders placed.

1.3. Count of cities & states of customers who ordered.
  
### 2. In-depth Exploration

2.1. Trend in the number of orders placed over the past years.

2.2. Monthly seasonality in the number of orders.

2.3. Time of day when Brazilian customers mostly place orders.

### 3. Evolution of E-commerce Orders

3.1. Month-on-month orders placed in each state.

3.2. Distribution of customers across states.

### 4. Impact on Economy

4.1. Percentage increase in order costs from 2017 to 2018.

4.2. Total & average order price for each state.

4.3. Total & average order freight for each state.

### 5. Analysis based on Sales, Freight, and Delivery Time

5.1. Delivery time and difference between estimated & actual delivery dates.

5.2. Top 5 states with highest & lowest average freight values.
5.3. Top 5 states with highest & lowest average delivery times.
5.4. Top 5 states with fastest order delivery compared to estimated date.

### 6. Analysis based on Payments

6.1. Month-on-month orders placed using different payment types.

6.2. Number of orders placed based on payment installments.

## Usage

1. Clone this repository.
2. Download the dataset files from the provided Google Drive link.
3. Place the dataset files in the appropriate directory.
4. Run the analysis scripts in your preferred environment.
