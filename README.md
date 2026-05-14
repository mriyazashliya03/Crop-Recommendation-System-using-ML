# Crop-Recommendation-System

Data Preprocessing & Exploratory Data Analysis (EDA)
Overview
This section covers the initial data loading, inspection, and exploratory data analysis performed on the Crop Recommendation dataset. The goal was to understand the structure of the data, identify patterns across features, and visualize how different soil and climate conditions relate to various crops.

Dataset
The dataset was downloaded directly from Kaggle using the kagglehub library:

Source: madhuraatmarambhagat/crop-recommendation-dataset
File: Crop_recommendation.csv
Features: N, P, K, temperature, humidity, ph, rainfall
Target: label (crop type)


Steps Performed
1. Dataset Loading
The dataset was downloaded via kagglehub and copied into the working directory for easy access.

2. Basic EDA
Initial inspection of the dataset included:

* Shape and structure of the data
* First few rows using .head()
* Data types and null value checks using .info() and .isnull().sum()
* Statistical summary using .describe()
* Class distribution using .value_counts() on the label column
