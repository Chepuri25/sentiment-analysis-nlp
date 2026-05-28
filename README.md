# 🎬 Sentiment Analysis — NLP

A Natural Language Processing pipeline for movie review sentiment
classification using TF-IDF and traditional ML models.

![Python](https://img.shields.io/badge/Python-3.13-blue)
![NLTK](https://img.shields.io/badge/NLTK-3.8-green)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-1.3-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🎯 Project Overview

Built an end-to-end NLP sentiment analysis pipeline on the NLTK
Movie Reviews dataset (2,000 reviews). Compared 3 ML models and
achieved **85%+ accuracy** using TF-IDF features with bigrams.

**Key Results:**
- ✅ Accuracy  : 85%+
- ✅ ROC-AUC   : 0.90+
- ✅ Dataset   : 2,000 movie reviews (balanced)
- ✅ Best Model: Linear SVM

---

## 📊 Results

| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | ~85%     |
| Naive Bayes          | ~82%     |
| Linear SVM           | ~87%     |

---

## 🛠️ Tech Stack

- **Python 3.13**
- **NLTK** — Text preprocessing & datasets
- **Scikit-learn** — TF-IDF, ML models, evaluation
- **WordCloud** — Text visualization
- **Pandas / NumPy** — Data manipulation
- **Matplotlib / Seaborn** — Visualizations
- **Jupyter Notebook** — Development environment

---

## 📁 Project Structure
sentiment-analysis-nlp/
├── data/
│   └── cleaned_reviews.csv
├── notebooks/
│   ├── 01_eda_preprocessing.ipynb
│   ├── 02_traditional_ml.ipynb
│   └── 03_evaluation.ipynb
├── models/
│   ├── best_model.pkl
│   └── tfidf_vectorizer.pkl
├── results/
│   ├── sentiment_distribution.png
│   ├── review_length.png
│   ├── wordclouds.png
│   ├── model_comparison.png
│   ├── confusion_matrix.png
│   └── roc_curve.png
├── requirements.txt
└── README.md
---

## 🚀 Quick Start

### 1. Clone the repo
```bash
git clone https://github.com/Chepuri25/sentiment-analysis-nlp
cd sentiment-analysis-nlp
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Download NLTK data
```python
import nltk
nltk.download('movie_reviews')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('punkt_tab')
nltk.download('omw-1.4')
```

### 4. Run notebooks in order
```bash
jupyter notebook
```
Navigate to `notebooks/` and run 01 → 02 → 03

---

## 💡 Key Insights

- **Linear SVM** performs best with TF-IDF features
- **Bigrams** (2-word combinations) improve accuracy significantly
- **Balanced dataset** (50/50) ensures unbiased model training
- **Lemmatization** reduces vocabulary size and improves generalization

---

## 🎬 Live Prediction Examples

| Review | Prediction |
|--------|------------|
| "Amazing movie, great acting!" | 😊 POSITIVE |
| "Terrible film, waste of time." | 😞 NEGATIVE |
| "One of the best I have seen!"  | 😊 POSITIVE |
| "Boring and predictable plot."  | 😞 NEGATIVE |

---

## 📞 Contact

**Pravallika Chepuri**
- 📧 Email: pchepur1@asu.edu
- 💼 LinkedIn: https://www.linkedin.com/in/pravallika-chepuri
- 🐙 GitHub: https://github.com/Chepuri25

---
**Built with ❤️ by Pravallika Chepuri | Arizona State University**
