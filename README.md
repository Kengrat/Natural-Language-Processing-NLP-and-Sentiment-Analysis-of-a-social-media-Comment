# Natural Language Processing (NLP) and Sentiment Analysis of a Tweet social media Comments
# Natural Language Processing is a data science and data mining technique that allows computers to understand language naturally, as a person does.
# In this project, we employed data cleaning and data exploratory techniques to improve the accuracy of the models used and sentiment analysis is deployed to detect the underlying sentiment in the text. Sentiment Analysis is the process of classifying text as either positive, negative, or neutral. Machine learning techniques are used to evaluate a piece of the text and determine the sentiment behind it.
# Tweet CSV data is a compilation of social media tweet comments on a particular product, the CSV file is named task6. task6 contains 40,000 rows of comments in 2 columns i.e. tweet column and sentiment column. Because the dataset is very large, 10,000 data are randomly selected and named dataset and deployed for this study. sentiment analysis is imported to process the text in the tweet column and return sentiment as output sentiment then categorize the text in the tweet as negative (0) or positive sentiment (1).
# There were 4,989 negative and 5,011 positive sentiments which comprised the randomly selected 10,000 data, Word cloud of dominant negative sentiments are: "day", "now", "today", and "work" while dominant positive sentiments are: "quot", "thank", "love". 
# Data Cleaning methods including removing punctuation using a regular expression, stemming and stopwords were applied to improve the words and increase evaluation metrics and accuracy.
# Six classifiers including SVM, Random Forest, KNN, Decision Tree, Logistic Regression and Naive Baise were deployed to test the model as 33% of the dataset is used as the test set while 67% is used as a train set. 
# SVM model sensitivity (positive class) is 78% while the specificity (negative class) is 66% The overall accuracy of the SVM model classifier is 72% 
# Random Forest model sensitivity (positive) is 76% while the specificity (negative) is 67% The overall accuracy of the Random Forest Model is 71% 
# K Nearest Neighbour model sensitivity is 54% while the specificity is higher at 71% The overall KNN accuracy of the model is 62%.
# Decision Tree Classification sensitivity (positive class) is 70% while the specificity (negative class) is 64% Overall decision Tree accuracy of the model is 67% 
# Logistic Regression model sensitivity (positive class) is 74% and specificity (negative class) is 70%, the overall accuracy of the Logistic Regression model is 72% 
# Naive Baise sensitivity (positive class) is lower at 26% and higher specificity (negative class) at 83%, the Overall accuracy of the Naive Baise model is 55% 
# Logistic Regression is the best model with balanced accuracy for sensitivity and specificity and an overall accuracy of 72%. SVM Overall accuracy is also 72%.
