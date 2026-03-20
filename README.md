Fake News Classification using NLP
Overview
This project focuses on detecting whether a news article is Real or Fake using Natural Language Processing (NLP) and Machine Learning techniques.
With the increasing spread of misinformation online, this system helps automate fake news detection by analyzing textual content and identifying patterns associated with misleading information.
Abstract
The rapid spread of misinformation through online platforms has made fake news detection an important problem in NLP. This project builds a machine learning model to classify news articles as real or fake using a labeled dataset from Kaggle.
Text preprocessing is performed using NLTK techniques such as stopword removal and lemmatization. The processed text is converted into numerical features using TF-IDF vectorization. Two models—Logistic Regression and Naive Bayes—are trained and evaluated using accuracy and F1-score.
A Streamlit-based web application allows users to input news text and receive predictions in real time.

Introduction
Fake news refers to false or misleading information presented as legitimate news. With the rise of digital media, misinformation spreads quickly and can influence public opinion.
This project aims to address this issue by building an automated system that classifies news articles using NLP and machine learning techniques.
Tech Stack
●	Python 
●	Pandas & NumPy
●	NLTK (Natural Language Toolkit)
●	Scikit-learn
●	TF-IDF Vectorizer
●	Streamlit
●	Google Colab
 Dataset
●	Source: Kaggle
●	Contains labeled news articles (Real & Fake)
Project Workflow
1. Data Collection
●	Download dataset from Kaggle
●	Separate real and fake news data
2. Data Preprocessing
●	Convert text to lowercase
●	Remove punctuation and special characters
●	Remove stopwords using NLTK
●	Apply lemmatization
3. Feature Extraction
●	Convert text into numerical form using TF-IDF
●	Capture importance of words in documents
4. Model Training
●	Logistic Regression
●	Naive Bayes
5. Model Evaluation
●	Accuracy Score
●	F1 Score
●	Classification Report
 Logistic Regression performed better.
6. Deployment
●	Built a Streamlit web app
●	User inputs news text
●	System predicts: Real or Fake

Features
●	NLP-based text preprocessing
●	TF-IDF feature extraction
●	Multiple ML models
●	Real-time prediction
●	Simple and interactive UI

How to Run
1.	Clone the repository
2.	Install dependencies:
pip install pandas numpy scikit-learn nltk streamlit
3.	Run the app:
streamlit run app.py
4.	Enter news text and view prediction

Future Enhancements
●	Use deep learning models (BERT, LSTM)
●	Improve dataset size and quality
●	Add explainable AI features
●	Deploy to cloud platforms
