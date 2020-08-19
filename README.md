# Kaggle_predict_game_rankings

Each entry is labeled according to its final average score in the "overall" category (from 1 to 5 stars, rounded to the nearest integer, or 0 if the game did not receive enough ratings to officially rank). This is a classification problem with 6 (unbalanced) classes.
___________________________________________________
I used **two methods** to predict the result. One is NN model, and another one is Random Forest.


1.**NN model** (script: "nn.ipynb", leaderboard public 0.93880)

Libraries need to install in your training environment: 

- tensorflow 1.12.0

- keras 2.2.4

- sklearn 0.23.1

- numpy 1.18.5

- pandas 1.0.5

- random

- csv


2.**Random Forest Classifier** (script: "random_forest.ipynb", leaderboard public 0.93207)

Libraries need to install in your training environment: 

- sklearn 0.23.1

- numpy 1.18.5

- pandas 1.0.5

- random
