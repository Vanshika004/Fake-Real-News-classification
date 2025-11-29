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
| Roll No. | Name | Assigned Work |
|----------|------|---------------|
| **21801012023** | Vanshika | Dataset collection and cleaning |
| **21501012023** | Vaishnavi | Stemming and Lemmatization |
| **22201012023** | Vidushi Mehra | Preprocessing Report & Visualization |

---

## ⭐ **Case Study 02 — Feature Extraction**
| Roll No. | Name | Assigned Work |
|----------|------|---------------|
| **21401012023** | Urvashi Yadav | BoW and TF-IDF |
| **21101012023** | Twinkle Kotnala | Word2Vec |
| **21201012023** | Udiksha Solanki | GloVe embeddings |

---

## ⭐ **Case Study 03 — Classification Algorithms**
| Roll No. | Name | Assigned Work |
|----------|------|----------------|
| **22901012023** | Zoya Rizvi | ANN Model |
| **21301012023** | Urvashi Singh | Genetic Algorithm |
| **22701012023** | Yogita | Hybrid Model |

---

# 📂 Dataset

We used the **GossipCop Fake News dataset** via direct GitHub import:

```python
real_url = "https://raw.githubusercontent.com/Vanshika004/Fake-Real-News-classification/main/gossipcop_real.csv"
fake_url = "https://raw.githubusercontent.com/Vanshika004/Fake-Real-News-classification/main/gossipcop_fake.csv"
