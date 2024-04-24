# SC1015_MiniProject
Welcome to Yu-Gi-Oh analysis repository

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on a collectible card game Yu-Gi-Oh data from Kaggle taken from ygoprodeck.com, an online repository for Yu-Gi-Oh cards. 

## Contents
1. [Data introduction and extraction]
2. [Data preparation and cleaning]
3. [Data visualisation, EDA and additional cleaning]
4. [Machine learning]

## Contributors
- @16fb – Corelation Matrix and Linear Regression
- @Iain-Lim – EDA on Categorical Variables and Decision Tree
- @leon0242 – EDA, Data Preparation, and Cleaning

## Problem Definition
- Can we use data to confirm this trend, do creatures with high attack and defense have high levels?
- Are we then able to predict a monster’s level from its attack and defense?
- Is it true that the level of a card impacts the price of a card?
- What other attributes of a card can we use to determine its price? Are we able to predict the price of a card from its attributes?

## Models Used
1.	Linear regression
2.	Binary classification
3.	EDA of categorical variable

## Conclusion
- The numerical variables [level], [attack] and [defense] are correlated.
- It is possible to predict a monster’s [level] using linear regression (R^2 of 0.6), or if it requires a [sacrifice] using binary classification (0.89 Classification Accuracy). 
- The conception that “boss monsters” have high attack or defense, is mostly true.
- The variables [level], [attack] and [defense] are only slightly correlated with [price].
- The conception that “boss monsters” have a high price, is unable to be verified. One should thus be wary of that assumption.
- The card [price] is not being strongly correlated with other numerical values and does not have distinct separations when EDA of categorical values were performed. 
- The classification model we generated was better than random guessing but is still not a very good model.

## What did we learn from this project?
- Other packages such as json
- Collaborating using GitHub

## References
- Thor, T. A. (2023, October 19). Yu-Gi-Oh! trading cards dataset. Kaggle. https://www.kaggle.com/datasets/tathor/yugioh-trading-cards-dataset 
