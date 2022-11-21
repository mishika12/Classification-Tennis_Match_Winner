# Tennis Classification
Introduction
Tennis is very popular sport which is enjoyed and worshiped by fans from all over the world. There are 4 major tournaments known as the grand slam tournaments namely the Wimbledon, Australian Open, US Open and French Open. It is usually played by players on three different types of surfaces (Clay, Hard,Grass). Tennis is an extremely unpredictable sport where each player has a unique style and technique which makes the game even more interesting and challenging to predict the winner.
Today, machine learning is used in many sports such as soccer, cricket, baseball, tennis etc. As we know data is everywhere and tennis is defined by data, and machine learning techniques are already making waves in the field of tennis not only for professional players but also for coaches, fans and potential bidders.The statistical analysis has helped to remodel the game of tennis by diving deep in to the insights of the game and predicting the results with great accuracy. This has not just increased the efficiency of the betting markets but also helped players and coaches to get better understanding about the game.
Problem Statement
The objective of this project is to analyze last 20 years of data and answer the following questions:
1. Find the top 10 players over the years across all grand slam tournaments based on their average rankings and which country do they hail from?
2. Find the number of right or left hand players in the dataset
3. Find the longest match ever played in the 20 years across the four grand slams?
4. Number of aces, double faults, break points faced and saved across tournaments in last 20 years
5. Correlation between various variables and winning
6. Trajectory of best player over the years, which is Roger Federer
In addition to this analysis, the project is aimed to develop predictive models and understand what are the key factors that impact the winning or losing of tennis player based on their past performance. The following classfication algorithms will be used to develop the models:
1. Logistic Regression
2. KNN
3. Support Vector Classifier
 localhost:8889/notebooks/Desktop/Classification_Tennis/Tennis Winner Prediction .ipynb 1/33
18/11/2022, 22:37 Tennis Winner Prediction - Jupyter Notebook
pp
4. Naive Bayes
5. Decision Tree Classifier 6. Random Forest Classifier
Dataset Description
For the purpose of the project, we consider three datasets:
1. Match.csv- It contains all the match level data. For eg:round, tournament, year of tournament etc.
2. Player.csv- It contains all the details pertaining to each player. For eg: Birthday, playing hand, country etc.
3. Stats.csv- It has all the data from all the matches played by each player. For eg: aces, break points won/
saved, rank, points etc.
Datasets have data from 2000 Aus Open - 2019 US Open for only ATP
