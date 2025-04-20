# Personality Prediction System using Machine Learning (MBTI)

This project is a Personality Prediction System that uses machine learning techniques to classify individuals into one of the 16 Myers-Briggs Type Indicator (MBTI) personality types based on text data (e.g., social media posts, essays, etc.).
## Overview

The goal of this project is to create a predictive model that can determine a person's MBTI personality type from their text. This can be useful in areas like mental health, HR screening, marketing, and social networking.

## MBTI Background

The MBTI categorizes people into 16 types based on four dichotomies:
- *I/E*: Introversion / Extraversion  
- *N/S*: Intuition / Sensing  
- *F/T*: Feeling / Thinking  
- *P/J*: Perceiving / Judging

Example: *INTJ, **ENFP*, etc.

## Tech Stack

- *Language:* Python
- *Libraries:* pandas, scikit-learn, nltk, seaborn, matplotlib
- *ML Models:* Logistic Regression, Random Forest, SVM 
- *NLP Techniques:* Tokenization, Stopword Removal, TF-IDF

## How It Works

1. *Preprocessing:* Clean and prepare the text data (removing URLs, stopwords, etc.)
2. *Feature Extraction:* Convert text to numeric features using TF-IDF
3. *Model Training:* Train classifiers to predict each of the 4 MBTI dimensions
4. *Prediction:* Combine outputs to form the full personality type

## Dataset

- Public MBTI dataset from Kaggle (contains ~8600 rows of user posts with personality labels)
- Link: [MBTI Personality Dataset](https://www.kaggle.com/datasnaek/mbti-type)

