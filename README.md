# heart_disease_predictor
A machine learning model used to predict whether a person is suffering from heart disease. This model uses Logistic Regression to make predictions on the dataset.
This model solves a classification problem, which uses Logistic Regression along with feature scaling on a subset of features.

# EDA results:
While analysing the data I found:
[*] No **null** values.
[*] Most of the rows were duplicated, so those duplicates were removed since their presence would lead to model overfitting, and hence a biased dataset.

# Feature Selection results:
The feature selection done through pearsons correlation matrix, shows that there is no feature with more than 85% correlation to another.

# Feature Scaling:
Feature scaling was performed on a subset of the dataset. This was because some of the features seemed out of the normal range of the dataset.
Standard scaler class was used for feature scaling.

# Training and fitting the model:
On training the logistic regression model, an accuracy of 86.8% was found on the split unseen dataset. 
This accuracy can further be increased by using a different type of scaler.
