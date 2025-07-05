# 📰 Fake News Detection using Machine Learning

This project aims to detect fake news articles using Natural Language Processing (NLP) and machine learning techniques. It compares the performance of Logistic Regression and Multinomial Naive Bayes classifiers trained on TF-IDF features.

## 🔍 Objective
To build a supervised ML model that classifies a news article as real or fake based on its content. This is important in combating the spread of misinformation on digital platforms.

## 📊 Dataset
- Source: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- Contains over 40,000 articles labeled as real or fake.
- Used `title` + `text` fields to form the `content`.

## 🛠️ Methods
- Text preprocessing and cleaning
- TF-IDF vectorization
- Train/test split
- Trained and evaluated:
  - Logistic Regression
  - Multinomial Naive Bayes

## 📈 Evaluation
- Metrics: Accuracy, Precision, Recall, F1 Score
- Logistic Regression achieved ~98% accuracy
- Naive Bayes achieved ~93% accuracy
- Confusion matrices and heatmaps for visual evaluation

## 📁 Project Files
- `fake_news_detection.ipynb` – main notebook with complete code
- `Fake.csv` / `True.csv` – datasets used
- `logistic_confusion_matrix.png` / `naive_bayes_confusion_matrix.png` – evaluation visuals
- `report.tex`, `output.pdf` – project documentation

## 🚀 Future Scope
- Add deep learning models (e.g., LSTM, BERT)
- Improve preprocessing using lemmatization, named entity recognition
- Deploy as a web-based news validation tool

---
