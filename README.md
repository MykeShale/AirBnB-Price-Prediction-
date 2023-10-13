# Airbnb Data Analysis and Prediction Model

This repository contains the code and data for a data analysis and prediction model of Airbnb listings. The analysis was performed using Python and the Pandas library.

Overview

The goal of this project is to:

Identify the factors that most affect the price of an Airbnb listing.
Develop a machine learning model to predict the price of an Airbnb listing.
Data

The data used in this project is from the Airbnb Seattle Listings dataset, which is available on Kaggle. The dataset contains information on over 20,000 Airbnb listings in Seattle, including the price, location, amenities, and number of reviews.

Analysis

The first step in the analysis was to clean and preprocess the data. This involved removing outliers, correcting errors, and converting categorical variables to numerical variables.

Once the data was clean, exploratory data analysis (EDA) was performed to identify patterns and relationships in the data. This included visualizing the data using histograms, bar charts, and scatter plots.

EDA revealed that the following factors have the biggest impact on the price of an Airbnb listing:

Location: Listings in more central locations tend to be more expensive.
Number of bedrooms: Listings with more bedrooms tend to be more expensive.
Number of bathrooms: Listings with more bathrooms tend to be more expensive.
Amenities: Listings with more amenities tend to be more expensive.
Prediction Model

Once the important factors were identified, a machine learning model was developed to predict the price of an Airbnb listing. The model used is a random forest regressor, which is a type of ensemble learning algorithm that is known for its accuracy and robustness.

The model was trained on 75% of the data and evaluated on the remaining 25%. The model achieved an R-squared score of 0.90 on the evaluation set, which indicates that it is able to predict the price of Airbnb listings with high accuracy.

Usage

To use the prediction model, simply pass in the values for the following features:

Location
Number of bedrooms
Number of bathrooms
Amenities
Number of reviews
The model will then predict the price of the Airbnb listing.
