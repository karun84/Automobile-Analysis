# Automobile-Analysis

This project describes a Chinese automobile company which aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US counterparts.
The main objective of this project is to:
     1. Which variables are significant in predicting the price of a car
     2. How well those variables describe the price of a car

Steps involved:

1. Preprocessing
   Did some basic preprocessing like checking for duplicates, missing values and if there is any outliers.

2. Model Implementation
   Implemented the following models:
     - Linear Regression
     - Decision Tree Regressor
     - Random Forest Regressor
     - Gradient Boosting Regressor
     - Support Vector Regressor

3. Model Evaluation
   Compared the performance of each model based on its R-Squared, Mean Squared Error(MSE) and Mean Absolute Error(MAE).
   Found out that out of all the regressors Random Forest Forest Regressor performed better as the dataset is small and this regressor shines in this aspect giving good predictions.

4. Feature Importance Analysis
   Found that engine size and horsepower plays an important role in determing the price of a car.

5. Hyperparameter Tuning
   Used GridSearchCV to fine-tune the performance of the model and discovered that it is an excellent fit.

Conclusion
 Here Random Forest Regressor was the best regressor for this dataset and solved the objectives.
   
   
