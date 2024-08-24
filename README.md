# Game Review Sentiment Analysis

## Project Overview
This project focuses on sentiment analysis of game reviews, utilizing a range of machine learning and deep learning techniques. The sentiment analysis models categorize reviews into two sentiment classes: Positive, and Neutral. The project explores various models, from traditional machine learning algorithms to advanced neural networks like RNN, GRU, LSTM, and the ALBERT pretrained large language model, to assess their performance on this text classification task.

## Introduction
Sentiment analysis is a vital tool for understanding user feedback, especially in the gaming industry, where reviews can significantly impact a game's success. This project applies various machine learning and deep learning models to analyze game reviews and classify them into Positive or Negative sentiments. The project compares the performance of traditional algorithms with advanced neural network models, including a state-of-the-art ALBERT model, to identify the most effective approach for sentiment analysis.

## Dataset
The dataset used for this project consists of game reviews collected from various online platforms. The reviews are labelled into two sentiment classes:
- **Positive**: Reviews expressing a favourable opinion about the game.
- **Negative**: Reviews expressing an unfavourable opinion about the game.

The dataset is preprocessed by cleaning the text, removing stopwords, and converting the text into a format suitable for model input.

## Installation
To run this project, you will need to have Python 3.x installed along with the following libraries:

- pandas
- numpy
- scikit-learn
- PyTorch
- NLTK
- Spacy
- Gensim
- Transformers (for ALBERT)
- Matplotlib
- Seaborn

You can install the required packages using pip:
```bash
pip install pandas numpy scikit-learn torch nltk spacy gensim transformers matplotlib seaborn
