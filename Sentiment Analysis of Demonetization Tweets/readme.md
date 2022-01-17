# Sentiment analysis of Twitter data: A machine learning approach to analyse demonetization tweets

With 500 Million Tweets sent each day, that is 6000 Tweets being generated every second, Twitter is the most popular micro-blogging site that allows users to express their views and opinions in 280 characters. As companies and political leaders take to the online social media platform to establish and develop their brand, one cannot ignore the amount to data being generated on Twitter. The proposed system aims to extract and analyse tweets, classify them as positive or negative with the help of machine learning techniques and algorithms, and finally subject to performance evaluation techniques. On November 8, 2016, in a television broadcast, Prime Minister Narendra Modi declared that all the 500 and 1000 rupee notes were illegal in an effort to curb black money and fake notes. Considering the demonetization dataset extracted from Twitter using Twitter API, pre-processing is performed using NLTK and Scikit-learn, which is then subjected to algorithmic executions such as Naive Bayes, Logistic Regression and Support Vector Machines. A comparison of this execution is considered to determine which algorithm works better for given dataset in terms of precision, recall, accuracy and F1 Score.

## Twitter data collection

The Twitter demonetization tweets are being collected using Tweepy package in python using the Twitter API.  

## Data pre-processing

Pre-processing involves removal of unimportant features from the data. In this phase, 
several techniques like Stemming and Stop word removal are applied to data set for noise reduction and facilitating feature extraction.

## Feature Extraction

Feature extraction is to extract features in a format supported by machine learning algorithms from datasets consisting of formats such as text and image. Feature extraction is carried out using
Bag of Words, TF-IDF (Term Frequency-Inverse Document Frequency) and N-grams

## Training the dataset and applying algorithms

The dataset is divided into training and testing set using KFold cross validation technique with the value of k set to 10. The project implements 3 algorithms for preparing and training the model.
They are Naive Bayes, Logistic Regression and Support Vector Machines

## Performance Evaluation
 
The dataset is then subject to evaluation in the following criteria: 
1 Accuracy is the most intuitive performance measure and it is simply a ratio of correctly predicted observation to the total observations. 
2 Precision is the ratio of correctly predicted positive observations to the total predicted positive observations. 
3 Recall is the ratio of correctly predicted positive observations to the all observations in actual class.
4 F1 Score is the weighted average of Precision and Recall. F1 score is more helpful than accuracy in uneven distribution.

## Observations and Conclusion
Classifying the sentiment of Twitter data has become a common yet an interesting challenge not only for data scientists but also for growing businesses. Also, the feature extraction techniques must be taken into account along with the workings of different algorithms in order to determine which is better. As a part of this work, a software solution has been developed that compares the different feature extraction techniques such as Bag of Words, TF-IDF and N-Grams. The cleaned dataset’s size has been varied and is subject to executions of Naive Bayes, Support Vector Machines and Logistic Regression.

Using a large dataset has showed improved accuracy and better outcomes. Naive Bayes performs satisfactorily but does not exceed expectations. Though Support Vector Machines gave better accuracy, its large execution time defeats the purpose of an efficient classifier. Logistic Regression performs as well as Support Vector Machines and takes as little time as Naive Bayes.  As Sentiment Analysis is a vast domain, there can be much scope in the detection of sarcasm in the tweets and also, stream tweets in real-time and give real-time analysis and results.
