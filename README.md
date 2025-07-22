This project tackles a stock return prediction challenge based on a Kaggle competition by Winton Capital. Given anonymized features and short time windows of return data, the goal was to forecast intraday and short-term future returns.

The data was cleaned and analysed, distinguishing between categorical and numerical features, applying normalization, encoding, and clustering where needed. Despite testing a range of models—including linear regression, regularized regressions, tree-based models (like CatBoost and XGBoost), and even neural networks—the noisy data made it hard to beat a simple zero-return benchmark.

The best-performing models were simpler, with CatBoost using only numerical features showing the strongest results. Future improvements would likely come from better feature engineering or ensemble methods.
