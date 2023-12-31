# Car Price Analysis

## Introduction

Welcome to the Car Price Analysis project! In this project, I explore a dataset containing various attributes of cars, such as brand, manufacturing year, selling price, mileage, fuel type, seller type, transmission, and owner history. The primary goal is to conduct a comprehensive Feature Importance Analysis through Exploratory Data Analysis (EDA).

This project is part of my portfolio, showcasing my skills in data analysis and providing insights into the factors influencing the selling prices of used cars. Your feedback is valuable and appreciated as I continue to enhance my data journey skills.

Let's dive into the details of this analysis and uncover the intricacies of the used car market!

## Dataset Overview

The dataset was obtained from the Kaggle and contains information about various cars. The columns include:

- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

## Data Cleaning and Feature Engineering

The initial steps involved cleaning the data and preparing it for analysis. Key actions included:

- Multiplying the selling price and present price by 1000 to standardize the currency assumption.
- Adjusting the Year column to a period data type for better representation.
- Identifying and handling outliers to ensure data integrity.

## Exploratory Data Analysis (EDA) Questions

### 1. Mileage and Depreciation
- What is the average mileage for cars in the dataset?
- What is the relationship between kms driven and selling price?

### 2. Owner History
- How does the number of previous owners correlate with the selling price?
- Are cars with more owners generally sold at lower prices?

### 3. Car Models
- What are the most popular cars?
- What are the most expensive cars?
- Do certain cars tend to have higher selling prices?

### 4. Selling Price Trends
- Are there any noticeable trends in car selling prices over the years?
- Do certain years have higher or lower average selling prices?

### 5. Seller Type
- How does the seller type impact the selling price?
- Are cars sold by dealers typically priced higher than those sold by individuals?

### 6. Fuel Type
- What is the distribution of fuel type by price?
- What are the pricing patterns of the different fuel types over the years?

### 7. Transmission
- What is the distribution of cars based on transmission type?
- Does the type of transmission influence the selling price?
- What is the distribution of automatic transmission by seller type?

### 8. Comparison with Present Price
- How does the selling price compare with the present price?
- Are there instances where the selling price is significantly higher or lower than the present price?

## Analysis and Insights

### Mileage and Depreciation

The average mileage of cars is approximately 31,969.803 kilometers, and there is no clear correlation between the kilometers driven and selling price.

### Owner History

There seems to be an anomaly in the data, as all cars claim to have zero owners, indicating a potential data quality issue.

### Car Models

The top 5 most popular cars are City, Verna, Corolla Altis, Brio, and Ciaz. In terms of average selling prices, the top 5 expensive cars are Innova, Creta, Elantra, Fortuner, and Vitara Brezza. The top 5 cars with the most sales are Creta, Innova, Elantra, City, and Fortuner.

### Selling Price Trends

The overall trend shows an increase in average selling prices over the years, with some fluctuations in 2007, 2011, and 2017.

### Seller Type

Dealers play a significant role, selling more cars and achieving higher average sales compared to individual sellers.

### Fuel Type

Petrol cars dominate the dataset, followed by Diesel and CNG. Diesel cars tend to be pricier, while Petrol cars are more budget-friendly.

### Transmission

Most cars sold are manual, but automatic cars, especially when sold by dealers, tend to be pricier.

### Comparison with Present Price

As the present price increases, the selling price tends to increase, with some notable variations in specific years.

## Conclusion and Next Steps

In conclusion, this analysis provides valuable insights into the factors influencing the selling prices of used cars. Dealers play a crucial role in the market, and fuel type, transmission, and year of manufacture contribute to pricing dynamics. However, further investigation is needed to address anomalies in the owner history data.

Feel free to explore the cleaned dataset in the `cleaned_car_data.csv` file, and your feedback is always welcome!

**Note:** The dataset used in this analysis was obtained from the Kaggle Walmart Sales Forecasting Competition.
