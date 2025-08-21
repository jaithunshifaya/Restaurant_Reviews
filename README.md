# 🍽️ Restaurant Reviews Sentiment Analysis

## 📌 Project Overview

This project analyzes restaurant reviews and classifies them as Positive or Negative using Natural Language Processing (NLP) and Machine Learning techniques.
The system is deployed so that users can input a review and instantly receive the sentiment prediction.

---

## 🚀 Features

✅ Preprocessing of text (cleaning, stopword removal, stemming/lemmatization).

✅ Feature extraction using Bag of Words / TF-IDF.

✅ Model training with machine learning algorithms (e.g., Naive Bayes, Logistic Regression, SVM).

✅ Deployed as a Flask web app / Streamlit interface (whichever you used).

✅ User-friendly interface for sentiment prediction.

---

## 🛠️ Tech Stack

Language: Python

Libraries:

pandas, numpy – Data handling

nltk, re – Text preprocessing

scikit-learn – Machine Learning models

matplotlib, seaborn – Data visualization

Deployment: Flask / Streamlit / Heroku / GitHub

---

## 📂 Project Structure
Restaurant-Reviews-Sentiment-Analysis-Deployment/

│── dataset/                     # Dataset files (e.g., Restaurant_Reviews.tsv)

│── Sentiment Analysis of Restaurant Reviews.ipynb  # Jupyter notebook

│── app.py                        # Flask/Streamlit app file

│── requirements.txt              # Dependencies

│── README.md                     # Project documentation

│── templates/ (if Flask)         # HTML templates

│── static/ (if Flask)            # CSS/JS files

---

## ⚙️ Installation & Usage

Clone the repository

git clone https://github.com/jaithunshifaya/Restaurant_Reviews.git

cd Restaurant_Reviews


Install dependencies

pip install -r requirements.txt


Run the application

python app.py


Open in browser

Go to http://127.0.0.1:5000/ to test the app.

---

## 📊 Model Performance

Accuracy: ~85-90% (depending on model)

Evaluation Metrics: Precision, Recall, F1-Score

---

## 🔮 Future Enhancements

Add more restaurant datasets for higher accuracy.

Use Deep Learning (LSTM, BERT) for better sentiment classification.

Deploy on cloud platforms (AWS, Azure, GCP).

Add multilingual support.
