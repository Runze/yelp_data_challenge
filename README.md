Yelp data challenge
===================
This is my first attempt at the [4th round Yelp data challenge](http://www.yelp.com/dataset_challenge) opened to students and researchers (although I'm neither). In this first attempt, I tried to use the reviews' text alone to predict the 5-star ratings by first computing the reviews' sentiment scores in a supervised fashion and then using the estimated scores to predict the 5-class outcome. Currently the model achieved a mean absolute error of 0.67 and an accuracy score of 0.48. In the future, I'm planing to incorporate more relevant information to improve the prediction power.

The IPython notebooks are hosted by nbviewer [here](http://nbviewer.ipython.org/github/Runze/yelp_data_challenge/tree/master/) and the individual files can be accessed directly below:
1. [Exploratory analysis](http://nbviewer.ipython.org/github/Runze/yelp_data_challenge/blob/master/1.%20explore_data.ipynb)
2. [Analyzing reviews](http://nbviewer.ipython.org/github/Runze/yelp_data_challenge/blob/master/2.%20parse_reviews.ipynb)
3. [Training models using the sentiment scores](http://nbviewer.ipython.org/github/Runze/yelp_data_challenge/blob/master/3.%20train_models.ipynb)
4. [Applying the model to the test set](nbviewer.ipython.org/github/Runze/yelp_data_challenge/blob/master/4.%20test_models.ipynb)
