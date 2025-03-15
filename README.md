# Amazon Reviews Sentiment Analysis

## Overview
This project performs sentiment analysis on Amazon product reviews using both traditional and transformer-based methods. The dataset is analyzed to extract user behavior insights and review distributions.

## Table of Contents
1. Data Loading & Initial Exploration
2. Data Analysis & Visualization
3. Text Length Analysis
4. NLTK-Based Sentiment Analysis (VADER)
5. Visualization of VADER Sentiment Scores
6. Transformer-Based Sentiment Analysis (RoBERTa)

---

## Data Loading & Initial Exploration
The dataset is loaded into a pandas DataFrame for initial exploration, including checking the dimensions and displaying sample records.

## Data Analysis & Visualization
### User Review Frequency Analysis
The distribution of reviews per user is analyzed to identify the most active reviewers and their review patterns.

### Most Active Users (Reviewers)
Users who have written more than 200 reviews are identified for further analysis.

### Multiple Users Review Distribution
Review distributions of the most active users are visualized to understand their rating patterns.

## Text Length Analysis
The length of review texts is analyzed by calculating the mean and standard deviation of text lengths. A histogram is plotted to visualize the distribution.

## NLTK-Based Sentiment Analysis (VADER)
### SentimentIntensityAnalyzer
VADER (Valence Aware Dictionary and sEntiment Reasoner) is used to compute sentiment scores for review texts.

### Apply Sentiment Analysis to Dataset
VADER sentiment scores are computed for each review, and the results are merged with the original dataset for further analysis.

## Visualization of VADER Sentiment Scores
The relationship between star ratings and sentiment scores is visualized using a box plot.

## Transformer-Based Sentiment Analysis (RoBERTa)
### Load Pretrained RoBERTa Model
A transformer-based sentiment analysis model (RoBERTa) is used to classify reviews into negative, neutral, and positive categories.

### Apply RoBERTa to Full Dataset
Sentiment scores from RoBERTa are computed and merged with VADER results to compare traditional and deep learning-based sentiment analysis methods.

## Conclusion
This project utilizes both traditional NLP (VADER) and modern transformer-based (RoBERTa) methods to analyze sentiment in Amazon reviews, providing insights into user review behavior and text-based sentiment trends.
