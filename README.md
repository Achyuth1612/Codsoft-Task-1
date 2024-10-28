# Codsoft-Task-1
TITANIC SURVIVAL PREDICTION

Task Description :

Use the Titanic dataset to build a model that predicts whether a passenger on the Titanic survived or not. This is a classic beginner project with readily available data.
The dataset typically used for this project contains information about individual passengers, such as their age, gender, ticket class, fare, cabin, and whether or not they survived.

Code Description :

This code builds a machine learning model to predict Titanic passengers' survival using a Random Forest Classifier. It starts by loading the dataset, filling missing values in the Age, Embarked, and Fare columns, and encoding categorical variables like Sex and Embarked. It then selects relevant features (Pclass, Sex, Age, Fare, SibSp, and Parch) as input variables (X) and Survived as the target variable (y). The data is split into training and testing sets, and the model is trained on the training data. Finally, it evaluates model performance on the test data by calculating accuracy, generating a classification report, and computing the AUC-ROC score.
