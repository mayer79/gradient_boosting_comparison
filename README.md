# Features of Major Gradient Boosting Implementations

Selection of features of major gradient boosting implementations [XGBoost](https://github.com/dmlc/xgboost), [LightGBM](https://github.com/microsoft/LightGBM), and [CatBoost](https://github.com/catboost/catboost) for Python and R.

Aspect         | XGBoost       | LightGBM      | CatBoost
:------------ | :-------------| :-------------| :-------------
Speed: CPU  |  | :two_hearts:  |
Speed: GPU  | :heart: |   | :two_hearts:
Standard losses | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Special loss: Poisson/Gamma/Tweedie |:heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Special loss: Survival| :heavy_check_mark: ||
Special loss: Robust | |  :heavy_check_mark: | :heavy_check_mark:
Special loss: Quantile ||:heavy_check_mark:|:heavy_check_mark:
Tree size regularization | :heavy_check_mark:| :heavy_check_mark:| :heavy_check_mark:
Categorical input handling | | :heart: | :two_hearts:
Constraints: monotonic  | :heavy_check_mark: |  :heavy_check_mark: | :heavy_check_mark:
Constraints: interaction  | :heavy_check_mark: |     :heavy_check_mark:      | 
Case weights | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Missing values | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Interpretation: Importance |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:
Interpretation: SHAP | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Cross-validation | :heavy_check_mark: | :heavy_check_mark: | Python only
Special mode: Random Forest | :heavy_check_mark: | :heavy_check_mark: |
Special mode: Linear booster | :heavy_check_mark: | :heavy_check_mark: |
Installation easy | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Initial public release | 2014 | 2016 | 2017

This compilation as per Oct 10, 2022 is neither complete nor does it claim to be correct.

- Update as per July 5, 2020: LightGBM has implemented interaction constraints, hurray :-).
- Update as per Sept. 25, 2020: LightGBM is on CRAN, hurray again!
- Fixed initial release year of LGB

