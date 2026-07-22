# 📊 Twitter Sentiment Analysis using NLP

A Machine Learning project that classifies tweets as positive or negative using Natural Language Processing techniques.

---

## 📌 Project Overview

This project uses text preprocessing, TF-IDF feature extraction and multiple machine learning algorithms to analyze tweet sentiment.

Three models were compared:

- Logistic Regression
- Multinomial Naive Bayes
- Linear SVM

The best-performing model was selected using the F1-score.

---

## 📂 Dataset

- Dataset: NLTK Twitter Samples
- Total Tweets: 10,000
- Positive Tweets: 5,000
- Negative Tweets: 5,000
- Training Samples: 8,000
- Testing Samples: 2,000

---

## 🧹 Text Preprocessing

The preprocessing pipeline includes:

- Lowercase conversion
- URL removal
- User mention removal
- Retweet marker removal
- Hashtag-symbol removal
- Punctuation removal
- Number removal
- Stop-word removal
- Lemmatization

---

## 🧠 Models Used

- Logistic Regression
- Multinomial Naive Bayes
- Linear Support Vector Machine

---

## 📊 Results

| Model | Accuracy | F1 Score |
|---|---:|---:|
| Logistic Regression | 76.35% | 0.756 |
| Multinomial Naive Bayes | 74.85% | 0.733 |
| Linear SVM | 73.85% | 0.734 |

Best model: **Logistic Regression**

---

## 🖼️ Output Screenshots

### Dataset and Preprocessing

![Dataset](images/dataset.png)

### Model Comparison

![Model Comparison](images/model_comparison.png)

### Classification Report

![Classification Report](images/classification_report.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### Sample Predictions

![Predictions](images/predictions.png)

### Model Saved

![Model Saved](images/model_saved.png)

---

## 🛠️ Technologies Used

- Python
- NLTK
- Pandas
- NumPy
- Scikit-learn
- TF-IDF
- Matplotlib
- Seaborn
- Joblib

---

## ▶️ How to Run

1. Open `Twitter_Sentiment_Analysis.ipynb` in Google Colab or Jupyter Notebook.
2. Install the libraries from `requirements.txt`.
3. Run all cells in order.
4. View the model comparison, classification report and confusion matrix.
5. Test custom sentences using the prediction function.

---

## 🚀 Future Improvements

- Add neutral-sentiment classification.
- Use a larger real-world Twitter dataset.
- Compare the results with BERT or RoBERTa.
- Deploy the model using Streamlit or Flask.

---

## 👨‍💻 Author

**Prajwal Sonawane**

M.Tech – AI in Signal Processing  
COEP Technological University
