# 📰 Persian News Category Recognition

This repository contains projects focused on **Persian news text classification**.  
It includes two main approaches:

1. **Basic Classification** (`NewsCatRed_basic`):
   - Text preprocessing using **tokenization, stopword removal, stemming, and lemmatization** with Hazm and NLTK.  
   - Feature extraction using **TF-IDF**.  
   - Classification using **SVM** and **Gradient Boosting** models.  

2. **Classification with Dimensionality Reduction** (`NewsCatRed_dimensionreduction`):
   - Same text preprocessing as the basic approach.  
   - Feature extraction with **TF-IDF** followed by **dimensionality reduction** techniques such as **Factor Analysis**, **Kernel PCA**, and others.  
   - Classification using **SVM** and evaluation with standard metrics.  

These projects explore the impact of feature reduction on text classification performance and provide a comparison between basic and advanced preprocessing and modeling techniques.

---

## 🛠️ Key Technologies
- Python, Pandas, NumPy  
- Hazm, NLTK  
- scikit-learn (SVM, Gradient Boosting, Factor Analysis, KPCA, etc.)  
- TF-IDF vectorization for text features
