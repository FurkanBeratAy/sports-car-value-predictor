# Sports Car Value predictor

This project analyzes a dataset of sports cars to explore the relationship between various features and car pricing. Using Exploratory Data Analysis (EDA) and Linear Regression models, the project compares the impact of different car attributes on sports car prices.

## Project Overview

The primary goal of this project is to determine which car features have the greatest influence on the price of sports cars. By performing EDA and building linear regression models, we can predict how features like Torque, 0-60 MPH Time, and the Year affect car pricing.

## Dataset

The dataset contains several attributes of sports cars, such as:
- **Price** (Target Variable)
- **Torque** (Engine Power)
- **0-60 MPH Time** (in seconds)
- **Year** (Car's Manufacturing Year)
- **Horsepower**, **Weight**, and other car features

## Key Steps in the Project

1. **Exploratory Data Analysis (EDA):**
   - Visualizing the distribution of car features and target variables.
   - Identifying correlations between features and the price of cars.
   - Checking for outliers, missing values, and distribution patterns.

2. **Data Preprocessing:**
   - Cleaning the dataset by handling missing values and outliers.
   - Scaling or transforming features as necessary for linear regression modeling.

3. **Linear Regression Modeling:**
   - Creating and training multiple linear regression models to predict the price based on various features.
   - Evaluating model performance using metrics like Mean Squared Error (MSE).

## Final Suggestions

From the linear regression models and scatterplot analysis, we conclude the following insights regarding the impact of specific features on sports car pricing:

- **Torque:**  
  There is a significant positive correlation between **Torque** and price. As the torque increases, the price of the car increases by **$2,212** for each unit increase in torque, highlighting the importance of engine power in determining the car's price.

- **0-60 MPH Time (seconds):**  
  The **0-60 MPH Time** has a negative relationship with price. As the time it takes to reach 60 MPH increases, the price of the car tends to decrease. This suggests that faster sports cars generally command higher prices.

- **Year:**  
  The **Year** of the car also negatively impacts pricing. As the car's manufacturing year increases (i.e., the car gets older), the price tends to decrease, indicating depreciation over time.

These findings provide a solid basis for pricing sports cars based on key features like torque, performance (0-60 MPH time), and the age of the car.
