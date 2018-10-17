# logistic_regression
Logistic Regression to predict benign vs malignant tumors. 
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-Learn

The objective of the project is to explore the sampled breast cancer data from the Wisconsin Breast Cancer database and predict if a tumor is benign or malignant. 
The data mainly describes the properties of the cell and its class. The model used for the prediction is a logistic regression regularized by L1  to avoid over-fitting.
The best features for the regression were selected by using a Recursive Feature Elimination model which given
the logistic regression model assigns weights to the features (predictors) to select the features with higher importance.
