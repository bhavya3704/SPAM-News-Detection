# SPAM-News-Detection
SPAM News Classifier
# Spam Message Classifier (Naive Bayes)

A Python-based machine learning project that classifies SMS messages as *spam* or *ham* using a *Multinomial Naive Bayes* algorithm and *Bag-of-Words* text vectorization.

## 🔍 Overview
This project demonstrates a simple but powerful approach to binary text classification using:
- CountVectorizer for feature extraction
- MultinomialNB for classification
- Evaluation with accuracy score & classification report

## 📁 Dataset
The dataset spamdetection.csv contains two columns:
- label: spam or ham
- message: the text content of the SMS

## 🚀 Features
- Train/test split with stratified sampling
- Performance metrics (accuracy, precision, recall, F1)
- Real-time predictions on custom messages

## 🧪 Example Output
```python
Message: "Congratulations! You've won a free ticket!" - Prediction: spam
Message: "Can we reschedule our meeting?" - Prediction: ham
