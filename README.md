# Predictive Modeling for Hotel Booking Cancellation

## Project Overview

This project aims to predict hotel booking cancellations using machine learning techniques. The model helps in understanding the factors that lead to cancellations and assists hotel management in minimizing the impact of these cancellations.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Visualization](#visualization)
- [Tools and Libraries](#tools-and-libraries)
- [Contributors](#contributors)

## Data Description

The dataset contains information on hotel bookings, including various features like:
- **Hotel Type:** Type of hotel (City Hotel or Resort Hotel)
- **Is Canceled:** Whether the booking was canceled (1) or not (0)
- **Lead Time:** Number of days between booking and arrival
- **Country:** Country of origin of the guest
- **Arrival Dates:** Including year, month, and day
- **Stays:** Number of nights spent during the stay (weekend and weeknights)
- **Adults, Children, Babies:** Number of adults, children, and babies
- **Special Requests:** Number of special requests made by the guest

## Data Preprocessing

- **Handling Missing Values:** Missing values in the 'Country' column were filled with the most frequent value. Other missing values were replaced with 0.
- **Filtering Invalid Data:** Removed entries where the number of adults, children, and babies was zero.
- **Feature Engineering:** Created new features and transformed existing ones to better capture the relationships in the data.

## Exploratory Data Analysis (EDA)

- **Country-wise Analysis:** Visualized the distribution of guests based on their country of origin using a choropleth map.
- **Cancellation Patterns:** Investigated patterns in the data to understand the key factors influencing cancellations.

## Modeling

- **Logistic Regression:** A baseline model for predicting cancellations.
- **Random Forest:** Improved model accuracy by capturing nonlinear relationships.
- **Gradient Boosting:** Enhanced prediction performance through iterative improvements.

## Evaluation

- **Confusion Matrix:** Analyzed the confusion matrix to understand true positives, false positives, etc.
- **Accuracy, Precision, Recall:** Measured the performance of the models using these metrics.

## Visualization

- **Interactive Choropleth Maps:** Used Plotly to visualize the geographic distribution of guests.
- **Feature Importance:** Visualized the importance of different features in predicting cancellations.

## Tools and Libraries

- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical computations
- **Matplotlib & Seaborn:** Data visualization
- **Plotly:** Interactive visualizations
- **Scikit-learn:** Machine learning algorithms and evaluation

## Contributors

- **Utkarsh Singh:** Data preprocessing, EDA, and model development
