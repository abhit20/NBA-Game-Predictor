# NBA Games' Outcome Machine Learning Model
#### A CSE 482 Project

Data and Code for "NBA Game Predictor"

## Abstract

The objective of this project was to create a model that can predict the winner of an NBA game. The data was collected from basket- reference and ESPN. To achieve this, we gathered data for each match from the 2017-2018 season which is a total of 1230 games for training the model and used 410 games played in 2018 from the 2018-2019 season for evaluating the model. All this data was preprocessed, and 52 feature vectors were created based on the averages of each teams last 7 games. The model was a classification problem solved through logistic regression, so the winner of each game was the predictor. 1 if the home team won and -1 if the away team won. First it was performed without sampling. The outcome of that model was 61.74% split between the home and away team. After that, sampling with replacement was performed to see if there could be a better outcome. The outcome of sampling with replacement was 64.98% split. The sampling with replacement model provided a much better outcome for the predictor than the model without sampling.
