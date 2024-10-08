# OIBSIP_03

Overview
The Car Price Prediction project aims to predict the prices of cars based on various features using machine learning techniques. This project explores the impact of car characteristics such as brand, fuel type, engine size, horsepower, and more on car pricing.

Dataset
The dataset used in this project is sourced from the CarPrice_Assignment.csv file

Project Structure

├── CarPrice_Assignment.csv  # Dataset used for training and testing
├── car_price_prediction.ipynb  # Jupyter notebook containing the code for data preprocessing, model training, and prediction
├── requirements.txt  # List of required libraries and dependencies
└── README.md  # Project documentation

Installation
To run this project, you'll need to have Python installed along with the necessary libraries. You can install the required libraries using pip:

pip install -r requirements.txt

Usage
Load the Dataset: The dataset is loaded into a Pandas DataFrame for analysis.
Preprocess the Data: Categorical variables are encoded, and irrelevant columns are dropped.
Train the Model: A machine learning model (Linear Regression) is trained on the preprocessed data.
Make Predictions: Use the trained model to predict car prices based on user-defined inputs.
Example Prediction
You can input specific car features in the provided format to predict the car price. Modify the new_car dictionary in the Jupyter notebook to include the desired features.

Evaluation
The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R²) values.
