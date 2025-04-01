# 🎬 Sentiment Analysis on IMDB Movie Reviews using RNN (LSTM)

## 🚀 Project Overview

This project demonstrates how to perform sentiment analysis on IMDB movie reviews using a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) layers in Python with TensorFlow/Keras. The goal is to accurately classify movie reviews into positive or negative sentiments.

## 📌 Dataset

- **Dataset Used:** [IMDB Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Description:** Contains 50,000 movie reviews labeled as either positive or negative.

The dataset must be placed inside the `data/` directory:

## ⚙️ Technical stack

- **Python**
- **TensorFlow / Keras**
- **Pandas, NumPy, Matplotlib, scikit-learn**

## 📖 Notebook contents

1. **Data loading & cleaning**
   - Loading IMDB dataset
   - Cleaning HTML tags and missing values

2. **Text preprocessing**
   - Tokenization of text data
   - Sequence padding to standardize input lengths

3. **Model construction**
   - Building an embedding layer
   - LSTM layers with regularization (Dropout, L2)

4. **Training and evaluation**
   - Splitting dataset (80/20 train-validation)
   - Training model with class weighting to handle class imbalance
   - Evaluating with accuracy and confusion matrix

5. **Results & visualization**
   - Accuracy metrics
   - Confusion matrix visualization for performance interpretation
