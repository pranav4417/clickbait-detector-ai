# Clickbait & Fake News Headline Detector

A lightweight, beginner-friendly Natural Language Processing (NLP) application that identifies whether a news headline uses psychological clickbait tactics or follows standard journalistic formatting.

## 🚀 How It Works
Instead of basic sentiment analysis, this model focuses on structural text patterns and token frequencies.
1. **Preprocessing:** Text is tokenized, lowercased, and stripped of generic stop words.
2. **Feature Extraction:** Converts headlines into numerical vectors using **TF-IDF (Term Frequency-Inverse Document Frequency)**.
3. **Classification:** Uses a **Multinomial Naive Bayes** classifier to calculate the mathematical probability of a headline being clickbait.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Machine Learning:** Scikit-learn
- **NLP Utilities:** NLTK
- **Data Manipulation:** Pandas
