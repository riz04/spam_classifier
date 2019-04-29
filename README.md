# Spam Classifier

Spam mail classifier using different ML algorithms :mailbox_with_mail:

## Description

A spam classifier program in python which can tell whether a given message is spam or not.
We can do this by using a simple Logistic Regression Model, but the results will not be very effective. 
So, we use bag of words technique, where more emphasis is given to the words with higher tf-idf score.

## Algorithms Used

Created different Jupyter files where I tried different **ML Algorithms** to enhance the accuracy.The following alogrithms were used:

- LogisticRegression
- Naive Bayes
- Support Vector Machine
- TF-IDF Vectorizer

## Process

Here you can find the details of the process folowed to build the model

- Loaded the data
- Checked for missing values
- Used **Matplotlib** and found insights by doing exploratory data analysis
- Splitted the data into train and test datasets

## About Accuracy

Checked accuracy using different techniques. The results of confusion matrix and classification report for all techniques were not very effective because we have lot of stopwords in the messages and their frequency is also very high that can be the reason for retarted accuracy. Therefore, used **Bag of Words** approach. 

Finally, 

- Craeted a pipeline of TF-IDF Vectorizer
- **Achieved accuracy of almost 99%** :star2:



