# Text-Classification-using-Naive-Bayes

# 🧠 Text Classification using Naive Bayes

A machine learning project that classifies text into predefined categories using the **Multinomial Naive Bayes algorithm**. This project demonstrates the complete pipeline from data preprocessing to model evaluation and prediction.

---

## 🚀 Project Overview

This project uses Natural Language Processing (NLP) techniques to convert text data into numerical features and applies a Naive Bayes classifier to categorize text inputs.

It includes:

* Data preprocessing
* Feature extraction using Bag of Words
* Model training using Naive Bayes
* Evaluation using accuracy and confusion matrix
* Real-time text prediction

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn

---

## 📂 Dataset

The model is trained on a dataset file:

```
synthetic_text_data.csv
```

It contains:

* `text` → input text data
* `label` → corresponding category

---

## ⚙️ How It Works

### 1. Data Loading

The dataset is loaded using Pandas.

### 2. Train-Test Split

Data is split into training and testing sets (80/20).

### 3. Text Vectorization

* Uses **CountVectorizer**
* Converts text into numerical feature vectors (Bag of Words)

### 4. Model Training

* Algorithm: **Multinomial Naive Bayes**
* Trained on vectorized text data

### 5. Prediction & Evaluation

* Accuracy score is calculated
* Confusion matrix is generated and visualized

### 6. User Input Prediction

* Takes custom text input
* Predicts the category using the trained model

---

## 📊 Output

* Accuracy Score (in percentage)
* Confusion Matrix Heatmap
* Predicted label for user input text

---


## 📈 Key Learnings

* Understanding of Naive Bayes algorithm
* Text preprocessing using NLP techniques
* Feature extraction using CountVectorizer
* Model evaluation using confusion matrix
* Real-world application of ML in text classification

---

## 🔮 Future Improvements

* Use TF-IDF instead of CountVectorizer
* Try advanced models (Logistic Regression, SVM, Deep Learning)
* Add web interface using Flask or Streamlit
* Use real-world datasets (spam detection, sentiment analysis)

---

## 👨‍💻 Author

**Darshan Patil**
AI & Data Science Student

* GitHub: https://github.com/darshan6239
* LinkedIn: https://www.linkedin.com/in/darshanpatil8633/

---

## ⭐ If you found this useful

Give this repo a star ⭐ and feel free to contribute!
