# 📰 Fake vs Real News Classification  
### *A Complete NLP Pipeline using Stemming, Lemmatization, BoW, TF-IDF, Word2Vec, GloVe, ANN, Genetic Algorithm & Hybrid Models*

---

## 📌 Project Overview  
This project aims to classify **Real vs Fake news headlines** from the **GossipCop dataset** using multiple Natural Language Processing (NLP) techniques.  
The workflow covers:

- Text preprocessing  
- Stemming & Lemmatization  
- Feature extraction (BoW, TF-IDF, Word2Vec, GloVe)  
- Undersampling for dataset balancing  
- ANN model  
- Genetic Algorithm-based feature selection  
- Hybrid ANN combining TF-IDF + Word2Vec  

The project is divided into 3 case studies with contributions from **Group 5**.

---

# 👥 **Team Members & Work Division (According to Official Assignment)**

## ⭐ **Case Study 01 — Preprocessing**
1. Dataset collection and cleaning
2. Stemming and Lemmatization
3. Preprocessing Report & Visualization

---

## ⭐ **Case Study 02 — Feature Extraction**
1. BoW and TF-IDF
2. Word2Vec
3. GloVe embeddings

---

## ⭐ **Case Study 03 — Classification Algorithms**
1. ANN Model
2. Genetic Algorithm
3. Hybrid Model

---

# 📂 Dataset

We used the **GossipCop Fake News dataset** via direct GitHub import:

```python
real_url = "https://raw.githubusercontent.com/Vanshika004/Fake-Real-News-classification/main/gossipcop_real.csv"
fake_url = "https://raw.githubusercontent.com/Vanshika004/Fake-Real-News-classification/main/gossipcop_fake.csv"
