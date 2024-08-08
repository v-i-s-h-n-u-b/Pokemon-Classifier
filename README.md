# Pokemon-Classifier
* Classifier to distinguish between Legendary and Non-Legendary Pok ́emon on a dataset with around 800 or more entries.
* Implemented and compared the following classification models: Random Forest, XGBoost, AdaBoost
  with feature scaling and hyperparameter optimization using a grid search.
  * hyperparameters to train the XGBoost classifier: n_estimators'
    'learning_rate','max_depth','subsample','colsample_bytree','gamma','min_child_weight'.
  * hyperparameters to train the AdaBoost classifier: n_estimators','learning_rate','base_estimator__max_depth','base_estimator__min_samples_split'.
* The accuracies achieved are ranked as follows: XGBoost ≥ AdaBoost ≥ RandomForest
* Also implemented a Neural Network to highlight they're limitations when it comes to classification problems.


NOTE: Scroll down past the training section of the XGB Classifier to view the remaining code
