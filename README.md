# 🌪️ Disaster Tweet Classification: Real vs False Alarm

## 📌 Overview
This Natural Language Processing (NLP) project is designed to classify online tweets as either referring to a real disaster or a false alarm. The goal of this program is to use machine learning algorithms and text analysis techniques to discern whether a tweet is related to an actual disaster or is simply an incorrect or exaggerated claim, thus helping to improve response times and prevent misinformation in times of crisis.

This model can be used by emergency response teams, social media platforms, or anyone interested in identifying and responding to disaster-related content on social media in real-time.

---

## 🔍 Key Features

- **Real-time Disaster Detection**: Classifies tweets to determine whether they refer to an actual disaster.
- **False Alarm Detection**: Identifies tweets that could cause confusion or panic but do not reference real disasters.
- **Machine Learning & NLP**: Utilizes various ML models and NLP techniques to process and classify tweet data.
- **Multi-Class Classification**: Classifies tweets into categories such as 'real disaster,' 'false alarm,' and others (e.g., irrelevant).

---

## 🧑‍💻 How It Works

This program uses Natural Language Processing (NLP) and machine learning to classify tweets into two categories: **Real Disaster** or **False Alarm**.

1. **Data Preprocessing**:
   - Tokenization of tweet text.
   - Removal of stop words, special characters, and irrelevant information.
   - Lemmatization to reduce words to their base form.

2. **Feature Engineering**:
   - Text vectorization using techniques like TF-IDF and word embeddings.
   - Textual features extraction like sentiment analysis, keyword frequency, etc.

3. **Model Training**:
   - Used Naive bayes algorithm to train the classification model.

4. **Model Evaluation**:
   - Evaluating the performance of the model using metrics such as accuracy, precision, recall, and F1-score.

---
