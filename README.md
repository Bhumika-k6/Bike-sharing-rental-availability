# Bike sharing rental prediction
This project predicts bike sharing rental demand using Machine learning techniques.
## Project Overview
This project focuses on predicting the daily demand for bike sharing rentals using machine learning techniques.
Bike sharing systems are widely used in smart cities, and predicting demand helps in better planning, resource management, and customer satisfaction.
## Objective
The main objective of this project is to:
1. Predict the number of bikes rented per day
2. Analyze factors affecting bike rental demand
3. Build a machine learning model for accurate prediction
## Problem Statement
Bike rental demand varies depending on factors such as weather, temperature, season, and day type.
Manual estimation often leads to shortage or excess availability.
Hence, a machine learning-based system is required to predict bike rental demand efficiently.
## Dataset Description
Dataset contains daily bike rental records with weather and seasonal information.
File used:
day.csv
## Important features
| Feature    | Description                                       |
| ---------- | ------------------------------------------------- |
| season     | Season (1: Spring, 2: Summer, 3: Fall, 4: Winter) |
| yr         | Year (0: 2011, 1: 2012)                           |
| mnth       | Month                                             |
| holiday    | Whether the day is a holiday                      |
| weekday    | Day of the week                                   |
| workingday | Working day or not                                |
| weathersit | Weather condition                                 |
| temp       | Normalized temperature                            |
| atemp      | Feeling temperature                               |
| hum        | Humidity                                          |
| windspeed  | Wind speed                                        |
| cnt        | Total bike rentals (target variable)              |

## Tools and technologies used:
- Python
- Jupyter Notebook
- Pandas
- Numpy
- Scikit-Learn
- Matplotlib
- Seaborn
## Project Workflow
1. Data Loading
2. Data Preprocessing
3. Handling missing values
4. Exploratory Data Analysis (EDA)
5. Feature selection
6. Data splitting (Train & Test)
7. Model training
8. Model evaluation
9. Prediction
## Machine Learning Model Used
Linear Regression
(Used for predicting continuous numerical values)
## Model Evaluation
The model performance is evaluated using:
1. R² Score
2. Mean Squared Error (MSE)
3. Prediction comparison graphs
These metrics help in measuring the accuracy of the model.
## Results
The model successfully predicts bike rental demand.
Weather and temperature significantly affect rental count.
Higher rentals are observed during favorable weather conditions.
## Conclusion
This project demonstrates how machine learning can be used to predict bike sharing rental demand efficiently.
The developed model helps understand rental patterns and supports decision-making in bike-sharing systems.
## Future Scope
1. Use advanced models like Random Forest or XGBoost
2. Real-time prediction system
3. Deployment using Flask or Streamlit
4. Integration with live weather API
## Author
Name: Bhumika
Department: Computer Science Engineering
Project Type: Machine Learning Mini Project
