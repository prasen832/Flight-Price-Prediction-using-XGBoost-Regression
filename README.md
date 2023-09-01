# Flight-Price-Prediction-using-XGBoost-Regression

## Overview
1. This **Machine Learning project** is built in **Python** using **Jupyter Notebook** to **Predict flight prices** for flights traveling across **major cities in India**.
2. The **dataset** is **scrapped** and it requires huge **data cleaning** which is done using **ReGex, Pandas** and **Numpy.**
3. **Sklean XGBoost Regressor model** is used for **Prediction.**

![Airplane](Airplane.jpg)

## EDA

### We used RegEx, Pandas and Numpy together to clean the dataset and some created new features using it

1. Extract Airline from Airline-Class
2. Extract Class from Airline-Class
3. Extract Source from Departure Time	
4. Extract Departure Hour and Min from Departure Time
5. Extract Destination from Arrival Time
6. Extract Arrival Hour and Min from Arrival Time
7. Convert Duration time in minutes
8. Convert Date of Journey into 2 separate features Journey Day and Journey Month
9. Convert Date of Booking into 2 separate features Booking Day and Booking Month

