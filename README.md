Gold Price Prediction Project
Overview
This repository contains a machine learning project that predicts gold prices using historical data. The project utilizes various regression algorithms, including Linear Regression, Ridge Regression, Lasso Regression, and Random Forest Regressor.

Metrics Used
The project evaluates the performance of each regression model using the following metrics:

- R-squared (R²)
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Mean Bias Error (MBE)
- Root Mean Squared Error (RMSE)

Dependencies
The project requires the following libraries:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Plotly

Data Preprocessing
The project performs the following data preprocessing steps:

- Handling missing values using SimpleImputer
- Scaling numerical features using StandardScaler

Model Evaluation
The project evaluates the performance of each regression model on a test dataset and compares their metrics.

Visualization
The project includes visualizations to illustrate:

- Correlation between features
- Outliers in the data
- Gold prices before and after scaling

Future Work
- Experiment with other regression algorithms
- Incorporate additional features (e.g., economic indicators, geopolitical events)
- Use more advanced techniques (e.g., time series analysis, deep learning)

Data Source
- The gold price data used in this project is sourced from kaggle.com .
