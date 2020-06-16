# machine-learning-challenge

This challenge requires the Data Scientist to apply two different models to a dataset on exoplanets.

The first model will be on random forests as it is a very powerful algorithm for recommendations and appears to be the standard for ML.

The second I want to dive into Deep Learning with TensorFlow and be experimenting with it to see how many hidden layers is too much.

## The First Model: Random Forests Classifier
I thought that the random forests would make the task of learning the data reletively straight forward as you you are determining if a planet based upon the data.  Random Forests are also considered quite powerful and work well with supervised learning.  One downside of them is that implementing them is slow and requires a lot of compute power.

The best parameters for this model is be having 260 estimaters(n_feaures) and the maximum features being log<sub>2</sub><sup>n</sup> according to Sci-Kit Learn's GridSearchCV class.

## The Second MOdel: Deep Learning with Linear Regression
