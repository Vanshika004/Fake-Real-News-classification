# 📰 Fake vs Real News Classification  
### *A Complete NLP Pipeline using Stemming, Lemmatization, BoW, TF-IDF, Word2Vec, GloVe, ANN, Genetic Algorithm & Hybrid Models*

---

## 📌 Project Overview  
This project aims to classify **Real vs Fake news headlines** from the **GossipCop dataset** using multiple Natural Language Processing (NLP) techniques.  
The workflow covers:

- Text preprocessing  
- Stemming & Lemmatization  
- Feature extraction (BoW, TF-IDF, Word2Vec, GloVe)  
- Undersampling for balancing dataset  
- Machine Learning & Deep Learning models  
- Genetic Algorithm for feature selection  
- Hybrid (TF-IDF + Word2Vec) ANN model  

The project is divided among **9 team members**, each contributing a distinct module.

---

## 👥 Team Members & Work Division

| Member | Roll No. | Assigned Work |
|-------|----------|----------------|
| **1. Vanshika** | — | Dataset loading, cleaning, preprocessing, combining Real & Fake |
| **2. Vidushi** | 22201012023 | Stemming & Lemmatization on cleaned dataset |
| **3. (Your name)** | — | Vocabulary analysis & comparison before/after stemming & lemmatization |
| **4. Twinkle** | 21101012023 | Word2Vec feature extraction |
| **5. Urvashi** | 21401012023 | BoW + TF-IDF (Uni-grams, Bi-grams) with visualizations |
| **6. Udiksha** | 21201012023 | GloVe Embeddings + Comparison with Word2Vec |
| **7. Zoya** | 22901012023 | ANN model with TF-IDF input |
| **8. Yogita** | 22701012023 | Genetic Algorithm for Feature Selection |
| **9. __________** | — | Hybrid Model (TF-IDF Selected Features + Word2Vec) |

---

## 📂 Dataset

We used the **GossipCop Fake News** dataset:

- **gossipcop_real.csv**
- **gossipcop_fake.csv**

Downloaded directly via GitHub:

```python
real_url = "https://raw.githubusercontent.com/Vanshika004/Fake-Real-News-classification/main/gossipcop_real.csv"
fake_url = "https://raw.githubusercontent.com/Vanshika004/Fake-Real-News-classification/main/gossipcop_fake.csv"
