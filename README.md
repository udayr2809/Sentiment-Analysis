# Sentiment Analysis Project

## Overview
This project performs sentiment analysis on a dataset of Twitter messages. The goal is to classify the messages as positive or negative based on their content. The project follows a typical machine learning workflow, including data loading, preprocessing, model training, evaluation, and saving.

## Project Structure
1. **Data Loading and Exploration**: Load and inspect the dataset to understand its structure and content.
2. **Data Preprocessing**: Clean and preprocess the text data, including stemming and removal of unnecessary characters.
3. **Model Training**: Train a machine learning model to classify the sentiment of the messages.
4. **Model Evaluation**: Evaluate the model's performance using accuracy and a classification report.
5. **Model Saving**: Save the trained model using `pickle` for future use.

## Details
- **Data**: The dataset consists of Twitter messages labeled as either positive or negative.
- **Preprocessing**: Includes text cleaning, stemming, and converting text to a suitable format for model training.
- **Model**: The model is trained using a machine learning algorithm suitable for text classification.
- **Evaluation**: The model's performance is evaluated using accuracy and classification metrics such as precision, recall, and F1-score.

## Results
- **Training Data Accuracy**: 82.0%
- **Test Data Accuracy**: 75.6%
- **Classification Report**: Shows detailed precision, recall, and F1-score for each class.
