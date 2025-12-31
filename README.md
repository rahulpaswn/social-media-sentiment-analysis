# Social Media Sentiment Analysis 🚀

An end-to-end NLP machine learning project that classifies social media posts
into **Positive, Negative, or Neutral** sentiments.

## 🔍 Problem Statement
Companies want to understand public opinion about their brand from social media posts.
Manual analysis is slow and inefficient.

## 💡 Solution
Built a sentiment classification system using NLP techniques and machine learning
to automatically analyze social media text.

## 🛠 Tech Stack
- Python
- NLP (Text Cleaning, Stopwords Removal)
- TF-IDF Vectorizer
- Logistic Regression
- Streamlit (Deployment)
- Docker

## 📊 Dataset
Social media posts containing text, sentiment labels, platform, and engagement metadata.

## ⚙️ ML Pipeline
1. Text Cleaning
2. Feature Extraction (TF-IDF)
3. Model Training (Logistic Regression)
4. Evaluation
5. Deployment using Streamlit

## ▶️ How to Run Locally
```bash
pip install -r requirements.txt
python train.py
streamlit run app.py
