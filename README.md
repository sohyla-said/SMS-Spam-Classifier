# SMS Spam Classifier 🔍

A Machine Learning project that classifies SMS messages as "spam" or "ham" (not spam) using Natural Language Processing (NLP) techniques. This project implements both manual Bag-of-Words feature extraction and scikit-learn's vectorizers for comparison.

## 📋 Project Overview

This project demonstrates a complete NLP pipeline from raw text data to a functioning spam classification model. The key feature is the implementation of a **manual Bag-of-Words model** to understand the fundamentals of text vectorization.

## 🎯 Features

- **Text Preprocessing**: Cleaning and normalizing raw text data
- **Manual Feature Engineering**: Custom Bag-of-Words implementation from scratch
- **Multiple Models**: Naive Bayes and Logistic Regression classifiers
- **Performance Comparison**: Custom BOW vs scikit-learn's TF-IDF vectorizer
- **Interactive Testing**: Predict spam/ham on custom messages

## 📊 Dataset

**Source**: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

**Statistics**:
- Total messages: 5,572
- Ham messages: 4,825 (86.6%)
- Spam messages: 747 (13.4%)


## 🔧 Technical Implementation
### Phase 1: Data Preprocessing
- Lowercasing
- Special character removal
- Tokenization
- Stopword removal
- Stemming

### Phase 2: Manual Bag-of-Words
- Vocabulary building from most frequent words
- Word-to-index mapping
- Feature vector creation
- Count-based word representation

### Phase 3: Model Training
- Naive Bayes classifier
- Logistic Regression
- Train-test split (80-20)
- Performance evaluation

### Phase 4: Comparison
- Custom BOW vs scikit-learn TF-IDF
- Accuracy
- Confusion matrix analysis

## 📈 Results
### Model	Vectorizer:	Accuracy	
- **Naive Bayes	Manual BOW:**	~98%	
- **Logistic Regression	Manual BOW:**	~98%
- **Naive Bayes	TF-IDF:**	~96%

### 🎓 Learning Outcomes
- Core NLP Concepts
T- ext preprocessing pipeline
- Bag-of-Words model intuition
- Feature engineering for text data
- Model evaluation metrics

## Technical Skills
- Manual implementation of text vectorization
- scikit-learn for machine learning
- pandas for data manipulation
- Regular expressions for text cleaning
