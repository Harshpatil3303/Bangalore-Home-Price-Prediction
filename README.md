# Bangalore-Home-Price-Prediction


Introduction
This project is aimed at predicting home prices in Bangalore based on various factors such as location and size of the home and Bathroom and BHK. We have employed machine learning techniques using Python's Scikit-Learn library to build predictive models. After thorough testing, we found that the Linear Regression algorithm provided the best results for our dataset.

Dataset
The dataset used for this project contains information about various homes in Bangalore. It includes features such as:

Location: The locality where the house is situated.
Size: The size of the house in terms of the number of bedrooms.
Total Square Feet: The total area of the house in square feet.
Bathrooms: The number of bathrooms in the house.
Price: The target variable, which is the price of the house in lakhs.

Data Cleaning
Data cleaning is a crucial step in preparing the dataset for modeling. In this project, we performed the following data cleaning tasks:

Handling Missing Values: We checked for missing values in the dataset and either removed rows with missing values or imputed them using appropriate methods.

Outlier Detection and Removal: We identified and handled outliers in the dataset, especially in the 'Price' and 'Total Square Feet' columns, as outliers can significantly impact the accuracy of the models.

Encoding Categorical Variables: We encoded categorical variables like 'Location' using techniques like one-hot encoding to convert them into a numerical format that can be used by machine learning algorithms.

Conclusion
This project demonstrates how machine learning techniques, specifically Linear Regression, can be used to predict home prices in Bangalore based on relevant features. Data cleaning and preprocessing play a crucial role in achieving accurate predictions.
