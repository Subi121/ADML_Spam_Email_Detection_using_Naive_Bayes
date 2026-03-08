# Spam Email Detection using Naive Bayes

## Project Overview
Spam emails are a major problem in digital communication.  
This project builds a simple machine learning model to classify emails as **Spam** or **Not Spam** using **Naive Bayes algorithms**.

The system processes email text, extracts features, and predicts whether the message is spam based on learned patterns.

---

## Objective
- Build a spam email classifier using **Naive Bayes**.
- Convert email text into numerical features using **Bag of Words** and **TF-IDF**.
- Train and compare different Naive Bayes models.
- Evaluate the models using classification metrics.

---

## Models Used

### 1. Bag of Words + Multinomial Naive Bayes
Counts how many times words appear in an email and uses those counts to detect spam patterns.

### 2. TF-IDF + Multinomial Naive Bayes
Assigns higher importance to meaningful words and lower importance to common words, improving classification performance.

### 3. TF-IDF + Gaussian Naive Bayes
Uses TF-IDF values as continuous features and applies Gaussian probability distribution for classification.

---

## Features
- Email text preprocessing
- Feature extraction using:
  - Bag of Words (BoW)
  - TF-IDF
- Spam classification using Naive Bayes
- Performance evaluation using standard metrics

---

## Evaluation Metrics
The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

---

## Project Workflow
1. Load the dataset  
2. Preprocess email text  
3. Convert text into numerical features (BoW / TF-IDF)  
4. Train Naive Bayes models  
5. Evaluate model performance  

---

## Use Cases
- Email spam filtering systems
- SMS spam detection
- Cybersecurity email monitoring
- Fraud and phishing detection

---

## Conclusion
Naive Bayes classifiers provide an efficient and simple solution for spam detection.  
Among the tested models, **TF-IDF + Multinomial Naive Bayes** achieved the best performance because it highlights important spam-related words while reducing the effect of common words.

---
