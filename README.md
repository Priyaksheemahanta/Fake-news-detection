# Fake-news-detection
## METHODOLOGY 
### 3.1. Response based detection 

Fake news generally carries strong sentiments and thus circulates in no time on  social media. Response based technique takes into consideration the collected responses on tweets/posts to determine the credibility of the news. This project has  progressed in two phases. In the First Phase, I implemented the higher posterior  probability method on the article‟s body and headlines. Although, I observed higher  accuracy results, I found this method to be not very efficient because there is  possibility that Fake news can appear in a well-written article. In the second phase, I  proposed approach to classify fake news more accurately by analyzing the response on  such news articles”. Implementation of the same was carried out in five sub phases: 
1) Collection of data from social media platform, Facebook and Twitter 2) Choosing relevant features for classification and Training the Model 3) Evaluation of different model performance based on extracted features 4) Improving performance 
5) Discussion and Presentation of results 
This project was developed in Python using Sci-kit libraries. Python has a huge  set of libraries and extensions, which can be easily used in Machine Learning. Sci-Kit  Learn [6] library is the best source for machine learning algorithms where nearly all  types of machine learning algorithms are readily available for Python, thus easy and  quick evaluation of ML algorithms is possible.
## Brief introduction to the algorithms 
### Naïve Bayes:

This classification technique is based on Bayes theorem, which assumes that the presence of a particular feature in a class is independent of the presence of any  other feature. It provides way for calculating the posterior probability. 
### Passive Aggressive Classifier: 

The Passive Aggressive Algorithm is an online  algorithm; ideal for classifying massive streams of data (e.g. twitter). It is easy to  implement and very fast. It works by taking an example, learning from it and then  throwing it away.  
### Logistic Regression:

Logistic regression is a classification algorithm, used to predict  the probability of occurrence of an event (0/1, True/False, Yes/No). It uses sigmoid function to estimate probabilities. 
### Support Vector Machine: 

In this algorithm, each data item is plotted as a point in n dimensional space (n is the number of features). Values of each feature are the value of  each co-ordinate. It specifically extracts a best possible hyper-plane or a set of hyper planes in a high dimensional space that segregates two classes. Linear kernel was used  for SVM in this work. 
### Stochastic Gradient Descent:

A SGD algorithm starts at a random point, updates the  cost function with each of the iteration using one data point at a time and builds a 
classifier with progressively higher accuracy given a large dataset. In SGD, a sample  of training set or one training value is used to calculate parameters, which are much  faster than other gradient descent.
