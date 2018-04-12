# Wine-Recommender

## Purpose of Project
This project uses a Kaggle database of over 129,000 wine reviews from Wine Enthusiast/Wine Magazine (https://www.kaggle.com/zynicide/wine-reviews). The data contains information related to variety, price, rating, and tasting notes. The goal of this project is to create a wine recommender based on item similarity, as I do not have access to user ratings.

## Process:
1.	Exploratory Data Analysis. In notebook #1, I deal with duplicates, null values, and generally explore the data available.
2.	Data Visualization. In notebook #2, I use Matplotlib, Seaborn, and Tableau and have great fun creating visualizations.
3.	Introduction to Natural Language Processing.  In notebook #3, I explore some NLP techniques, Count Vectorization and Term-Frequency/Inverse Document Frequency, and use Logistic Regression to predict the wine varietal Chardonnay using the written narrative/reviews. In notebook #4, I delve deeper into the Description variable, using Kmeans to explore whether clusters can be identified that match specific varietals. 
4. Recommender. This notebook houses the code for the recommender system. I use Fuzzy Wuzzy searching to improve the ability to search for a specific wine. I examine a few recommendations to understand how the content-based recommender is working. I also include an evaluation metric which takes the top 10 words common to each recommendation (using Count Vectorization) and calculates their average. On a sample of 100 recommendations, the top 10 words appeared on average 6.7 times among the 10 recommendations. This means that among 10 recommendations, they shared about 6 of the same words - which is how the recommender is judging their similarity. 

As of 4/12/18 - Still to come. Right now, the recommender exists in my Jupyter notebook. I will explore using DJango to create a user interface for users to interact with the recommender.
