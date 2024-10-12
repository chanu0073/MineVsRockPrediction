# MineVsRockPrediction
## Project Overview
This project demonstrates a binary classification model using Logistic Regression to predict whether an object is a mine or a rock based on sonar signal data. The dataset consists of sonar returns from 208 objects, and the goal is to classify them into two categories: Rock (R) or Mine (M).

## Dataset
The dataset for this project is sourced from Kaggle and contains sonar signal data. Each record in the dataset consists of 60 frequency-based attributes and a label that classifies the object as either a "Mine" or a "Rock."

Source: Kaggle <br />
Number of Features: 60 <br />
Number of Classes: 2 (Mine, Rock) 
## Libraries and Tools
Numpy: For numerical computations.
Pandas: For data manipulation and analysis.
Scikit-learn: For machine learning algorithms and model evaluation.
## Workflow
### Data Loading and Exploration:
Loaded the dataset using Pandas.
Explored the shape and summary statistics of the dataset.
### Data Preprocessing:
Split the data into features (X) and labels (Y).
Used train_test_split to divide the data into training and test sets (90% training, 10% testing).
### Model Building:
Implemented the Logistic Regression algorithm using Scikit-learn’s LogisticRegression module.
### Model Training and Evaluation:
Trained the model using the training dataset.
Evaluated the model's performance by calculating the accuracy score on the test dataset.
### Testing the Predictive System: 
Test the predictive system by providing input data to ensure correct classification.
# Conclusion
The Logistic Regression model provides a simple yet effective method for classifying objects based on sonar signal data. While this project serves as a fundamental introduction to classification using Logistic Regression, further improvements could be made by experimenting with other algorithms.
