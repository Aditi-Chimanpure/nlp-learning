# NLP Practice

This repository contains my practice notebooks and notes while learning Natural Language Processing (NLP).

## 📚 Course

* https://learn.365datascience.com/courses/nlp
* https://www.udemy.com/course/intro-to-natural-language-processing-in-python-for-ai/

## 📂 Contents

* Tokenization
* Stopwords removal
* Stemming & Lemmatization
* POS Tagging
* Named Entity Recognition (NER)
* Sentiment Analysis
* Text Classification
* Word Embeddings

## ⚙️ Setup

```bash
conda create --name nlp_course_env python=3.11
conda activate nlp_course_env
pip install nltk pandas matplotlib spacy textblob vaderSentiment transformers scikit-learn gensim seaborn torch ipywidgets
python -m spacy download en_core_web_sm
```

## ▶️ Run

```bash
jupyter notebook
```

Select kernel: `nlp_course_env`

## 📌 Notes

* Includes personal practice and small experiments
* Some differences from course due to package updates
