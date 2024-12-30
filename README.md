# CODETECH-Intern-Task-2
Housing Prices Prediction Project

Overview

This project predicts housing prices in California using data from the housing.csv dataset. It employs Linear Regression to estimate the median house value based on various features, including location, income levels, and housing characteristics.

Objectives

Perform exploratory data analysis (EDA) to gain insights into the dataset.

Preprocess the data to handle missing values and categorical variables.

Train and evaluate a Linear Regression model.

Visualize key insights, correlations, and model results.

Features

The dataset includes the following features:

longitude and latitude: Geographical location of the house.

housing_median_age: Median age of houses in the area.

total_rooms and total_bedrooms: Total number of rooms and bedrooms.

population: Population of the area.

households: Number of households in the area.

median_income: Median income of residents.

ocean_proximity: Categorical variable indicating proximity to the ocean.

median_house_value: Target variable (house price).

Steps

1. Exploratory Data Analysis (EDA)

Displayed basic statistics and visualized distributions using histograms.

Plotted geographical data to observe patterns in housing prices.

Analyzed the correlation matrix to identify relationships between features and the target variable.

2. Data Preprocessing

Handled missing values by removing rows with null values in total_bedrooms.

Applied one-hot encoding to convert the ocean_proximity categorical variable into numerical format.

Prepared data for modeling by splitting into features (X) and target (Y).

3. Model Training

Split the dataset into training and testing sets (80-20 split).

Used Linear Regression to fit the training data and predict housing prices.

4. Evaluation

Evaluated the model's performance using R-squared value.

Visualized residuals to assess prediction errors.

Analyzed feature coefficients to determine feature importance.

Results

Intercept: <insert_value>

Coefficients:

Provided in the feature importance plot.

R-squared value: <insert_value>

Residual plot and error analysis indicate model accuracy and performance.

Visualizations

Correlation Heatmap: Highlights relationships between features and the target variable.

Residual Plot: Visualizes prediction errors.

Feature Importance: Bar plot showing the coefficients of features.

Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Tools: Google Colab, GitHub

Installation

To replicate this project:

Clone this repository:

git clone https://github.com/MadhuLekhaV/Housing-Prices-Prediction.git

Navigate to the project folder:

cd Housing-Prices-Prediction

Install the required libraries:

pip install -r requirements.txt

Usage

Place the housing.csv dataset in the project directory.

Run the Python script or Jupyter Notebook to:

Explore the dataset.

Train and evaluate the model.

Visualize results.

Future Improvements

Implement advanced regression models such as Ridge or Lasso regression.

Perform hyperparameter tuning to optimize the model.

Incorporate additional evaluation metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE).

Experiment with feature engineering to improve predictions.

Author

Name: Madhu Lekha V

Email: madhulekhav.ug22.ad@francisxavier.ac.in

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

Dataset sourced from California Housing Prices dataset.
