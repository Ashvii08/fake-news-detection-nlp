# 📰 Fake News Detection & Live Fact Verification using NLP & ML

An end-to-end Natural Language Processing (NLP) pipeline and interactive web application designed to classify fake news articles and perform real-time credibility verification using machine learning and live news data[cite: 2].

---

## 🎯 Overview & Objectives

Misinformation spreads rapidly across online media platforms[cite: 2]. This project implements a high-precision text classification system paired with live news checking to evaluate article credibility[cite: 2].

- **NLP Model:** Trained on **6,000–7,000 news articles** to classify content as real or fake[cite: 2].
- **Web Interface:** Deployed as a **Flask web app** allowing users to test raw text input or fetch live articles via **NewsAPI** for instant credibility checks[cite: 2].
- **Accuracy:** Reached **~95% classification accuracy** through optimized text preprocessing and vectorization[cite: 2].

---

## ⚙️ Project Architecture & Pipeline

1. **4-Stage Text Preprocessing:** Cleaning text data using tokenization, stop-word removal, lemmatization/stemming, and special character stripping[cite: 2].
2. **Feature Extraction:** TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to capture word importance and contextual features[cite: 2].
3. **Model Training:** Passive Aggressive Classifier optimized for large-scale text streams and fast inference times[cite: 2].
4. **Live API Integration:** Real-time news ingestion and verification via **NewsAPI** integration[cite: 2].

---

## 🛠️ Tools & Technologies Used

- **Language:** Python[cite: 2, 3]
- **Libraries:** Scikit-learn, Pandas, NumPy, NLTK[cite: 2]
- **NLP Techniques:** TF-IDF Vectorization, Text Cleaning, Feature Engineering[cite: 2]
- **ML Algorithm:** Passive Aggressive Classifier[cite: 2]
- **Web Framework:** Flask, HTML5, CSS3[cite: 2, 3]
- **External Services:** NewsAPI[cite: 2]

---

## 📁 Repository Structure

```text
├── dataset/                    # Raw/processed dataset files
├── Images/                     # Screenshots and visual assets
├── static/                     # Web app static assets (CSS, JS)
├── templates/                  # HTML templates for Flask frontend
├── app.py                      # Flask application entry point
├── Fake_News_Detector-PA.ipynb # Model development & training notebook
├── model.pkl                   # Serialized ML model
├── vector.pkl                  # Serialized TF-IDF vectorizer
├── requirements.txt            # Project library requirements
└── README.md                   # Documentation
