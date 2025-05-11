# Python_IPL_Winning_Team_Prediction_Model
# IPL Winning Team Prediction
A simple machine learning model that predicts the winning team in an IPL match based on current game context. This is a classification project that uses historical IPL data to predict match outcomes. It demonstrates how to use preprocessing techniques and Logistic Regression to make real-time win predictions.

# Dataset
matches.csv  
deliveries.csv  
Source: Kaggle - IPL Dataset

# Problem Statement
The goal is to predict the probability of a team winning the match given certain features like batting team, bowling team, venue, target, runs scored, wickets lost, overs, runs in last 5 overs, and wickets in last 5 overs.

# Features Used
After preprocessing and feature engineering, the final dataset includes:
Batting team, Bowling team, City, Runs left, Balls left, Wickets left, Target, Current run rate, Required run rate, Result (Win/Loss)

# ML Workflow
Preprocessing with OneHotEncoder for categorical features  
Logistic Regression model using scikit-learn pipeline  
Train-test split with 80-20 ratio  
Evaluation using accuracy score and predicted probabilities

# Model Performance
Accuracy: ~80%  
Model: Logistic Regression (liblinear solver)  
Tech Stack  
-Python  
-Pandas  
-NumPy  
-scikit-learn  
-Jupyter Notebook
