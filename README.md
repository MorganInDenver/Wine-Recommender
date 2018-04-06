# Wine-Recommender

## Purpose of Project
This project uses a Kaggle database of over 129,000 wine reviews from Wine Enthusiast/Wine Magazine (https://www.kaggle.com/zynicide/wine-reviews). The data contains information related to variety, price, rating, and tasting notes. The goal of this project is to create a wine recommender based on item similarity, as I do not have access to user ratings.

## Process:
1.	Exploratory Data Analysis. In notebook #1, I deal with duplicates, null values, and generally explore the data available.
2.	Data Visualization. In notebook #2, I use Matplotlib, Seaborn, and Tableau and have great fun creating visualizations.
3.	Introduction to Natural Language Processing.  In notebook #3, I explore some NLP techniques, Count Vectorization and Term-Frequency/Inverse Document Frequency, and use Logistic Regression to predict the wine varietal Chardonnay using the written narrative/reviews. In notebook #4, I delve deeper into the Description variable, using Kmeans to explore whether clusters can be identified that match specific varietals. 

As of 4/6/18 - Still to come. I am working on the recommendation engine. I also wish to explore using DJango to create a user interface for users to interact with the recommender.
