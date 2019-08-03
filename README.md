# Same Side Classification

Testing different approaches for the task given here: https://github.com/webis-de/argmining19-same-side-classification

Rule-based approach: lemmatize the data and 2 lists of words (positive and negative words). Count the number of positive/negative words in each of 2 arguments to decide whether the argument is positive or negative, then mark if the arguments are on one side or not.

LightGBM: train LightGBM using different vectorizers and n-grams; choose the best option and use it for the test-data from GitHub.
