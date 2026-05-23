# 📰 Fake News Prediction using Machine Learning

This project is a Machine Learning based Fake News Detection System that predicts whether a news article is **Real** or **Fake** using **Natural Language Processing (NLP)** and **Logistic Regression**.

The model preprocesses textual news data, converts it into numerical vectors using **TF-IDF Vectorization**, and performs binary classification.

---

## 🚀 Features

- Text preprocessing using NLP
- Stopwords removal
- Stemming using Porter Stemmer
- TF-IDF Vectorization
- Logistic Regression model
- Fake/Real news prediction system
- Model accuracy evaluation

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- NLTK
- Regular Expressions (re)

---

## 📂 Dataset

The dataset used contains news articles labeled as:
- REAL
- FAKE

Dataset file:
```bash
fake_or_real_news.csv
```

---

## ⚙️ Project Workflow

1. Import Dependencies
2. Load Dataset
3. Data Preprocessing
4. Text Cleaning
5. Stopwords Removal
6. Stemming
7. TF-IDF Feature Extraction
8. Train-Test Split
9. Logistic Regression Model Training
10. Model Evaluation
11. Prediction System

---

## 🧠 Machine Learning Model

The project uses:

```python
LogisticRegression()
```

for binary classification of news articles.

---

## 📊 Model Accuracy

| Dataset | Accuracy |
|---------|----------|
| Training Data | ~99% |
| Testing Data | ~98% |

*(Accuracy may vary slightly depending on dataset split.)*

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone <your-repository-link>
```

### 2️⃣ Install Required Libraries

```bash
pip install numpy pandas nltk scikit-learn
```

### 3️⃣ Run the Python File / Notebook

```bash
python fake_news_prediction.py
```

---

## 🔍 Example Prediction

```python
prediction = model.predict(X_new)
```

Output:
```bash
The news is Fake
```

---

## 📌 Future Improvements

- Deploy using Flask/Streamlit
- Use Deep Learning models like LSTM/BERT
- Add live news article prediction
- Improve UI/UX

---

## 👨‍💻 Author

Ignesh Samal

BTech CE Student | Machine Learning Enthusiast
