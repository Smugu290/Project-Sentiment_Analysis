# Project-Sentiment_Analysis
This is my first repository
 # Sentiment Analysis of Restaurant Reviews in Majitar, Sikkim

##Project Overview

This project focuses on performing **Sentiment Analysis** on restaurant reviews collected from restaurants near **Majitar, Sikkim**. The system uses **Machine Learning** and **Natural Language Processing (NLP)** techniques to classify customer reviews into three categories:

- 😊 Positive  
- 😐 Neutral  
- 😞 Negative  

The main objective is to help customers understand restaurant quality through review analysis and assist restaurant owners in identifying customer satisfaction trends.

## Objectives

- Analyze customer opinions from restaurant reviews.
- Automatically classify reviews into sentiment categories.
- Compare different machine learning models.
- Evaluate model performance using standard metrics.
- Build a user-friendly prediction system.

## Dataset Information

The dataset contains **500 restaurant reviews** based on restaurants in and around Majitar, Sikkim.

### Sentiment Classes:

| Sentiment | Approx Count |
|----------|--------------|
| Positive | 170 |
| Neutral | 165 |
| Negative | 165 |

### Sample Review Records:

| Review | Sentiment |
|--------|----------|
| Amazing food and service | Positive |
| Food was okay nothing special | Neutral |
| Very disappointing meal | Negative |

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **NLTK**
- **Matplotlib / Seaborn**
- **Streamlit** (for web app)
- **Pickle** (model saving)

## ⚙️ Project Workflow

1. Data Collection  
2. Data Cleaning & Preprocessing  
3. Text Vectorization using TF-IDF  
4. Model Training  
5. Sentiment Prediction  
6. Performance Evaluation  
7. Web Application Deployment

## 🧹 Text Preprocessing Steps

- Convert text to lowercase
- Remove punctuation
- Remove stopwords
- Tokenization
- Clean unnecessary symbols

## Machine Learning Models Used

### 1. Logistic Regression
A strong baseline model for text classification.

### 2. Naive Bayes
Fast and efficient for NLP tasks.

### 3. Support Vector Machine (SVM)
Best performing model for sparse text datasets.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Sample Results:

| Model | Accuracy |
|------|----------|
| Logistic Regression | 91% |
| Naive Bayes | 88% |
| SVM | 94% |

## 💻 How to Run the Project

### Install Dependencies

bash
>pip install pandas numpy scikit-learn nltk matplotlib seaborn streamlit

## Web App Features
Enter custom review text
Predict sentiment instantly
User-friendly interface
Real-time analysis

## Future Improvements
Use real-time Google/API reviews
Deep learning models (LSTM/BERT)
Multi-language review analysis
Restaurant recommendation system
Interactive dashboards

Applications
Restaurant reputation monitoring
Customer satisfaction analysis
Smart restaurant recommendations
Business intelligence for owners

Conclusion

This project demonstrates how Machine Learning and NLP can be used to automatically analyze restaurant reviews and extract valuable insights. It can help both customers and business owners make informed decisions.

```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn streamlit
