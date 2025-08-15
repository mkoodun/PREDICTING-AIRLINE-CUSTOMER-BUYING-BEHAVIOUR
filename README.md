# PREDICTING-AIRLINE-CUSTOMER-BUYING-BEHAVIOUR

Developping a predictive model to determine the likelihood that a customer will complete a booking for a holiday.

## Overview

This project uses a Random Forest classifier to predict whether a customer is likely to book a holiday based on various features, including customer demographics and flight details. The model aims to support decision-making in marketing and customer engagement by identifying high-probability customers.

## Dataset

The dataset is `customer_booking.csv`. It is from the British Airways data science job simulation.

## Methodology

The full pipeline (data preprocessing, model training, evaluation, and improvements) is documented in the [Jupyter Notebook](https://github.com/mkoodun/PREDICTING-AIRLINE-CUSTOMER-BUYING-BEHAVIOUR/blob/main/Code.ipynb).

## Tech Stack
- Python (Jupyter Notebook)
- Numpy, Pandas, Scikit-learn
- Matplotlib, Seaborn

## Future Work
- Explore alternative ensemble methods or algorithms, such as Gradient Boosting or Logistic Regression
- Experiment with oversampling, SMOTE, or hybrid sampling techniques to handle imbalance
- Include more customer-centric features (demographics, historical bookings, preferences)
- Increase training data and further optimise hyperparameters for improved recall
