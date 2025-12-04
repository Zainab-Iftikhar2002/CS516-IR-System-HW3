# Information Retrieval System using TF-IDF

Zainab Iftikhar
Course: CS 516 - Information Retrieval and Text Mining
Fall 2025

Overview
This is a local Information Retrieval system that uses TF-IDF and cosine similarity to search and rank documents.

Dataset
- Total Documents: 2,692 articles
- Source: Articles.csv
- Columns: Article, Date, Heading, NewsType

Requirements
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, nltk

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
- Average Query Time: 12.25 ms
- Memory Usage: 2.16 MB
- Vocabulary Size: 5,000 terms
- Matrix Sparsity: 97.90%

System Features
- Text preprocessing (lowercase, tokenization, stopword removal, stemming)
- TF-IDF vectorization
- Cosine similarity ranking
- Fast and memory efficient

Files Included
- Jupyter Notebook (.ipynb)
- README.md
- Articles.csv (dataset)

Zainab Iftikhar
