# Hotel Booking Cancellation Prediction

This project predicts whether a hotel booking will be canceled using machine learning.

## Project Overview

Hotel booking cancellations can affect revenue, room planning, and operational efficiency.  
This project uses historical hotel booking data to build a classification model that predicts cancellation behavior.

## Objective

The goal of this project is to identify whether a booking will be canceled based on customer, booking, and stay-related features.

## Dataset

The dataset used in this project is `hotel_bookings.csv` and contains information such as:

- hotel type
- lead time
- deposit type
- market segment
- previous cancellations
- special requests
- length of stay

## Workflow

The project includes:

- data cleaning
- exploratory data analysis
- feature engineering
- label encoding for categorical variables
- correlation analysis
- train test split
- model training and evaluation

## Feature Engineering

Some feature engineering steps include:

- converting `deposit_type` into binary values
- creating a new `total_nights` feature
- encoding categorical variables into numerical form

## Models Used

- Decision Tree
- Random Forest

## Results

The best result was achieved using the **Random Forest** model.

- **Decision Tree Accuracy:** 84.35%
- **Random Forest Accuracy:** 88.23%

## Key Insight

One of the most important features related to booking cancellation was **deposit_type**, which showed the strongest relationship with the target variable.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## File

- `hotel_booking_cancellation_prediction.ipynb` – main notebook for the project

## Resume Link

This project is listed in my resume under **Hotel Booking Cancellation Prediction**.
