Twitter Sentiment Analysis 🚀

An end-to-end NLP + Machine Learning project that classifies tweets as positive or negative using classical text processing and TF-IDF features.

Built on the Sentiment140 (1.6M tweets) dataset to demonstrate scalable text classification.

🔍 Problem Statement

Social media platforms generate massive volumes of unstructured text.
The goal of this project is to automatically detect sentiment in tweets using efficient and interpretable machine-learning techniques.

📊 Dataset

Name: Sentiment140

Source: Kaggle

Size: 1.6M tweets

Labels:

0 → Negative

1 → Positive

Dataset is downloaded programmatically using the Kaggle API.

🧠 Approach
1️⃣ Text Preprocessing

Removed non-alphabetic characters

Lowercased text

Tokenized words

Removed English stopwords

Applied Porter Stemming

2️⃣ Feature Engineering

TF-IDF Vectorization

Vocabulary learned only from training data (prevents data leakage)

3️⃣ Model

Logistic Regression

Stratified 80/20 train–test split

📈 Results
Metric	Score
Training Accuracy	~80%
Test Accuracy	~78–80%

(Results may vary slightly depending on random seed)

🛠 Tech Stack

Python

pandas, numpy

NLTK

scikit-learn

Kaggle API

▶️ How to Run
pip install numpy pandas nltk scikit-learn kaggle


Configure Kaggle API (kaggle.json)

Run the notebook cells sequentially

Model trains and evaluates automatically

✨ Why This Project?

Handles large-scale real-world data

Demonstrates complete NLP pipeline

Avoids common mistakes like data leakage

Uses interpretable ML, not black-box models

🔮 Future Enhancements

N-grams in TF-IDF

Naive Bayes / SVM comparison

Neutral sentiment class

Model deployment as REST API

Transformer-based models

Add arc
