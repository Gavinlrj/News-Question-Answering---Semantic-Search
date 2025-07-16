A deep learning-powered system for question answering and semantic retrieval on large-scale news articles.

## Project Objective

The goal of this project is to build a robust NLP pipeline that preprocesses and cleans news articles, performs coreference resolution, and enables users to ask questions and get accurate, context-aware answers from the news corpus. It also identifies the most relevant sentence to a user query.

## Features

- **Data Cleaning & Preprocessing**: Lowercasing, punctuation removal, stemming, stop word filtering.
- **Coreference Resolution**: Replace ambiguous pronouns with the correct entities using SpaCy.
- **Semantic Search**: Finds the most relevant sentence to the user's question using BERT embeddings and cosine similarity.
- **Question Answering**: Uses a pre-trained BERT model to extract accurate answers from news articles.
- **Evaluation**: Includes precision, recall, and F1-score for QA system performance.
