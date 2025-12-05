# Information Retrieval System using TF-IDF

Zainab Iftikhar
Course: CS 516 - Information Retrieval and Text Mining
Fall 2025

Overview
This is a local Information Retrieval system that uses TF-IDF and cosine similarity to search and rank documents.

Dataset
1. Total Documents: 2,692 articles
2. Source: Articles.csv
3. Columns: Article, Date, Heading, NewsType

Requirements
1. Python 3.8+
2. Libraries: pandas, numpy, scikit-learn, nltk

Installation
pip install pandas numpy scikit-learn nltk

How to Run in Google Colab
1. Open the notebook file in Google Colab
2. Upload Articles.csv to Colab
3. Run all cells from top to bottom
4. System will preprocess documents and build TF-IDF index
5. Use search_documents(query, top_k=5) to search

Example Usage
query = "oil prices economy"
results = search_documents(query, top_k=5)

Performance Metrics
1. Average Query Time: 12.25 ms
2. Memory Usage: 2.16 MB
3. Vocabulary Size: 5,000 terms
4. Matrix Sparsity: 97.90%

System Features
1. Text preprocessing (lowercase, tokenization, stopword removal, stemming)
2. TF-IDF vectorization
3. Cosine similarity ranking
4. Fast and memory efficient

Files Included
- Jupyter Notebook (.ipynb)
- README.md
- Articles.csv (dataset)

Zainab Iftikhar
