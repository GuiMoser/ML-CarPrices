# Car Prices Regression

## Project Description
Regression Model to predict car prices.

This notebook works with training three different regression models (LinearRegression, Catboost, and LightGBM).

Performs an EDA using python, uses plots, functions and cycles to detect outliers. Selects the best features to split between training, validation and testing, and encodes categorical features.

Uses GridSearchCV for hyperparameter tuning, and uses the CatBoost and LightGBM libraries to perform Gradient Boosting to reduce the RMSE of the models.

The decision on the best model, in addition to the lowest RMSE, also takes into account the prediction speed.

## Objectives
- Perform exploratory data analysis.
- Select the best features to split between training, validation and testing.
- Encode categorical features.
- Train three different regression models (LinearRegression, Catboost, and LightGBM).
- Perform hyperparameter tuning using GridSearchCV.
- Compare the performance of the three models and select the best one.

## Tools and Libs used
- Python: Main language used for analysis.
- Pandas: Library for data manipulation and analysis.
- NumPy: Library for numerical operations.
- Matplotlib and Seaborn: Libraries for data visualization.
- Scikit-learn: Library for machine learning.
- CatBoost and LightGBM: Libraries for Gradient Boosting.

## Methodology
#### EDA
- Import libraries.
- Load the dataframes.
- Perform exploratory data analysis using summary statistics and data visualization.
#### Preprocessing
- Identify and treat missing values.
- Identify and treat outliers.
- Scale the data.
- Select the best features to split between training, validation and testing.
- Encode categorical features.
#### Model Training
- Train three different regression models (LinearRegression, Catboost, and LightGBM).
- Perform hyperparameter tuning using GridSearchCV.
#### Model Evaluation
- Compare the performance of the three models and select the best one.

## Learnings
- Data analysis: Interpreting and extracting valuable insights from large volumes of data.
- Data cleaning: Identifying and correcting missing, duplicate, and anomalous values.
- Creating graphics: Using matplotlib and seaborn to visualize data in an intuitive and informative way.
- Data preprocessing: Preparing Data for analysis, including cleaning and treat the data.
- Use of libraries and tools: Practical application of various libraries and tools from the Python ecosystem, such as Pandas, Numpy, Sklearn, Matplotlib and Seaborn.
- Data visualization: Creating very detailed graphs and other types of visualizations to identify patterns and trends.
- Data-driven decision making: Using insights derived from data analysis to guide strategic decisions.
- Regression Models: Train and evaluate regression models.
- Model comparison: Compare models based on different metrics
- Scaling: Scaling the data to have zero mean and unit variance.
- Encoding: Encoding categorical variables
- Feature selection: Selecting the best features to split between training, validation and testing.
- Hyperparameter tuning: Using GridSearchCV to find the best hyperparameters for the models.
