<div align="center">

# 📰 Fake News Detector

**Classify news articles as real or fake with classical machine-learning models on text features.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

`app.ipynb` works with two CSV files, `Fake.csv` and `True.csv` (the public *Fake and Real News* dataset):

1. Label and merge the two sets, then shuffle.
2. Clean the text (lower-casing, punctuation and special-character removal with `re` / `string`).
3. Vectorize the text and train four classifiers: **Logistic Regression, Decision Tree, Gradient Boosting, Random Forest**.
4. Evaluate with precision / recall / F1 - the best models reach about **99 % accuracy** on the test split.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/fake-news-detector.git
cd fake-news-detector
pip install pandas numpy scikit-learn matplotlib jupyter
jupyter notebook app.ipynb
```

Download `Fake.csv` and `True.csv` (Kaggle: *Fake and real news dataset*) and place them next to the notebook.

## 📁 Project Structure

```
.
└── app.ipynb     # Preprocessing, training and evaluation
```

## 🛠️ Tech Stack

`scikit-learn` · `pandas` · `NumPy` · `Matplotlib`
