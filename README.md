# 🐦 Sentiment Analysis on Tweets

> Automatically classifying tweets as **positive** or **negative** using NLP and Machine Learning — built from scratch as my first AI/ML project.

---

## 🧠 What is this project?

Every second, thousands of tweets are posted expressing opinions, emotions, and reactions. This project builds a machine learning pipeline that reads a tweet and predicts whether the sentiment behind it is positive or negative — just like a human would, but automated.

---

## ⚙️ How it works
| Step | What happens |
|------|-------------|
| 🧹 Text Cleaning | Remove URLs, @mentions, punctuation, stopwords, stem words |
| 🔢 TF-IDF Vectorization | Convert words into numbers the model can understand |
| 🤖 Logistic Regression | Train a model to classify sentiment |
| 📊 Evaluation | Measure accuracy with F1 score and confusion matrix |

---

## 🛠️ Tools & Why I used them

| Tool | Purpose |
|------|---------|
| `pandas` | Load and manage tweet data |
| `NLTK` | Text cleaning — stopwords removal and stemming |
| `scikit-learn` | TF-IDF vectorization, Logistic Regression, F1 score |
| `matplotlib` + `seaborn` | Visualize the confusion matrix |
| `Jupyter Notebook` | Interactive development environment |

---

## 📈 Results

| Metric | Score |
|--------|-------|
| Macro F1 Score | **0.756** |
| Model | Logistic Regression |
| Features | TF-IDF (5000 features) |

---

## 🚀 How to run this yourself

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Open the notebook
jupyter notebook sentiment_analysis.ipynb

```
## 📁 Project structure

sentiment-analysis/
├── sentiment_analysis.ipynb   # main notebook
├── tweets.csv                 # dataset
├── requirements.txt           # dependencies
└── README.md                  # readme
---
## Dataset

The original dataset is not included in this repository because it exceeds GitHub's file size limits. A smaller sample dataset can be provided, or the dataset can be downloaded separately.
---
## 👨‍💻 Built by Apoorva.R
