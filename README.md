# fetal-healt-prediction
In this notebook i built, evaluated and compared three models to predict the correct classification (normal - suspect - pathological) of fetuses.
### Steps
1. preparation: dataset exploration with a focus on the target (unbalanced)
2. data cleaning: looking for missing values, deleting outliers, detecting collinearity
3. feature selection: mutual information and anova f-test
4. standardization and metrics choice
5. spot check: finding the 2 best models (logistic regression - random forest - k nearest neighbors)
6. hyperparameters tuning: grid search with built in cross validation
7. prediction and evaluation: with selected features and with all of them
