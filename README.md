# UnSriptRookies22_Archarios
UnScript Rookie’s Hackathon 2022. An Exclusive Hackathon for 2nd Year Engineering Students

## AIML Problem Statement:
### Financial Management System:
The Financial Management System is a software that is used to check the 
authenticity of a particular transaction in a financial company.
In Financial Management System, participants must create a model for 
predicting fraudulent transactions for a financial company and then use the model's 
insights to create an actionable plan. The case's data is stored in a CSV file with 
6362620 rows and 10 columns.

We imported the data from the csvfile and perform some analysis on it to find certain trends.
We then used CatBoostClassifier to create a model which we trained.
We then shifted to XGBoost which is better for numeric values.
XGBoost applies a better regularization technique to reduce overfitting, and it is one of the differences from the gradient boosting. The xgboost.XGBClassifier is a scikit-learn API compatible class for classification. We created our machine learning model using XGBClassifier. 
We then performed some more manipulation of the date and the passed the fields to the model.
