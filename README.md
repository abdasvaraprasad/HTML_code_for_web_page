# Analysis of Spam and Non-Spam Text Messages.

## Abstract

Spam messages, which are frequently seen as digital annoyances, comprise a wide range of uninvited and unwanted communication sent through different digital channels like social media, text messaging, and emails.
This analysis comprises of analyzing text messages and categorizing if they are spam or non-spam messages. This is a process of analyzing, the users regarding text messages that they have received. 

## Beneficiaries

Organizations that can gain substantial advantages through this analysis include:
Technology companies.
Social media companies. 
Finance companies.
E-commerce companies. 
Telecommunication companies.

## Dataset Partition

The dataset was randomly partitioned into the following: Training (40%) – Validating (30%) – Testing (30%).
The table below describes the data partitions with respect to the target feature values, where there were 6182 records before data cleaning and 5572 records after the data cleaning.

## Data Cleaning

Preprocess Text: Convert messages to lowercase, remove punctuation/special characters.
Handle Duplicates and Missing Values: Check for and remove duplicate messages; fill in or remove missing values in "Class" or "Message".
Encode Categories: Transform "Class" into a numerical format for analysis; 0 is Non-Spam, 1 is Spam

## Data Mining

Exploratory Analysis: Examine the balance of spam vs. non-spam messages and identify frequent words in each category.
Feature Extraction: Use BoW or TF-IDF to convert text messages into a numerical format that models can interpret.
Model Building: Apply classification algorithms (e.g., Naïve Bayes, Logistic Regression, Random Forest Classifier) to distinguish between spam and non-spam messages.
Evaluate and Optimize: Measure model performance with confusion matrix for Accuracy, Sensitivity, Precision and Specificity.
Footnote Definitions:
BoW (Bag of Words): This method turns text into a list of words without considering the order. Imagine dumping all the words from a message into a bag; each word is counted but where it was in the message doesn’t matter.
TF-IDF (Term Frequency-Inverse Document Frequency): A way to score the importance of words in a message based on how often they appear in that message but less often in all other messages. It helps figure out which words are special in a particular message compared to all messages.

## Summary

![alt text](image.png)

