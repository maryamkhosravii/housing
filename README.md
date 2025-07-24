# House Price Prediction using California Housing Dataset

## Project Overview
This project aims to predict house prices using the California Housing dataset. The dataset was preprocessed and then a regression model was built using XGBoost. Random search was applied to optimize the model
parameters. (Further optimization is ongoing)

## Data Preprocessing
The California Housing dataset was downloaded and loaded into a Jupyter Notebook. Preprocessing steps included filling missing values with median, Checking outliers and Multicollinearity, and encoding the categorical column 'OceanProximity' using one-hot encoding (get_dummies). The data was then split into training and testing sets.

##  Model Training and Evaluation
simple model RMSE: 47676.68589556266
optimized model RMSE: 47676.68589556266

## Current Status and Future Work
The project is currently under active development to optimize the model performance. Efforts include revisiting hyperparameter ranges, feature engineering, and validation strategies to improve prediction accuracy.
Integrate a full ml pipeline for data preprocessing, training and evaluation.
API development
Dockerization
DataBase Integration

## Usage
To run the project, load the data, perform preprocessing, train the model, and evaluate performance. Hyperparameter tuning is done via RandomSearchCV from sklearn.

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




