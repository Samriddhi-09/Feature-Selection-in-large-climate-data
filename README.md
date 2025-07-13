# Feature-Selection-in-large-climate-data
This project focuses on building a robust machine learning model for daily precipitation prediction over various grid locations in Madhya Pradesh, India, using data from the ERA5 reanalysis dataset (1979–2023). The model is developed using XGBoost, a powerful gradient boosting framework, and incorporates Recursive Feature Elimination (RFE) for selecting the most significant meteorological features that contribute to rainfall prediction.

Highlights
Dataset: Daily ERA5 climate data (1979–2023) for multiple spatial grids across Madhya Pradesh.

Model: XGBRegressor from the XGBoost library is used for regression tasks.

Feature Selection: RFECV (Recursive Feature Elimination with Cross-Validation) using XGBoost as the base estimator to identify the most relevant predictors.

Goal: Improve prediction accuracy and model interpretability by reducing dimensionality and focusing on the most influential features.

Methodology
Data Preprocessing: Cleaned and organized daily ERA5 data into a machine learning-ready format.

Feature Selection: Applied RFE with XGBoost to rank and select the top features contributing to precipitation.

Model Training: Trained the XGBoost regressor on selected features.

Evaluation: Evaluated model performance using metrics like R² score, RMSE, and MAE.
