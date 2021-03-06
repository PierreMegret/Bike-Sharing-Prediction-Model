# Bike-Sharing-Prediction-Model

## The project
Building a predictive model for the total number of hourly bike rentals in the bike sharing network of Washington, D.C.  Python was the programming language for this project.

## The code
The code is organized as follow: an exploration of the data, a k-fold cross-validation error to determine the best hyper-parameters of my model, and the predictions. 

## The data
The dataset provided was hourly rental data spanning two years with an exception of 2 months used as a testing set for predictions. I predicted the total count of bikes rented during each hour for the months of August and December 2012.

### Part 1. Exploration of the data
Looked at the features of the data as well as the existence of missing values.

### Part 2. Building of the Model
Built a Random Forest Regressor after having tuned it with a grid search cross-validation.

### Part 3. Predictions and model performances
Evaluated the model performances and predicated the total count of bikes rented in the test set.

## Results
Ranked first in a private Kaggle competition (22 participants).
