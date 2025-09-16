# Spotify App Reviews Analysis (Machine Learning)

## Overview
This project analyzes user reviews of the Spotify app and applies machine learning for sentiment classification.  
The goal is to understand user opinions (Positive, Negative, Neutral) and visualize common trends in feedback.  

## Features
- Preprocessing of Spotify reviews dataset (Review, Rating, Sentiment).
- Automatic sentiment labeling from ratings.
- Sentiment distribution visualization using Seaborn.
- Logistic Regression classifier using TF-IDF features.
- WordCloud generation for positive/negative reviews.
- Built and tested in Google Colab.

## Sample Results
- Sentiment distribution plot (Positive/Neutral/Negative).
- Confusion matrix for classification performance.
- WordClouds highlighting common terms in reviews.

  <img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/57d21d43-126d-4566-8c9b-624a704e52d7" />
  <img width="790" height="427" alt="image" src="https://github.com/user-attachments/assets/7be178e9-5d5b-43ca-afda-b74638b8730d" />


## How to Run
1. Open the notebook in **Google Colab**:  
   [![Open In Colab](https://colab.research.google.com/drive/1eSsuwj3j4OyHhsLMhar2tROn8lhEYe89?usp=sharing)
2. Install dependencies:
- !pip install pandas numpy matplotlib seaborn scikit-learn wordcloud
3. Upload reviews.csv or use your own dataset.
4. Run all cells to see results (plots, metrics, WordClouds).

## Future Work
- Extend classification to multi-class (Positive/Neutral/Negative).
- Try advanced models (SVM, Random Forest, or deep learning).
- Deploy as a simple web app with Flask or Streamlit.


## Tech Stack
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, WordCloud
- Google Colab for development and execution
