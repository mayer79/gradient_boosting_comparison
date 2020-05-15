# Features of Major Gradient Boosting Implementations

Selection of features of major gradient boosting implementations for Python and R as per May 15, 2020.

Aspect         | XGBoost       | LightGBM      | CatBoost
:------------ | :-------------| :-------------| :-------------
Speed: CPU  |  | :two_hearts:  |
Speed: GPU  | :heart: |   | :two_hearts:
Standard losses | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Special loss: Poisson/Gamma/Tweedie |:heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Special loss: Survival| :heavy_check_mark: ||
Special loss: Robust | |  :heavy_check_mark: | :heavy_check_mark:
Special loss: Quantile ||:heavy_check_mark:|:heavy_check_mark:
Tree size regulation | :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:
Categorical input handling | | :heart: | :two_hearts:
Constraints: monotonic  | :heavy_check_mark: |  :heavy_check_mark: | :heavy_check_mark:
Constraints: interaction  | :heavy_check_mark: |          | 
Case weights | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Missing values | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Interpretation: Importance |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:
Interpretation: SHAP | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Cross-validation | :heavy_check_mark: | :heavy_check_mark: | Python only
Special mode: Random Forest | :heavy_check_mark: | :heavy_check_mark: |
Special mode: Linear booster | :heavy_check_mark: | :heavy_check_mark: |
Installation easy | :heavy_check_mark: | Python only | :heavy_check_mark:

This compilation is neither complete nor does it claim to be correct.
