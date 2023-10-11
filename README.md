# Titanic-Survival

## Overview
This repository contains Python code for predicting the survival of passengers on the Titanic. The model is built using a Decision Tree Classifier and is trained on the Titanic dataset. The features considered include passenger class, sex, age, and fare.

![image](https://github.com/Aditya3012Purwar/Titanic-Survival/assets/103439955/1c7a79ad-229b-401c-b14b-d2aebc834e6b)


## Dependencies
- Pandas
- Scikit-learn

## Dataset
The model is trained on the "titanic.csv" dataset. This dataset includes various features of passengers, and the target variable is whether the passenger survived or not.

## Preprocessing
The dataset is preprocessed to handle missing values and categorical features:
- Missing values in the 'Age' column are filled with the mean age.
- The 'Sex' column is label-encoded to convert it into numerical format.

## Model Training and Prediction
A Decision Tree Classifier is trained on the preprocessed dataset. The model's performance is evaluated, and it is used to make predictions.

## Code Explanation
- The dataset is loaded and preprocessed.
- Unnecessary columns are dropped to create the feature matrix X, and 'Survived' is considered as the target variable y.
- Missing values in 'Age' are replaced with the mean age.
- The 'Sex' column is encoded to numerical values.
- A Decision Tree model is trained and evaluated on the entire dataset.
- The trained model is then used to make predictions.

## Conclusion
This simple implementation serves as a baseline for predicting Titanic passenger survival. Further improvements can be made by tuning the model, feature engineering, and using more complex algorithms.
