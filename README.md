# 📰 News_type_predict

A machine learning project that classifies English news articles into three categories: **Sports**, **Politics**, and **Economy/Business**, using classic NLP techniques and scikit-learn.

---

## 📌 Overview

This project builds a text classification pipeline that takes a raw news article as input and predicts its category. It covers the full workflow: data preprocessing, feature extraction (TF-IDF), model training, evaluation, and inference on new/unseen text.

**Categories:**
- ⚽ Sports 
- 🏛️ Politics
- 💰 Economy / Business

---

## 🚀 Features

- Text preprocessing (cleaning, tokenization, stopword removal, lemmatization/stemming)
- TF-IDF vectorization
- Classification using **K-Nearest Neighbors (KNN)**
- Model evaluation with accuracy, Confusion matrix 
- Easy-to-use prediction function/script for new articles

---

## 📁 Project Structure

```
News_type_predict/
│
├── data/
│   ├── news.csav
│
├── notebooks/
│   └── News_Predict.ipynb

├── Result_Image/
│   ├── Confusion matrix.png
│   ├── Train vs Test Accuracy Scores.png

│
├── requirements.txt
├── README.md
└── LICENSE
```

> ℹ️ Update this structure to match your actual repo layout.

---

## 🗂️ Dataset

- **Language:** English
- **Classes:** 3 (Sports, Politics, Economy)

Example data format:

| text | label |
|------|-------|
| "The team won the championship last night..." | sports, 0 |
| "The president announced new policies today..." | politics, 1 |
| "Stock markets rose sharply after the report..." | economy, 2 |

---

## 🧠 Model

The pipeline uses **TF-IDF** for feature extraction combined with a **K-Nearest Neighbors (KNN)** classifier from **scikit-learn**.

---

## 📊 Results

| Metric | Score |
|--------|-------|
| Accuracy_Train  | 0.83 |
| Accuracy_Test | 0.83 |
> Fill in your actual evaluation numbers above.

---

## ⚙️ Installation

```bash
git clone https://github.com/mahanly89mly-boop/News_Type_Predict
cd News_Type_Predict
pip install -r requirements.txt
```

## Requirements
```
scikit-learn
pandas
numpy
matplotlib
seaborn
```

## 🚀 How to Run

```bash
pip install -r requirements.txt
pip install numpy , pandas , scikit-learn , matplotib , seaborn
jupyter notebook notebook.ipynb

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
