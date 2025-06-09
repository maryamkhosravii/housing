# House Price Prediction using California Housing Dataset

## Project Overview
This project aims to predict house prices using the California Housing dataset. The dataset was preprocessed and then a regression model was built using XGBoost. Grid search was applied to optimize the model
parameters, but initial attempts showed worse performance. Further optimization is ongoing

## Data Preprocessing
The California Housing dataset was downloaded and loaded into a Jupyter Notebook. Preprocessing steps included removing columns with missing values and encoding the categorical column 'OceanProximity' using one-hot encoding (get_dummies). The data was then split into training and testing sets.

##  Model Training and Evaluation
An initial XGBoost regression model was trained, achieving the following RMSE scores:
- Training RMSE: 40783
- Testing RMSE: 49517
However, when grid search was applied for hyperparameter tuning, the RMSE worsened significantly:
- Training RMSE: 100928
- Testing RMSE: 100785

## Current Status and Future Work
The project is currently under active development to optimize the model performance. Efforts include revisiting hyperparameter ranges, feature engineering, and validation strategies to improve prediction accuracy.

## Usage
To run the project, load the data, perform preprocessing, train the model, and evaluate performance. Hyperparameter tuning is done via GridSearchCV from sklearn.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- xgboost
- jupyter
- joblib

## Author
Made with ❤️ by Maryam Khosravi
GitHub: https://github.com/maryamkhosravii




