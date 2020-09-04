# Watch Better Movies Incorporated 
[]!(img/leo-pointing.jpg)
#### presented by Andrew Means and Jacob Hei


# Abstract
Tired of scrolling to infinity? So were we.  That is, until we developed a movie recommendation model capable of accurately predicting a given user's rating for a new movie based on past ratings, as well as the capability to handle the cold start problem of new movies or new users who have not yet rated movies.  This repository will go through rating prediction methods and accuracy for content-based, similarity-based, and matrix factorized models and display a given user's top 5% rated movies.  

# Overview
 - Understanding the data
 - first simple model
 - matrix facorization
 - random forest model
 - 

 





# EDA
Datasets used in building the model
1) training set of 800,000 instances of movie ratings from ___ users on ___ movies
2) movie database with genre description tags
3) kaggle database with tfidf vectorized plot description words





# Item-item Similarity Model
To explore how our more complex models captured the signal from the noise we needed an initial model to compare it to.  Item-item similarity is a fine comparision 




# Graphing Users






# Matrix Factorized ALS Model

RMSE values for varying k values:

Adjusting rank: we sampled a few different rank values to see how accurate our model could be with a smaller rank to avoid overfitting to our training set and better generalizing.  


hyper parameter adjustments by including bias factors for dampened mean, rating bias adjustment, and regularization learning rate.

[]!(img/alssummary.png)
[]!(img/alspredtable.png)
[]!(img/rmses.png)

# Random Forest Model
We decided it would be prudent to add in other features to our recommendation model.
The context of the information we have on users as well as tfidf vectorized words of plot description would allow our model to better pick up on the nuances left out by sparse ratings matrix.  




# Testing the model on unseen data



# Conclusion