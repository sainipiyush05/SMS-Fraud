# SMS-Fraud

# SMS Fraud Detection

This project implements a machine learning-based system to detect and classify SMS messages as normal, hate speech, or offensive. The model uses various text processing techniques and classification algorithms to achieve high accuracy and precision.

Project Overview

The dataset consists of labeled SMS messages categorized into the following classes:

Normal: Regular, non-offensive messages.

Hate Speech: Messages containing hate-inducing content.

Offensive: Messages with offensive language.

The project involves:

Data Preprocessing: Cleaning and transforming text data.

Feature Engineering: Extracting numerical features from text using techniques like TF-IDF and CountVectorizer.

Model Building: Using machine learning models like Naive Bayes, SVM, Random Forest, and others.

Evaluation: Comparing models using accuracy, precision, and confusion matrices.
Features

Text Preprocessing:

Lowercasing
Tokenization
Stopword Removal
Stemming using PorterStemmer

Visualization:

Word Clouds for each class.
Histograms and Pair Plots to understand feature distributions.

Classification Algorithms:

Naive Bayes (Gaussian, Multinomial, Bernoulli)

Support Vector Machines (SVM)

Random Forest

Gradient Boosting

Voting and Stacking Classifiers for ensemble learning.

$ Performance Metrics:

Accuracy

Precision
Confusion Matrices
