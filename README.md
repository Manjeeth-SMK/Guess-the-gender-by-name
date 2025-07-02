# 👤 Guess the Gender by Name

This project predicts a person's gender based on their name using a machine learning model (Naive Bayes) wrapped in a Flask API. It is fully version-controlled and ready for DevOps integration with Git, Docker, and CI/CD support.

---

## 🚀 Features

- Predicts gender from a given name
- Built using Python, Flask, and scikit-learn
- Simple REST API (JSON-based)
- Easy to run locally or deploy via Docker/Heroku
- DevOps-ready: Git-tracked, Dockerized, and CI/CD support

---

## 🧠 How It Works

1. A dataset of names and genders is used to train a Naive Bayes classifier.
2. The name is vectorized using `CountVectorizer`.
3. A Flask API takes a name via POST and returns the predicted gender.

---

