# Movie-Reviews-Sentiment-Analysis

##  Project Overview
This project focuses on **Sentiment Analysis of Movie Reviews** using **Machine Learning techniques**.  
The objective is to classify movie reviews as **positive** or **negative** by comparing different **text representation methods** and **classification algorithms**.

---

## Approaches Used

### Text Vectorization Techniques
Two feature extraction methods were applied to convert text into numerical vectors:

- **Bag of Words (BoW)**
- **TF-IDF (Term Frequency–Inverse Document Frequency)**

---

### Machine Learning Models
Three classification algorithms were implemented and compared:

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Naive Bayes**

Each model was trained and evaluated using both **BoW** and **TF-IDF** representations.

---

## Project Workflow

1. Load and explore the movie reviews dataset  
2. Text preprocessing  
   - Lowercasing  
   - Removing punctuation  
   - Stopwords removal  
   - Tokenization  
3. Feature extraction (BoW & TF-IDF)  
4. Model training  
5. Model evaluation and comparison  

---

## Evaluation Metrics
The models were evaluated using standard classification metrics:

- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## Technologies Used

- Python  
- scikit-learn  
- NLTK  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## Project Structure
NLP_ANALYSE_SENTIMENTS/
│
├── naive_bayes.py
├── logistic_regression.py
├── svm.py
└── IMDB_Dataset.csv
   

