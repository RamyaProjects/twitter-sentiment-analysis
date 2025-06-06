# Twitter Sentiment Analysis using NLP & ML
**overview**:

This project applies Natural Language Processing (NLP) techniques and Machine Learning models to classify tweets as positive or negative based on their sentiment. It includes extensive preprocessing, vectorization using TF-IDF, model training (Logistic Regression and Naive Bayes), evaluation, and visualization using WordCloud.

**Features**:

- Cleaning and preprocessing of tweet text
- Tokenization, lemmatization, and stemming
- Stopword and punctuation removal
- TF-IDF vectorization with bi-grams:In this project,TF-IDF (Term Frequency–Inverse Document Frequency) vectorization is used to transform cleaned tweet text into numerical features suitable for machine learning models.TF-IDF is a statistical method used to evaluate the importance of a word in a document relative to a collection (or corpus) of documents.
- Model training: Logistic Regression & Bernoulli Naive Bayes
- Performance evaluation using F1 Score, Accuracy, Precision, and Recall
- WordCloud visualizations for sentiment classes-To better understand the most frequently occurring terms in positive and negative tweets, WordClouds is used as a form of text-based data visualization.
- Confusion matrix visualization

**Tech Stack**
- Language: Python
- NLP Tools: spaCy, nltk
- ML Models: sklearn (LogisticRegression, BernoulliNB)
- Visualization: matplotlib, seaborn, wordcloud

**Preprocessing Steps**
- Remove punctuation, numbers, URLs, hashtags, and mentions
- Convert text to lowercase:Convert all characters to lowercase to ensure uniformity.
- Tokenize using spaCy:Splits the text into individual tokens using spaCy.
- remove stopwords:Eliminates common but uninformative words like the, and, is, etc.
- Lemmatize using spaCy :Converts words to their base or dictionary form.
- stem using nltk.PorterStemmer:Reduces words to their root form using PorterStemmer.
- Remove empty or duplicate cleaned tweets

**Feature Engineering**
- TF-IDF vectorization with bigrams
- Max features: 100,000
- Train-test split: 80-20
