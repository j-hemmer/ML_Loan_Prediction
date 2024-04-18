# ML_Loan_Prediction
Training xgboost and random forest regression models to predict loan defaulters.
Data prep: one hot encoding, ordinal encoding/mapping, minmax scaler
EDA: correlation matrix, boxplots to look for outliers, printing unique values for categorical variables, checking for nulls
Models: used grid search to get best parameters and applied this to train the model.
- The threshold value for whether or not the prediction is default or not can be changed around
- The affects can be seen in the confusion matrix as well as the various metrics: accuracy, f1 score (auc does not change)
Results: Both models have high accuracy: 0.886 (both). The AUC was .725 (rf) and .753 (xgb). The models had very low f1 scores: .11 (both)
Depending on what the potential credit agency's goals this model may work as a good start despite such a low f1 score.
