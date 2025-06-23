# 📰 Fake News Detection Web App

A full-stack web application to detect fake news articles using machine learning and Django. Users can enter any news article or paragraph, and the app will classify it as either **Fake News** or **Real News**.

---

## 🚀 Features

- Built using **Logistic Regression** and **TF-IDF vectorizer**
- Integrated with a **Django backend**
- Clean **Bootstrap UI** for easy interaction
- Supports real-time news classification

---


## 🛠️ Tech Stack

- Python 3
- Django 5
- Scikit-learn
- Pandas
- Bootstrap 5 (via CDN)
- HTML, CSS

---

## 🧠 How It Works

1. Dataset of real and fake news is used to train a machine learning model.
2. The text is converted into numerical form using **TF-IDF vectorization**.
3. A **Logistic Regression** model is trained and saved.
4. Django loads the model and makes predictions based on user input via a web form.

---

## 📦 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/sarang-7/fake-news-detection.git
cd fake-news-detection
