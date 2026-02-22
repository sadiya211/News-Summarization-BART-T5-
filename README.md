# 📰 News Summarization using BART and T5

## 📌 Overview
This project implements **abstractive text summarization** using two transformer models:
- BART (facebook/bart-large-cnn)
- T5 (t5-base)

The models generate short summaries from news articles and are evaluated using the ROUGE metric.

---

## 🎯 Objective
- Generate summaries from news articles
- Compare BART and T5 performance
- Evaluate summaries using ROUGE scores

---

## 🛠 Technologies Used
- Python
- HuggingFace Transformers
- PyTorch
- Newspaper3k (for scraping)
- Evaluate (ROUGE metric)

---

## 📂 Workflow
1. Scrape news article text  
2. Generate summary using BART  
3. Generate summary using T5  
4. Evaluate summaries using ROUGE  
5. Compare performance  

---

## 📊 Evaluation Metric
ROUGE is used to measure similarity between:
Generated Summary  vs  Reference Summary

Metrics used:
- ROUGE-1
- ROUGE-2
- ROUGE-L

---

## 🚀 How to Run

### Step 1: Install dependencies 

### Step 2: Run the notebook
Open the Jupyter Notebook or Google Colab file and execute all cells.

---

## ⚠ Important Note
ROUGE scores depend on a proper reference summary. If the reference text is empty or incorrect, the score may become zero.

---

## 📈 Result
Both BART and T5 successfully generated abstractive summaries. Performance comparison was done using ROUGE scores.

---

