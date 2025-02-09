# Sunshine Miami: Unveiling Real Estate AI

This project aims to predict housing prices in Miami using various regression models. The dataset includes multiple features related to housing prices, and three regression models are implemented: Linear Regression, KNeighbors Regressor, and Random Forest Regressor.

## Table of Contents
- [Installation](#installation)
- [Data Overview](#data-overview)
- [Data Preprocessing](#data-preprocessing)
- [Data Visualization](#data-visualization)
- [Models and Evaluation](#models-and-evaluation)
  - [Linear Regression](#linear-regression)
  - [KNeighbors Regressor](#kneighbors-regressor)
  - [Random Forest Regressor](#random-forest-regressor)
- [Conclusion](#conclusion)

Installation <a name="installation"></a>
  - Install Python 3.12.  
  - Install Jupyter Notebook.
  - Install `scikit-learn` library.
  - Install `pandas` library.
  - Install `numpy` library.
  - Install `matplotlib` library.
  - Install `seaborn` library.
  - Run `Machine Learning algorithms on Miami Housing Dataset.ipynb`

Data Overview <a name="data-overview"></a>

The dataset `miami-housing.csv` contains various features related to housing prices in Miami. The target variable is SALE_PRC (Sale Price).

Data Preprocessing <a name="data-preprocessing"></a>

  - Load the dataset and check for duplicates and missing values.
  - Drop duplicate rows and unnecessary columns.
  - Split the dataset into training and testing sets.
  - Scale the features using StandardScaler.

Data Visualization <a name="data-visualization"></a>

  - Boxplot of Sale Price.
  - Heatmap of feature correlations.
  - Boxplot of Sale Price distribution by month sold.
  - Scatter plots of Sale Prices against various features.

Models and Evaluation <a name="models-and-evaluation"></a>
Linear Regression <a name="linear-regression"></a>

  - Fit the Linear Regression model to the training data.
  - Make predictions on the test data.
  - Evaluate the model using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared.
  - Plot actual vs. predicted values.

KNeighbors Regressor <a name="kneighbors-regressor"></a>

  - Implement KNeighbors Regressor with uniform and distance weights.
  - Fit the model to the training data.
  - Make predictions on the test data.
  - Evaluate the model using MSE, RMSE, MAE, and R-squared.
  - Plot actual vs. predicted values.

Random Forest Regressor <a name="random-forest-regressor"></a>

  - Fit the Random Forest Regressor model to the training data.
  - Make predictions on the test data.
  - Evaluate the model using MSE, RMSE, MAE, and R-squared.
  - Plot actual vs. predicted values.

Conclusion <a name="conclusion"></a>

This project demonstrates the process of predicting housing prices using different regression models. The evaluation metrics provide insights into the performance of each model. The Random Forest Regressor typically performs better due to its ability to handle non-linear relationships and interactions between features.


