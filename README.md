# Stroke-Prediction
This has code for stroke prediction using ML algorithms
This reads the dataset from Kaggle and the dataset has 5110 rows and 12 columns.
Feature engineering is done on the dataset and id column is dropped as it will not contribute to the analysis. 
EDA is done to understand the data and how the data is spread.
Since the datset is imbalanced SMOTE-ENN is applied to balance. 
Classification algorithm is tried on the datset like logistic, Random forest, Decision trees, ADA, XGBoost, Neural network.
Hyper parameter tuning is tried such as Random search and Bayesian cv.
Finally XGBoost and Neural networks gives good recall score.
