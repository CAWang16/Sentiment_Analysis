# Amazon Review Sentiment Analysis

This repository contains a Python script for analyzing the sentiment of Amazon product reviews using both traditional and deep learning-based sentiment analysis models. The dataset, `Reviews.csv`, includes user comments and star ratings from Amazon.

---

## **Features**
- **Data Visualization**: Explore the distribution of review ratings and their associated sentiment scores.
- **Sentiment Analysis with VADER**: Perform lexicon-based sentiment analysis to extract polarity scores.
- **Sentiment Analysis with RoBERTa**: Leverage a pre-trained RoBERTa model for state-of-the-art sentiment classification.
- **Combined Analysis**: Compare and visualize sentiment results from both models.

---

## **Requirements**

Install the required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn nltk tqdm transformers
