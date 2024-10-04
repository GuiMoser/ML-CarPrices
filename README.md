# Car Prices Regression

Regression Model to predict car prices.

This notebook works with training three different regression models (LinearRegression, Catboost, and LightGBM).

Performs an EDA using python, uses plots, functions and cycles to detect outliers. Selects the best features to split between training, validation and testing, and encodes categorical features.

Uses GridSearchCV for hyperparameter tuning, and uses the CatBoost and LightGBM libraries to perform Gradient Boosting to reduce the RMSE of the models.

The decision on the best model, in addition to the lowest RMSE, also takes into account the prediction speed.