# Ireland Residential Home Price Analysis and Prediction

This project analyzes and predicts residential home prices in Ireland using the Daft.ie dataset. The main goal is to identify key factors affecting home prices through exploratory data analysis (EDA) and then build predictive models to estimate home prices.

## Project Overview
1. **Dataset**: Residential home data from Daft.ie, including features like property size, number of bedrooms, and more.
2. **Exploratory Data Analysis (EDA)**: Completed the EDA to understand trends, outliers, and key factors influencing home prices.
3. **Visualization**: Currently working on visualizing the data for better insights into the relationships between different features.
4. **Prediction**: The next phase will focus on building predictive models using both single-variable and multi-variable regression techniques. These models will estimate house prices based on numerical data.

## Workflow

### 1. Data Preparation
   - Cleaned the dataset by handling missing values.
   - Applied one-hot encoding to categorical variables.
   - Removed outliers in property sizes to improve model accuracy.

### 2. Exploratory Data Analysis (EDA)
   - Identified key factors influencing home prices, such as property size, number of bedrooms, and location.
   - Visualized data distributions, correlations, and outliers.

### 3. Visualization (In Progress)
   - Creating visual representations of data, including scatter plots, histograms, geospatial, and heatmaps.
   - Highlighting the impact of key variables on house prices.

### 4. Predictive Modeling (Upcoming)
   - Develop single-variable and multi-variable regression models.
   - Use advanced techniques like multiple imputation to handle missing data.
   - Evaluate models using performance metrics such as R², RMSE, and MAE.

## Key Features
- **Handling Missing Data**: Applied multiple imputation techniques to fill missing values in key columns such as `propertySize`.
- **Data Splitting**: Split the dataset into numerical and categorical datasets for more effective modeling.
- **Mapping Categorical Data**: Applied ordinal encoding to features such as `ber_rating` and reverse-mapped them when needed.

## Future Work
- Build and optimize regression models to predict house prices.
- Compare the performance of different models using evaluation metrics.
- Fine-tune models by removing outliers and adjusting features to improve prediction accuracy.

## Getting Started
To run this project:
1. Clone the repository - git clone https://github.com/fernandes-s/Daft_ie.git
