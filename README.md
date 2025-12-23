# 😊Task: 07 — Emotion Detection from Text  

---

## 📌 Project Overview
Emotion Detection from Text is a Machine Learning and Natural Language Processing (NLP) project developed as part of the **RISE Internship Program**.  
The goal of this project is to automatically classify human emotions from textual messages such as feedback, chats, or student responses.

The model can detect emotions like **joy, sadness, anger, fear, love, and surprise**, making it useful for applications in **education, mental health analysis, and emotion-aware chatbots**.

---

## 🎯 Objective
- To classify emotions from text messages using NLP techniques  
- To apply TF-IDF vectorization for feature extraction  
- To train and evaluate a machine learning classification model  
- To measure performance using precision, recall, F1-score, and accuracy  

---

## 🧠 Emotions Covered
| Label | Emotion |
|-----|--------|
| 0 | Sadness |
| 1 | Joy |
| 2 | Love |
| 3 | Anger |
| 4 | Fear |
| 5 | Surprise |


---

## ⚙️ Technologies Used
- Python  
- Google Colab  
- Pandas & NumPy  
- NLTK  
- Scikit-learn  
- Matplotlib & Seaborn  

---

## 🛠 Methodology
1. Load and explore the dataset  
2. Clean and preprocess text data  
3. Remove stopwords and unwanted characters  
4. Convert text into numerical features using **TF-IDF Vectorization**  
5. Split data into training and testing sets  
6. Train a **Logistic Regression** multi-class classifier  
7. Evaluate the model using classification metrics  
8. Predict emotions for new unseen text  

---

## 📊 Model Evaluation
The model performance is evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

This ensures reliable and balanced emotion classification.  

---

## 🧪 Sample Prediction
```python
Input: "I am very happy and excited today!"
Output: Joy
```

---

Author: Adhi Narayan  
Internship: RISE 3.0 — Machine Learning and AI
