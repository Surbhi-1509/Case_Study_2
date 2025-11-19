# Case_Study_2
A Gen AI & LLM course case study on sentiment analysis using Word2Vec and GloVe embeddings for deeper contextual understanding.

## Project Overview
This project focuses on using word embeddings to analyze customer reviews and classify sentiment (positive, negative, or neutral).
Unlike traditional TF–IDF models, embeddings like Word2Vec and GloVe capture semantic and contextual meanings, improving prediction accuracy.

The workflow includes text preprocessing, embedding generation, model training, evaluation, and comparison of embedding-based models.

## Problem Statement
Customer reviews contain meaningful insights about satisfaction and product quality.
Conventional models fail to capture the true context behind words.
This project utilizes Word2Vec and GloVe embeddings to build sentiment classifiers that better interpret natural language and enhance prediction results.

## Objectives
- Preprocess and clean textual review data.
- Generate vector representations using Word2Vec and GloVe.
- Train models (e.g., Random Forest) on the generated embeddings.
- Compare embedding-based models with classical TF–IDF approaches.
- Identify the most effective embedding technique for sentiment prediction.

## Methodology
1. Dataset Preparation: Import and clean product review dataset.
2. Preprocessing: Tokenize text, remove stopwords, and apply lemmatization.
3. Embedding Generation:

- Word2Vec: Trained locally for domain relevance.
- GloVe: Pre-trained embeddings used for contextual richness.
    -Modeling: Train Random Forest and other ML models on embeddings.
    -Evaluation: Accuracy, F1-score, and confusion matrix used for comparison.
    -Analysis: Assess embedding performance in capturing sentiment context.

## Results
Word embeddings outperformed traditional Bag-of-Words and TF–IDF models.
Random Forest achieved strong performance using embeddings.
Word2Vec excelled in context-specific patterns, while GloVe captured global semantics.
Embedding-based models generalized effectively on unseen data.

## Tools & Libraries
- Python
- Scikit-learn
- Gensim
- NLTK / SpaCy
- NumPy, Pandas, Matplotlib

## Academic Context
This project was completed as part of the Gen AI & LLM subject coursework, focusing on embedding-based NLP and comparative sentiment analysis techniques.
