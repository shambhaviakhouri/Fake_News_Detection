# Fake News Detection using Machine Learning

This project focuses on detecting whether a news article is **Fake** or **Real** using Machine Learning techniques.
The model is trained on a labeled dataset of fake and true news articles and classifies news based on textual patterns.

---

## 📌 Project Overview

Fake news spreads misinformation and creates confusion among people.  
This project uses **Natural Language Processing (NLP)** and **Machine Learning** to analyze news text and predict whether it is fake or real.

> ⚠️ Note: This project performs **text-based classification**, not real-time fact verification.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Dataset

The dataset consists of two CSV files:

- `True.csv` → Contains real news articles  
- `Fake.csv` → Contains fake news articles  

Each dataset contains news text and related metadata.

---

## ⚙️ Methodology

1. Load and combine fake and true news datasets  
2. Label the data (`1` for Real, `0` for Fake)  
3. Clean and preprocess the text data  
4. Convert text into numerical features using **TF-IDF Vectorizer**  
5. Split data into training and testing sets  
6. Train a Machine Learning model  
7. Predict whether a news article is Fake or Real  

---

## 🧠 Machine Learning Concept Used

- **TF-IDF (Term Frequency–Inverse Document Frequency)** for feature extraction  
- Supervised learning for classification  

---

## 📊 Key Observation

- The model predicts based on **language patterns**, not factual correctness  
- Short headlines may sometimes be classified incorrectly due to lack of context  
- Longer, formal news articles give better predictions  

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/shambhaviakhouri/Fake_News_Detection.git
