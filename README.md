# 🚗 Car Price Prediction using Machine Learning

## Overview

Car Price Prediction is a machine learning web application that estimates the market value of a vehicle based on its specifications and attributes. The project demonstrates an end-to-end machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and deployment through an interactive Streamlit interface.

## Features

* Predicts vehicle prices using Machine Learning
* Interactive and user-friendly Streamlit web application
* Data preprocessing and feature engineering pipeline
* Comparison of multiple regression models
* Real-time price prediction
* End-to-end Scikit-Learn pipeline implementation

## Dataset

The project uses a vehicle dataset containing information such as:

* Brand
* Manufacturing Year
* Fuel Type
* Transmission Type
* Engine Capacity
* Horsepower
* Mileage
* Vehicle Category

The dataset used for training is available in:

```text
dataset/global_cars_enhanced.csv
```

## Feature Engineering

Custom features were created to improve model performance and capture meaningful vehicle characteristics:

* Car Age
* HP-per-CC Ratio
* Efficiency Score
* Luxury Vehicle Indicator

## Machine Learning Workflow

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training and Evaluation
5. Model Selection
6. Deployment using Streamlit

## Models Explored

* Linear Regression
* Random Forest Regressor
* Decision Tree Regressor

The final deployed model is integrated into a reusable Scikit-Learn pipeline for real-time predictions.

## Project Structure

```text
Car_Price_Prediction/
│
├── app.py
├── car_price_pipeline.pkl
├── requirements.txt
├── README.md
│
├── dataset/
│   └── global_cars_enhanced.csv
│
└── notebook/
    └── Project_AB+.ipynb
```

## Installation

```bash
pip install -r requirements.txt
```

## Run Locally

```bash
streamlit run app.py
```

## Live Demo

https://carpriceprediction-5gu5tyet7bhifkkbjyqscp.streamlit.app/

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Streamlit
* Joblib

## Author

**Anunay Kumar**
B.Tech Information Technology
Haldia Institute of Technology
