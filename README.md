# 📰 News Summarization using BART and T5

## 📌 Project Overview

This project implements **Abstractive Text Summarization** using two transformer-based models:

- BART (facebook/bart-large-cnn)
- T5 (t5-base)

The system generates concise summaries from news articles and evaluates model performance using the **ROUGE metric**.

---

## 🎯 Objectives

- Implement transformer-based abstractive summarization
- Compare BART and T5 performance
- Evaluate summaries using ROUGE scores
- Understand the importance of proper reference summaries in NLP evaluation

---

## 🧠 Models Used

### 🔹 BART
Model: `facebook/bart-large-cnn`  
Pre-trained for news summarization tasks.

### 🔹 T5
Model: `t5-base`  
Text-to-text transformer capable of summarization using prefix-based prompting.

---

## 📊 Evaluation Metric

We used **ROUGE (Recall-Oriented Understudy for Gisting Evaluation)**:

- ROUGE-1 → Unigram overlap
- ROUGE-2 → Bigram overlap
- ROUGE-L → Longest Common Subsequence

ROUGE compares:
