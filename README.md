# 🧠 HR Sentiment Intelligence System — Employee Retention Risk via LLMs

This project leverages **Transformer-based NLP models** to detect emotional tone and predict employee retention risk from open-ended feedback, in the context of real Algerian business environments.

## 🚀 Objective

Traditional HR systems rely on rigid surveys and outdated indicators. This project brings **modern AI to HR** by:

- 🔍 **Analyzing employee feedback** using Large Language Models (LLMs)
- 🎯 **Detecting emotional signals** like stress, disengagement, hope, motivation
- 🧠 **Clustering employees** based on tone and language
- 🛑 **Flagging high-risk employees** before they quit

---

## 🧩 Dataset

Simulated feedback from **40 employees** in various departments (IT, Sales, HR, etc.), with:

- Age, department, job role, salary, years at company
- Open-ended text feedback (the kind HR teams might collect)
- ⚠️ No labels for satisfaction or attrition — instead, we infer them using AI

---

## 📦 Technologies Used

| Purpose | Tools/Models |
|--------|--------------|
| Emotion detection | 🤗 `transformers` — DistilRoBERTa (`j-hartmann/emotion-english-distilroberta-base`) |
| Semantic embeddings | 🧠 `sentence-transformers` — `all-MiniLM-L6-v2` |
| Clustering | `KMeans`, `UMAP` |
| EDA & Visualization | `pandas`, `matplotlib`, `seaborn` |
| Optional dashboard | `streamlit` or `Power BI` |

---

## 🔬 Project Structure

