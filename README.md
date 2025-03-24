# Sentiment Analysis and Recommender System  

## 📌 Project Overview  
This project focuses on **sentiment analysis** and a **recommender system** using Amazon product reviews from 2014. The goal is to classify user reviews as **positive** or **negative** and provide personalized product recommendations based on sentiment insights.  

## 🚀 Features  
- **Sentiment Analysis** using machine learning and deep learning models:
  - Naïve Bayes (Multinomial & Bernoulli)
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Convolutional Neural Networks (CNN)  
- **Recommender System**:
  - Collaborative Filtering (KNN-based)
  - Content-Based Filtering (TF-IDF)
  - Hybrid Recommendation Approach  
- **Data Preprocessing**:
  - Tokenization, stopword removal, TF-IDF vectorization  

# Experimental Results
The experimental results indicate that Logistic Regression achieved the highest accuracy of 97.30%, outperforming other models in sentiment classification. Naïve Bayes (Multinomial) also performed well with 92.32% accuracy, while Bernoulli Naïve Bayes had slightly lower accuracy at 88.56%. The KNN model results are also strong with an accuracy of 87.52%. CNN demonstrated a lower accuracy of 65.75%, suggesting that it may require more training data or hyperparameter tuning for better performance. 

The recommender system, implemented using a KNN classifier, achieved an accuracy of 90.69%, effectively predicting user preferences based on product reviews. It attained a precision of 91%, ensuring that recommended products closely matched user interests. With a recall of 91%, the system successfully identified relevant products for users, minimizing missed recommendations. The overall performance, reflected in an F1-score of 91%, highlights the system’s ability to balance precision and recall, providing accurate and personalized product suggestions.


