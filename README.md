NLP Word2Vec & AvgWord2Vec Project

Overview

This project demonstrates the use of **Word2Vec embeddings** and an **Average Word2Vec (AvgWord2Vec)** approach for basic Natural Language Processing (NLP) tasks using Python. 

The goal is to convert SMS text messages into **vector representations** that capture semantic relationships between words, enabling downstream tasks such as **spam detection** or **text classification**. 

Key highlights:
- Preprocessing text data for NLP tasks.
- Training and using Word2Vec embeddings with Gensim.
- Creating sentence embeddings by averaging word vectors (AvgWord2Vec).
- Designed for experimentation and easy extension to ML models.

---

Dataset

- **Source:** [SMSSpamCollection Dataset (UCI ML Repository)](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
- **Description:** 5,574 SMS messages labeled as `ham` (legitimate) or `spam`.
- **Format:** TSV (`label`, `message` columns)

