# Urdu Sentiment Analysis NLP Pipeline

## Overview
This project focuses on the development of an **Automatic Sentiment Analysis Tool for Urdu Text** from social media platforms like Twitter, Facebook, Instagram, and YouTube. The tool classifies posts into **positive**, **negative**, or **neutral** sentiments and addresses various challenges associated with the Urdu language, such as complex grammar, morphology, and noisy social media data.

### Key Features
- Custom Urdu stopword removal
- Preprocessing techniques for handling punctuation, emojis, URLs, and hashtags
- Stemming and lemmatization for Urdu words
- Tokenization and feature extraction using **TF-IDF** and **Word2Vec**
- N-gram analysis (unigrams, bigrams, and trigrams)
- Sentiment classification using machine learning models like **Logistic Regression** or **Naive Bayes**
- Performance evaluation using accuracy, precision, recall, and F1-score

## Phases of Development
1. **Text Preprocessing for Urdu Text**
   - Removal of Urdu stopwords, punctuation, emojis, URLs, and hashtags
   - Filtering short posts with less than three words
   - Handling special characters and spelling variations

2. **Stemming and Lemmatization for Urdu Text**
   - Implemented custom algorithms for Urdu stemming and lemmatization to reduce word variants to their base forms

3. **Feature Extraction**
   - Tokenization of Urdu text
   - TF-IDF algorithm to extract important terms contributing to sentiment
   - Word2Vec model trained on the dataset

4. **N-gram Analysis**
   - Analyzed unigrams, bigrams, and trigrams to identify common patterns in the dataset

5. **Sentiment Classification Model**
   - Built machine learning models to classify sentiment based on features extracted
   - Evaluated the models with accuracy, precision, recall, and F1-score

6. **Evaluation & Optimization**
   - Tested the models on a validation set and identified areas for improvement

## Tools and Libraries
- **Python**
- **NLTK**, **spaCy**, **Polyglot** , **LughaatNLP** for text processing
- **Scikit-learn** for machine learning models
- **Gensim** for Word2Vec
- **pandas**, **matplotlib** for data analysis and visualization

## Dataset
A publicly available dataset of Urdu social media posts was used for this project, such as the [Urdu Twitter Sentiment Dataset](https://www.kaggle.com/). The dataset contains raw social media posts and their corresponding sentiment labels (positive, negative, neutral).

## Getting Started

### Prerequisites
- Python 3.x
- Install dependencies using:
  ```bash
  pip install -r requirements.txt
