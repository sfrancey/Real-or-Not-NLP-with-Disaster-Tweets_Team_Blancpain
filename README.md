# DM&ML Project: Real or Not NLP with Disaster Tweets 

## Team Blancpain

Gabin FLOURAC,
Sixtine FRANCEY,
Alexandre KEUSEN,

## Objective of the Project 🕵️

Our challenge is to build a Machine Learning Model that aim to predict which tweets are about a real disaster and which are not. 

To do so, we have access to a dataset of 6,471 tweets classified between real disasters (1) and not real disasters (0).

Our results are compared among all teams involved in this competition in order to get the best prediction possible. 

## Project Structure 🚀

Step 1: Load and visualize (EDA) 
- import the initial database 
- describe database 
- highlight distribution among features 

Step 2: Base rate of the initial database 

Step 3: Bases benchmark accuracies: train the model on the original dataset without any modification (basic model)
- Text preprocessing
- testing by using "Keyword" feature 
- testing by using Tweeets, "text" feature 
- testing by combining both Keywords and tweets features
--> Startegic conclusion 

Step 4: Improvement of our ML Model: data cleaning 
- Cleaning keywords (text processing)
- Cleaning Tweets (text processing)
--> Interative structure 

Step 5: Development of the modeling 
- logistic regression 
- kNN method 
- decision trees 

Step 6: Results presentation 

## Results 🥇 

- 1st submission: ...
- ...
- ...

## Accuracy evolution Graph

![](Data/progressiongraph.jpg)

1.   Iteration 1 : Find the base rate >> Accuracy = 0,57
2.   Iteration 2 : Working on Keywords >> Accuracy = 0,74
3.   Iteration 3 : Working on text >> Accuracy = 0,817
4.   Iteration 4 : Working on Keyword + Text >> Accuracy = 0,818
5.   Iteration 5 : Workig on Location >> Accuracy = 0,77
6.   Iteration 6 : Model and hyperparameters optimization >> Accuracy = 0,818
7.1  Iteration 7.1 : Working on Emojis >> Accuracy = 0,804
7.2  Iteration 7.2 : Working on spelling correction >> Accuracy = 0,79
