
# README for Twitter Sentiment Analysis Project

---

## Introduction
This project focuses on performing sentiment analysis on tweets using the `Sentiment140` dataset. The main objective is to classify the sentiments of tweets into positive, negative, or neutral categories.

## Dataset
The `Sentiment140` dataset is utilized, which contains columns like 'target', 'id', 'date', 'flag', 'user', and 'text'. For the scope of this project, the columns 'id', 'date', 'flag', and 'user' were deemed unnecessary and hence dropped.

## Data Preprocessing
The tweets underwent several preprocessing steps:
- Removal of URLs, usernames, and hashtags.
- Removal of non-alphabetic characters.
- Conversion to lowercase.
- Removal of stopwords.
- Lemmatization using `WordNetLemmatizer`.

## Data Visualization
- Pie and bar charts were used to visualize the distribution of positive, negative, and neutral sentiments.

## Feature Engineering
The text data was vectorized using a bag-of-words approach with the `CountVectorizer`.

## Model Training and Evaluation
Several machine learning models were trained and evaluated on the dataset:

1. **Multinomial Naive Bayes**:
   - Performance metrics and confusion matrix were generated to evaluate the model's efficiency.
  
2. **Logistic Regression**:
   - Performance metrics and confusion matrix were generated for evaluation.
   
3. **Gradient Boosting**:
   - Performance metrics and confusion matrix were used to gauge the model's performance.
   
4. **Random Forest**:
   - Evaluated using performance metrics and a confusion matrix.

## Conclusion
This project provides an end-to-end solution for performing sentiment analysis on tweets. It demonstrates the steps from preprocessing raw tweet data to training machine learning models and evaluating their performance.

---

