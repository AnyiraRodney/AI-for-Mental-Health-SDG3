# AI for Mental Health (SDG 3)

## 🌍 Overview
A proof-of-concept machine learning model that detects distress-related tweets using the public **Sentiment140** dataset.  
This supports **SDG Target 3.4 — Promote mental health and wellbeing** through early distress pattern recognition.

## 🧠 Approach
- **Dataset:** Sentiment140 (1.6M tweets; sampled 60k)
- **Model:** Logistic Regression & Naive Bayes (TF-IDF features)
- **Proxy label:** Negative sentiment → Distress
- **Framework:** Google Colab + scikit-learn + NLTK

## 📊 Results
| Metric | Logistic Regression | Naive Bayes |
|--------|--------------------|-------------|
| Accuracy | *paste from notebook* | *paste from notebook* |
| F1-Score | *paste from notebook* | *paste from notebook* |

## 🖼️ Visuals
![Confusion Matrix](confusion_matrix.png)  
![WordClouds](wordclouds.png)

## ⚖️ Ethics
- **Proxy limitation:** Negative sentiment ≠ clinical distress.  
- **Bias risk:** Twitter data ≠ population data (age, region, language bias).  
- **Responsible use:** For awareness and research — not diagnosis.  
- **Privacy:** Use anonymized, public text only.

## 🧩 SDG Impact
Demonstrates how AI can support **SDG 3 (Good Health & Wellbeing)** by identifying distress signals in online conversations — paving the way for early awareness tools or human-in-the-loop support systems.

## 👤 Author
[Your Name]  
AI for Good – SDG3 Project (2025)
