# House Price Prediction

## Overview
![HPP](https://ritu-19.github.io/images/housing_0_2.jpg)
This project aims to predict house prices using various machine learning techniques. By analyzing a set of features related to houses, such as size, location, number of bedrooms, and more, the model can estimate the market value of a house. This can be useful for real estate agents, buyers, sellers, and other stakeholders.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Data](#data)
- [Models](#models)
- [Evaluation](#evaluation)
- [Modeling](#modeling)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation
To run this project, you need to have Python installed. It is recommended to use a virtual environment to manage dependencies. Follow the steps below to set up the project:

1. Clone the repository:
```
git clone https://github.com/devShivaniP/house-price-prediction.git
cd house-price-prediction
```

2. Create a virtual environment:
```
python -m venv venv
```

3. Activate the virtual environment:
- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```
  source venv/bin/activate
  ```

4. Install the required packages:
```
pip install -r requirements.txt
```

## Data
The data used in this project includes prices and features of houses such as:
- Sale price
- Condition
- Zip Code
- Flat Area
- No. of rooms
- Other indicators such as age, latitude, longtitude, etc.  

## Models
The project explores different machine learning and deep learning models, including:
- Linear Regression
- Gradient Descent


## Evaluation
Model performance is evaluated using various metrics: <br>

- Mean Squared Error (MSE)
- Mean Absolute Error(MAE)
- Root Mean Squared Error(RMSE)
- R^2 score
- Cost Function Curve
- Residual plots

## Modeling
The modeling phase of the House Price Prediction project involves several key steps to ensure the development of an accurate and reliable predictive model. Below is a detailed breakdown of these steps:

### 1. Data Cleaning
Before building any models, it's crucial to clean the data to ensure it is in the best possible shape for analysis. This includes:
- **Handling Missing Values:** Impute or remove missing data points.
- **Treating Outliers in both Dependent and Independent Variables:** Identify and handle outliers that could skew the model.
- **Correcting Data Types:** Ensure all features are in their correct data types (e.g., converting categorical variables to strings or integers).

### 2. Exploratory Data Analysis (EDA)
EDA is performed to understand the underlying patterns and relationships in the data:
- **Descriptive Statistics:** Summarize the central tendency, dispersion, and shape of the dataset’s distribution.
- **Visualizations:** Use plots such as histograms, scatter plots, and box plots to visualize relationships and distributions.
- **Correlation Analysis:** Identify correlations between features and the target variable (house price).

### 3. Feature Engineering
Feature engineering involves creating new features or modifying existing ones to improve model performance:
- **Encoding Categorical Variables:** Convert categorical variables into numerical values using techniques such as one-hot encoding.
- **Scaling and Normalization:** Scale features to ensure they have similar ranges, which is important for algorithms like Gradient Boosting.
- **Feature Selection:** Select the most relevant features based on their importance or correlation with the target variable.

### 4. Model Selection

Various machine learning algorithms are explored to determine the best fit for the data. Some of the models considered include:

- **Linear Regression:** A simple approach to model the relationship between the features and the target variable.

- **Gradient Boosting:** Another ensemble technique that builds models sequentially to correct errors of the previous models.

### 5. Model Training

The selected models are trained on the prepared dataset:

- **Train-Test Split:** Divide the dataset into training and testing sets to evaluate model performance.

- **Hyperparameter Tuning:** Optimize model parameters using techniques such as Grid Search or Random Search to enhance model performance.

### 6. Model Evaluation
Evaluate the trained models using appropriate metrics to understand their performance:
- **Mean Absolute Error (MAE):** Measures the average magnitude of the errors in predictions.
- **Mean Squared Error (MSE):** Measures the average of the squares of the errors.
- **Root Mean Squared Error (RMSE):** The square root of MSE, which provides error in the same units as the target variable.
- **R-squared (R²):** Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
I would like to thank the contributors and the open-source community for their valuable resources and support. Special thanks to [Internshala Trainings](https://trainings.internshala.com/) for their guidance and constant supervision as well as for providing necessary datasets and code files for completion of the project. 

