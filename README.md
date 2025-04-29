# California-Housing-Linear-Regression

## Project Overview
This project involves implementing a simple linear regression model using the California Housing Prices dataset. The goal is to predict the median house value based on median income, evaluate model performance, and visualize the relationship through graphs and statistical metrics.

## Dataset
The dataset used in this project is the California Housing Prices dataset, which can be found here: https://www.kaggle.com/datasets/camnugent/california-housing-prices

## Key Insights

### Data Cleaning & Preprocessing
1. Handle Missing Values:
   - Filled missing values in the total_bedrooms column with the median value of that column.

2. Feature Engineering:
   - Created new categorical columns population_group and age_group using binning for visualization purposes.

### Visualizations Created
- Count of Houses by Ocean Proximity: A countplot showing the distribution of houses based on their distance from the ocean.
- House Value by Population Group: A bar plot comparing median house value across different population ranges.
- House Value by Housing Age Group: A bar plot showing median house values grouped by the age of the houses.

### Model Training & Evaluation
- Built a Simple Linear Regression model using median_income as the independent variable and median_house_value as the target.
- Split the data into training and testing sets using an 80-20 split.
- Trained the model and evaluated it using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).
- Created a scatter plot with the regression line to visualize model performance.

## Tools and Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
