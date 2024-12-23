# Machine-Learning-project

**Car Price Prediction Model**

Car Price Prediction Model

Project Overview

This project aims to predict the price of cars based on various features such as engine size, curb weight, fuel efficiency, and other attributes. The model uses machine learning techniques, particularly a Random Forest Regressor, to analyze the relationship between car features and price. This model can be used by businesses in the automotive industry to understand the factors influencing car prices and to optimize design and pricing strategies for different markets.

Overview

This repository contains a machine learning model designed to predict car prices based on independent variables such as engine size, curb weight, fuel efficiency, and other car features. The model uses Random Forest Regressor and provides insights into how car prices vary with different features, helping automotive businesses make data-driven decisions for pricing strategies, market entry, and car design optimization.

Objective

•	Predict car prices based on various features.

•	Understand the impact of different car features (e.g., engine size, curb weight, fuel efficiency) on pricing.

•	Help businesses optimize their pricing strategies and car design decisions to meet target market prices and consumer preferences.

Key Features

•	Curb Weight: Heavier cars typically cost more due to more robust construction.

•	Engine Size: Larger engines usually lead to higher prices because of better performance.

•	Fuel Efficiency (MPG): Cars with higher fuel efficiency tend to be more desirable, especially in fuel-conscious markets.

•	Other Features: Includes metrics like bore, stroke, and horsepower, which also affect the price.

Model

•	The model used is a Random Forest Regressor, which was chosen for its ability to capture non-linear relationships and handle complex feature interactions.

•	The model achieved an R² score of 95.27%, indicating that it explains 95% of the variance in car prices.

Dependencies

The following libraries are required to run the project:

•	pandas

•	numpy

•	matplotlib

•	seaborn

•	sklearn

•	xgboost

•	scipy

Data Description

The dataset used for this model consists of car features like engine size, curb weight, fuel efficiency (MPG), and others. The target variable is the price of the car.

Usage

Running the Jupyter Notebook

1.	Exploratory Data Analysis (EDA):

o	Start by inspecting the dataset to understand the distributions and correlations of different features with the target price.

o	Use the Car_Price_Prediction_Analysis.ipynb notebook for this process.

2.	Model Training and Evaluation:

o	Use the model.py script to train the Random Forest Regressor model.

o	Preprocessing of the data is handled in the preprocess.py script, which includes feature selection and scaling.

3.	Prediction:

o	After training the model, use it to predict car prices for new data by passing input features into the model and obtaining price predictions.

Key Results

•	Random Forest Regressor Model:

o	Achieved R² = 95.27%, which means it explains over 95% of the variance in the car prices.

o	Mean Absolute Error (MAE) = $1,357.84, indicating an average error of $1,358 in the price predictions.

•	Significant Features:

o	Curb Weight and Engine Size are the most important features influencing car price.

o	Fuel Efficiency (MPG) and Other Features like bore and stroke also contribute but to a lesser degree.

•	Model Implications for Business Strategy:

o	Businesses can optimize car designs to meet price targets by focusing on key factors such as curb weight and engine size.

o	In markets with high fuel prices, focusing on improving fuel efficiency could be a winning strategy.

Acknowledgments

•	This model was built using the Random Forest Regressor from the sklearn library.

•	Thanks to the dataset sources and the community for providing the resources to develop this project.

