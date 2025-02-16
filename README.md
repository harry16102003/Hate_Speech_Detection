# Hate_Speech_Detection

## Overview
This project detects hate speech in tweets using natural language processing (NLP) techniques. It preprocesses text data by removing noise, tokenizing, removing stopwords, and stemming. The processed data can be used to train machine learning models for classification.

## Dataset
The dataset used is HateSpeechData.csv, which contains tweets labeled for hate speech detection. Each tweet is categorized into one of the following classes:
* 0: Neutral or non-hate speech
* 1: Offensive language
* 2: Hate speech

## Features
* Text length analysis: Examines the distribution of tweet lengths across classes.
* Data preprocessing: Cleaning, tokenization, stopword removal, and text normalization.
* Exploratory Data Analysis (EDA): Visualization of tweet distribution and feature analysis.
* Machine Learning Models: Implementation of classifiers to predict hate

## Dependencies
To run this project, install the required dependencies:<br>
<b>pip install pandas numpy seaborn matplotlib nltk scikit-learn</b>

## Results
* Class imbalance: The dataset is skewed, with more instances in class-1.
* Text length insights: Hate speech tweets tend to have longer lengths.
* Model performance: Evaluation of different models for accuracy and precision.

## Future Improvements
* Implement deep learning models (e.g., LSTMs, Transformers) for better accuracy.
* Improve dataset balancing techniques.
* Deploy the model as a web application.
