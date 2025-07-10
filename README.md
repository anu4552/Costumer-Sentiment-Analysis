# 🧠 Customer Sentiment Analysis | NLP + Machine Learning

This project performs **sentiment analysis** on customer reviews using **Natural Language Processing (NLP)** and **Machine Learning (Naive Bayes)** in Python. It classifies reviews as **positive** or **negative**, and includes text preprocessing, TF-IDF vectorization, model training, and evaluation.

---

## ✅ Features

- Clean and preprocess raw text (HTML, stopwords, stemming)
- Convert reviews into numerical features using **TF-IDF**
- Train a **Multinomial Naive Bayes** classifier
- Achieve **85%+ accuracy** on real-world data
- Export trained model and vectorizer using `joblib`
- Use the model via CLI or integrate into a web app

---

## 📁 Folder Structure

sentiment-analysis/
├── sentiment_predictor.ipynb # CLI script to predict sentiment
├── sentiment_model_nb.joblib # Saved ML model
├── tfidf_vectorizer.joblib # Saved TF-IDF vectorizer
├── IMDB_Dataset.csv # Input dataset (or any CSV with review + label)
├── README.md # Project documentation

---

## 🧰 Technologies & Libraries

- Python 3.8+
- pandas
- scikit-learn
- nltk
- joblib
- matplotlib / seaborn (optional for visualization)

