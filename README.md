# AML-Fake-Tweets

We used various machine learning techniques to identify fake tweets. We used Twitter APIs to
generate our data to ensure that our data replicates the real world scenario. We relied on the fact that
parody accounts tweet news which are generally fake, and the legitimate news accounts tweet real news.
To ensure that we had reliable and pre-labeled data from external sources, we utilized the Liar and Kaggle
Datasets (described below). In doing so, we obtained a mixture of real world tweets and news datasets,
which was then preprocessed using techniques such as limiting sentences to the first n words, and
incorporated the sentiment of the tweets in order to improve the performance. We observed that the LSTM
model performed the best to identify fake tweets with relatively higher accuracy and sensitivity
