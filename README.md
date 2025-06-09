# 🧠 Fake News Detection with Explainability

![Fake News Banner](https://allea.org/wp-content/uploads/2020/06/shutterstock_1387192166-1500x630.jpg)

#  **Project Overview**


In this project we will be useing machine learning and NLP to distinguish between fake and real news articles. It integrates explainable AI (LIME and SHAP) to reveal how predictions are made.

**Goals**:
- Build a fake news classifier using NLP (TF-IDF + Logistic Regression).
- Improve model transparency and trust using explainability tools (LIME and SHAP).
- Deploy using Streamlit for interactive exploration.

**Dataset Overview**:
- Source: [Kaggle - Fake News Detection Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- Files: 
  - `Fake.csv` (23,502 fake news articles)
  - `True.csv` (21,417 real news articles)
- Columns:
  - `title`: Headline of the news article
  - `text`: Main content of the article
  - `subject`: Topic category of the article
  - `date`: Publication date

**Purpose**:
- To analyze linguistic and structural differences between fake and real news.
-  To train an interpretable model to help audiences understand how and why an article is labeled as real or fake.
- To support efforts against misinformation by providing an explainable AI-based tool.

## 🚀 Highlights
- TF-IDF + Logistic Regression
- Explainable AI (LIME)
- SHAP Value Visualization
- (Bonus) Streamlit Deployment

Environment


Team Members

## 🔧 Installation
```bash
pip install -r requirements.txt

