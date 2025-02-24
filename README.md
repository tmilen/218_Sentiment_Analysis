# 218_Sentiment_Analysis
🚀 A comparative study of **three sentiment analysis models** on tweets.

---

## 📝 Project Overview  
This project aims to **classify sentiment** (Positive, Neutral, Negative) using **three different approaches**:

1️⃣ **Fine-tuned DistilBERT (distilbert-based-uncased)**  
2️⃣ **Fine-tuned XLM-RoBERTa for Bilingual Sentiment Analysis**  
3️⃣ **VADER + TF-IDF + Random Forest (Hybrid Approach)**  

**Objective:**  
Compare the **performance, accuracy, and efficiency** of deep learning vs. traditional NLP models for sentiment analysis.

---

## 📂 Datasets  
We use two main datasets:

1️⃣ **English Sentiment Dataset** (Twitter-based)  
📌 [Kaggle Link](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)  

2️⃣ **Burmese Sentiment Dataset**  
📌 [Hugging Face Link](https://huggingface.co/datasets/kornwtp/burmese-gklmip-sentiment)  

---

## 📊 Results & Comparison  

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|---------|
| Fine-tuned XLM-RoBERTa | 86.79% | 0.87 | 0.87 | 0.87 |
| Fine-tuned DistilBERT | 88.15% | 0.88 | 0.88 | 0.88 |
| VADER + TF-IDF + Random Forest | 97% | 0.97 | 0.97 | 0.97 |

🟢 **VADER + TF-IDF struggled with Burmese text** showing strong sentiment classification.  
 
---
## Feel free to request for collaborations ❤️
