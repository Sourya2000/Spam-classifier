# Email Spam Classifier

## Project Overview
This project implements an Email Spam Classifier to automatically **classify emails as Spam or Not Spam**. It follows a typical machine learning pipeline involving data cleaning, analysis, feature extraction, model training, and deployment.

## Steps Involved

- **Data Cleaning and Preprocessing:** Remove noise, format text data properly, and prepare it for modeling.
- **Statistical Data Analysis & Visualization:** Explore dataset characteristics and visualize trends.
- **Tokenization & Vectorization:** Convert text into numerical features using techniques such as TF-IDF or Count Vectorization.
- **Model Training & Validation:** Train models on vectorized features and evaluate performance with metrics such as precision, recall, and accuracy.
- **Email Classification:** Use the trained model to classify incoming emails as Spam or Not Spam.

## Model Training and Classifiers

- Implemented **three Naive Bayes classifiers** for comparative analysis:
  - **Multinomial Naive Bayes (MultinomialNB)** achieved the best precision score of **1.0**.
- Chose **MultinomialNB** as the final model due to its superior precision and performance on text data.

## Prediction Application

- Developed a **full-stack web app** using **Streamlit**.
- The app allows users to input email content and get real-time predictions classifying emails as Spam or Not Spam.

## How to Run

1. Clone the repository
2. Run "email_spam_classifier.ipynb"
3. Run python -m streamlit run pycode.py for navigating through browser
