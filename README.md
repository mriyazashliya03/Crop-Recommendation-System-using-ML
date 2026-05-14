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

3. Feature Distributions
Histograms were plotted for all 7 features to understand the spread and distribution of values across the dataset. Saved as feature_distributions.png.

4. Correlation Heatmap
A heatmap was generated to analyze the correlation between all numerical features, helping identify which features are strongly or weakly related to each other. Saved as correlation_heatmap.png.

5. Samples per Crop
A count plot was created to visualize how many data samples exist for each crop type, confirming a balanced dataset. Saved as crop_distribution.png.

6. Boxplots per Crop
Boxplots were generated for each feature grouped by crop type, giving insight into how feature values vary across different crops and highlighting outliers. Saved as boxplots_per_crop.png.

7. Pair Plots
Pairplots were created for a sample of 5 crops (rice, maize, wheat, mango, coffee) using the first 4 features, to visualize relationships and cluster separability between crops. Saved as pairplot.png.

8. EDA Folder Organization
All generated visualizations were moved into a dedicated /EDA folder for clean project structure.
