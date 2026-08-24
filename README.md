# AI Customer Feedback Intelligence System

## Overview

This project was developed during my AI Training at the Information Technology Institute (ITI).

The goal of this project is to transform unstructured customer reviews into actionable business insights using Natural Language Processing (NLP), Machine Learning, and Business Intelligence techniques.

The system analyzes customer feedback, classifies sentiment, identifies common complaint categories, and presents findings through an interactive Power BI dashboard.

---

## Problem Statement

Organizations receive thousands of customer reviews every day.

Manually analyzing these reviews is time-consuming and inefficient.

This project aims to automate the process by:

- Analyzing customer reviews
- Predicting customer sentiment
- Identifying common complaint categories
- Generating business insights
- Supporting data-driven decision-making

---

## Dataset

### Women's E-Commerce Clothing Reviews Dataset

Dataset Features:

- Review Text
- Rating
- Product Category
- Recommendation Indicator

Dataset Size:

- 22,000+ Customer Reviews

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

- Handling missing values
- Removing duplicates
- Text cleaning
- Lowercasing
- Removing punctuation
- Stopword removal

### 2. NLP Processing

- Tokenization
- Lemmatization
- TF-IDF Vectorization

### 3. Sentiment Classification

Machine Learning Models:

- Logistic Regression
- Random Forest

### 4. Customer Complaint Analysis

Unsupervised Learning:

- K-Means Clustering

Purpose:

- Discover hidden complaint categories
- Identify recurring customer issues

### 5. Business Intelligence Dashboard

Interactive Power BI dashboard used to visualize:

- Sentiment Distribution
- Recommendation Rate
- Review Rating Distribution
- Product Category Analysis
- Complaint Clusters
- Customer Insights

---

## Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- NLTK
- Scikit-Learn
- Matplotlib
- Seaborn

### Machine Learning

- Logistic Regression
- Random Forest
- K-Means Clustering

### Business Intelligence

- Power BI

---

## Key Insights

- Over 22,000 customer reviews analyzed.
- Positive sentiment dominated customer feedback.
- "Tops" was the most reviewed product category.
- Sizing-related issues appeared as one of the most common customer complaints.
- Logistic Regression outperformed Random Forest for sentiment classification.

---

## Results

### Sentiment Analysis

Successfully classified customer reviews into sentiment categories using NLP and Machine Learning techniques.

### Complaint Clustering

Identified common customer complaint themes through K-Means clustering.

### Business Insights

Generated actionable insights to help businesses improve customer experience and product quality.

---

## Project Structure

```text
AI-Customer-Feedback-Intelligence-System/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── analysis.ipynb
│
├── models/
│   ├── logistic_regression.pkl
│   └── random_forest.pkl
│
├── dashboard/
│   └── Customer_Feedback_Dashboard.pbix
│
├── visuals/
│   ├── sentiment_distribution.png
│   ├── clusters.png
│   └── wordcloud.png
│
├── src/
│   ├── preprocessing.py
│   ├── training.py
│   ├── clustering.py
│   └── evaluation.py
│
├── requirements.txt
└── README.md
```

---

## Dashboard Preview

Add screenshots of your Power BI dashboard here.

---

## Future Improvements

- Deep Learning Models (LSTM, BERT)
- Real-Time Review Analysis
- Streamlit Web Application
- Deployment on Cloud Platforms
- Advanced Topic Modeling

---

## Author

**[Your Name]**

Data Science Student

AI Training - Information Technology Institute (ITI)

LinkedIn: [Your LinkedIn]

GitHub: [Your GitHub]
