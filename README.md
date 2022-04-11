# Heart_disease_predictor
Is a Machine Learning model that predicts the Heart disease of a patient, based on certain features. With the use of the Logistic regression, an accuracy of 86.81% is achieved. The use of feature scaling also helped with the above accuracy.

## EDA results:
While analysing the data I found:
1. No **null** values.
2. Most of the rows were duplicated, so those duplicates were removed since their presence would lead to model overfitting, and hence a biased dataset.

## Feature Selection results:
The feature selection done through pearsons correlation matrix, shows that there is no feature with more than 85% correlation to another.

## Feature Scaling:
Feature scaling was performed on a subset of the dataset. This was because some of the features seemed out of the normal range of the dataset.
Standard scaler class was used for feature scaling.

## Training and fitting the model:
On training the logistic regression model, an accuracy of 86.8% was found on the split unseen dataset. 
This accuracy can further be increased by using a different type of scaler.
