# 😊 Twitter Sentiment Analysis

A Natural Language Processing (NLP) project that classifies tweets as positive or negative based on their textual content using Machine Learning techniques.

---

## 🚀 Project Overview

Social media platforms generate massive amounts of user opinions every day. Analyzing these opinions can help businesses understand customer sentiment, improve products, and make better decisions.

This project uses Natural Language Processing (NLP) and Machine Learning to classify tweets into positive or negative sentiments.

---

## 🎯 Objective

Build a sentiment analysis model capable of predicting whether a tweet expresses a positive or negative sentiment.

---

## 📂 Dataset

**Dataset:** Sentiment140 Twitter Dataset

The dataset contains 1.6 million tweets collected from Twitter.

### Features Used

* Tweet Text

### Target Labels

| Label | Sentiment |
| ----- | --------- |
| 0     | Negative  |
| 1     | Positive  |

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing

* Removed unnecessary columns
* Converted sentiment labels
* Sampled 50,000 tweets for efficient training
* Cleaned tweet text by:

  * Converting to lowercase
  * Removing URLs
  * Removing mentions (@username)
  * Removing special characters
  * Removing stopwords

### 2️⃣ Feature Engineering

Applied **TF-IDF Vectorization** to convert text into numerical features suitable for machine learning models.

### 3️⃣ Model Development

Implemented:

* Logistic Regression

### 4️⃣ Model Evaluation

Evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📈 Results

| Metric    | Score      |
| --------- | ---------- |
| Accuracy  | **75.62%** |
| Precision | **0.76**   |
| Recall    | **0.76**   |
| F1-Score  | **0.76**   |

---

## 🔍 Sample Predictions

### Positive Tweet

```text
I absolutely love this phone. The battery life is amazing!
```

Prediction:

```text
Positive Sentiment 😊
```

### Negative Tweet

```text
Worst customer service ever. Very disappointed.
```

Prediction:

```text
Negative Sentiment 😠
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-Learn
* TF-IDF Vectorizer
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## 📁 Project Structure

```text
Twitter-Sentiment-Analysis/
│
├── Twitter_Sentiment_Analysis.ipynb
├── sentiment_model.pkl
├── vectorizer.pkl
├── README.md
└── training.1600000.processed.noemoticon.csv
```

---

## 🔮 Future Enhancements

* Multi-class sentiment classification
* Deep Learning using LSTM
* BERT-based sentiment analysis
* Real-time Twitter sentiment dashboard
* Web application deployment using Streamlit

---

## 👨‍💻 Author

**R. Kaushik**

AI/ML Internship Project

---

⭐ If you found this project useful, consider giving it a star on GitHub!
