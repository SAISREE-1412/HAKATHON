# DS-1: Spot the Scam 🔍

## 📌 Project Overview
This project detects fraudulent job postings using machine learning. It accepts job listing data in CSV format and flags suspicious listings with fraud probabilities.

## 🧠 Features
- Binary classification: Real vs Fraudulent job postings
- Text preprocessing (title, description)
- Trained ML model (e.g., Logistic Regression / Random Forest)
- Dashboard with:
  - Table of predictions
  - Histogram of fraud probabilities
  - Pie chart of fraud/genuine jobs
  - Top-10 suspicious jobs

## 🛠 Technologies Used
- Python
- Scikit-learn
- Pandas
- Matplotlib / Streamlit
- Joblib

## 🚀 How to Run the Project Locally

- How to Run the Project Locally
- Run the code using Goggle Colab.
- You need to uplod two CSV files in the Goggle Colab before running given isn problem statement.
- Steps : file -> uplod file -> select each csv file -> click on open.
- Access both CSV file from the given link :
  "jobs.csv" - https://drive.google.com/file/d/1PdXqLRKmAoopar97sikErz2iMqEbI_--/view?usp=sharing
  "jobs_test.csv" - https://drive.google.com/file/d/1lwoPGO1pOrMiXwn6caLM4yCkBBUbFmh8/view?usp=sharing
## How the Model Detects Fraudulent Job Listings
The system uses a TF-IDF vectorizer to convert job titles and descriptions into numerical features based on the importance of words. A Random Forest classifier is then trained on this data to distinguish between real and fraudulent job postings. It learns patterns from historical data—for example, listings containing words like "quick money", "limited slots", or "no experience" are often fraudulent. In contrast, listings with structured language and professional terms are more likely to be real. The model identifies such patterns and uses them to predict fraud with high accuracy.

## CODE - 
https://colab.research.google.com/drive/1zYXXNNsnteWSW7Y63DQ65eSLoh6iyQhH?usp=sharing
