# MindScope AI

Unsupervised Discovery of Mental Health Patterns using NLP & Clustering

---

## Overview

MindScope AI is an end-to-end machine learning project that analyzes social media text to uncover hidden psychological patterns without using labeled data.
It combines NLP techniques, embedding models, and clustering algorithms to group similar expressions into meaningful mental health categories.

---

## Objectives

* Discover latent mental health patterns from raw text
* Apply unsupervised learning (no labels)
* Simulate real-time prediction using streaming data
* Build an interactive visualization system

---

## Pipeline

```
Text Data
   ↓
Preprocessing
   ↓
Sentence-BERT Embeddings
   ↓
UMAP (Dimensionality Reduction)
   ↓
Clustering (HDBSCAN / KMeans)
   ↓
Analysis & Visualization
```

---

## Features

* NLP preprocessing pipeline
* Semantic embeddings using Sentence-BERT
* Multiple clustering approaches (KMeans, DBSCAN, HDBSCAN)
* Automatic cluster interpretation (keywords + labels)
* Real-time simulation (streaming unseen data)
* Interactive dashboard (Streamlit)

---

## Example Output

| Cluster | Label      | Description              |
| ------- | ---------- | ------------------------ |
| 0       | Depression | sadness, hopelessness    |
| 1       | Anxiety    | worry, overthinking      |
| 2       | Stress     | pressure, burnout        |
| 3       | Loneliness | isolation, no connection |

---

## Real-Time Simulation

The system simulates a real-time environment by streaming unseen samples from the dataset and predicting their cluster dynamically, mimicking live user input.

---

## Demo (Streamlit)

* Input text
* Get predicted cluster instantly
* Visualize clusters in 2D (UMAP)
* Explore insights and keywords

---

## Project Structure

```
MindScope-AI/
│
├── data/
├── preprocessing/
├── embeddings/
├── clustering/
├── simulation/
├── app/
│   └── streamlit_app.py
├── models/
├── notebooks/
└── README.md
```

---

## Tech Stack

* Python
* PyTorch
* Sentence-Transformers
* Scikit-learn
* UMAP
* HDBSCAN
* Streamlit

---

## Evaluation

* Silhouette Score
* Davies-Bouldin Index
* Cluster Distribution Analysis
* Human Interpretation (Labels & Meaning)

---

## Team Roles

* Data & Simulation
* NLP Preprocessing
* Embeddings
* Clustering & Modeling
* Deployment & Visualization

---

## Future Improvements

* Real API deployment (FastAPI)
* Live user input system
* Advanced topic modeling
* Multilingual support

---

## Summary

MindScope AI transforms unstructured text into meaningful psychological insights using unsupervised learning, demonstrating how AI can reveal hidden patterns in human expression.

---
