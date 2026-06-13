# Overview 
This repository contain machine learning with python and build linear regression model to make a prediction on price of the house. The dataset includes the information about square_feet , age , distant_to_city(km) , number of room . The target feature is the price of the house .

## 1. Introduction 
Predicting real estate prices accurately is a significant challenge for buyers, sellers, and investors due to complex market variables. Traditional property valuation methods are often slow, subjective, and prone to human error. This project addresses the problem by utilizing historical sales data to build an automated pricing model, providing a scalable and objective approach to estimating property values.

## 2. Objective 
* To predict the price of the house base on the dataset and feature of dataset . 🏦
* To build machine learning model such as Linear Regression. 📈
* To minimize the prediction error by using optimization stredtegy  such like gradient descent. 🧠 📊

## 3. Dataset Overview
* This dataset was from : Kaggle.
* Tota Record : 10,000 observations (rows).
* Total Features : 4 independent variables and 1 target variable.
* Feature Dictionary :
### Feature Dictionary

| Feature Name | Data Type | Description | Example Value |
| :--- | :--- | :--- | :--- |
| `square_feet` | Continuous Numerical | Total interior living space of the house | `2248.36` |
| `num_rooms` | Discrete Numerical | Total number of rooms in the property | `3` |
| `age` | Discrete Numerical | The age of the house in years since construction | `92` |
| `distance_to_city(km)` | Continuous Numerical | Distance from the property to the city center in kilometers | `22.99` |
| **`price` (Target)** | Continuous Numerical | The final market sale price of the house in USD | `$200,374.09` |

### Dataset Preview (First 5 Rows)

| Index | square_feet | num_rooms | age | distance_to_city(km) | price |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **0** | 2248.36 | 3 | 92 | 22.99 | 200374.09 |
| **1** | 1930.87 | 2 | 22 | 13.98 | 268784.85 |
| **2** | 2323.84 | 6 | 33 | 21.50 | 315020.86 |
| **3** | 2761.51 | 3 | 63 | 10.34 | 355111.47 |
| **4** | 1882.92 | 7 | 54 | 25.49 | 234197.12 |

## 4. Data Preprocessing  and Cleaning 
* Checking missing value  : since the dataset took from kaggle so there is no missing value .
* Hanle outlier : Outliers in `square_feet` and `price` were intentionally retained because they represent valid, real-world market variations like luxury homes. Keeping these data points ensures the model learns the full market spectrum, while **Mean Absolute Error (MAE)** was prioritized during evaluation to accurately measure performance without extreme values skewing the results.

## 5. Exploatory Data Analytic 
In this part we will do EDA to analyst our data :
*  

  



