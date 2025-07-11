# 📧 Email Spam Classifier

An end-to-end machine learning project to classify emails as **Spam or Not Spam** using NLP techniques and classical ML algorithms.

## 🔧 Tech Stack
- Python (Jupyter Notebook)
- scikit-learn
- NLTK (`stopwords`, `punkt`)
- Pandas, NumPy, Pickle

## 🚀 Features
- Text preprocessing: stopword removal, tokenization
- Vectorization using CountVectorizer or TF-IDF
- Model training (e.g., Naive Bayes or Logistic Regression)
- Model persistence using `pickle`
- Interactive prediction interface (can be extended to Flask/Streamlit)

## 🧪 How It Works
1. Load email dataset (CSV or custom).
2. Clean & tokenize text using `nltk`.
3. Train ML model on labeled data.
4. Save model using `model.pkl`.
5. Predict email type using `.predict()` from saved model.

## 💾 Requirements



