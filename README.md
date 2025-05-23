# U.S. Airline Twitter Sentiment Analysis

## Overview
This project performs sentiment analysis on tweets related to U.S. airlines using natural language processing (NLP) techniques and K-Nearest Neighbors (KNN) classification. The goal is to uncover patterns in public opinion and extract actionable insights for the airline industry.

## Methods & Tools
- **Tokenization & Stemming** for text preprocessing
- **Vectorization** of tweets for model input
- **KNN Classifier** with hyperparameter tuning
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score
- **Similarity Metrics**: Cosine Similarity, Manhattan Distance, Euclidean Distance
- **Cross-Validation**: 10, 100, 1000 folds tested

## Key Findings
- Higher values of K improved model stability and reduced overfitting
- Cosine similarity yielded more consistent results than Manhattan and Euclidean
- Cross-validation revealed diminishing returns after 100 folds
- Optimal K identified: 200 with 10-fold CV showed best generalization

## Business Applications
- Track brand perception in real-time
- Improve customer support responsiveness
- Inform marketing and service personalization
- Monitor competitor sentiment landscape
- Enable predictive modeling of market shifts

