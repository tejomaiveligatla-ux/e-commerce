# E-Commerce Sales Analysis and Prediction

## Project Overview

This project analyzes e-commerce sales data using Python and applies machine learning techniques to predict sales.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## Project Steps

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Sales Analysis
* Machine Learning
* Model Comparison
* Sales Prediction

## Machine Learning Models

Three regression models were evaluated:

| Model                    | R² Score |
| ------------------------ | -------: |
| Linear Regression        |   78.96% |
| Polynomial Regression    |   99.86% |
| Random Forest Regression |   99.93% |

Random Forest Regression achieved the highest R² score among the evaluated models.

## Prediction

The model predicts sales using:

* Quantity
* Unit Price
* Discount

Example:

**Quantity:** 5
**Unit Price:** 100
**Discount:** 10%
**Formula-based Sales:** 450
**Random Forest Prediction:** 382

## Note

The Sales value in the dataset is derived from Quantity, Unit Price, and Discount. Therefore, the high R² scores should not be interpreted as real-world prediction accuracy.

## Conclusion

This project demonstrates the complete workflow of an e-commerce sales analysis and machine learning prediction project, from data preprocessing and visualization to model comparison and prediction.
