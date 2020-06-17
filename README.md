# machine-learning-challenge

This challenge requires the Data Scientist to apply two different models to a dataset on exoplanets.

The first model will be on random forests as it is a very powerful ML algorithm for recommendations and appears to be the standard for ML.

The second model uses Descision Tree Classifiers as the nature of the data set is either Confirmed, False Positive, or Candidate.

## The First Model: Random Forests Classifier
I thought that the random forests would make the task of learning the data reletively straight forward as you you are determining if a planet based upon the data.  Random Forests are also considered quite powerful and work well with supervised learning.  One downside of them is that implementing them is slow and requires a lot of compute power.

The best parameters for this model is be having 240 estimaters(n_feaures) and the maximum features being sqrt according to Sci-Kit Learn's GridSearchCV class. This gave an accuracy of 73.5%.  In a real world test, this gave a score of 69.3% with the test data. 

## The Second Model: Decision Tree Classifier
Decision Tree Classifiers are . This was a faster and less accurate than the Random Forests Classifier and are more prefered as a result.  The best parameters for this is where the max depth is 7 and the minimum samples split is 70.  This provides the model with a testing score of 67.5% with the test data.