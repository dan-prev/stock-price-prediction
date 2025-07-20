# stock-price-prediction

This project focuses on predicting house prices in Ames, Iowa using various regression models. The dataset contains 79 features covering different aspects of each property. After cleaning the data and handling missing values, several models were tested, including linear regression (OLS, Ridge, Lasso), decision trees, random forests, gradient boosting, and XGBoost.

XGBoost performed best overall, with the lowest RMSE after tuning and applying a log transformation to the target variable. Tree-based models generally outperformed linear ones, though regularization helped improve Ridge and Lasso results. The project also explored feature importance, basic feature engineering, and visualized key trends in the data.

All code for training and evaluation is available in the linked Colab notebook. This report summarizes the workflow, key findings, and model comparisons in a clear and structured format.
