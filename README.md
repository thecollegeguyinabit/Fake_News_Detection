# Fake News Detection - Jupyter Notebook

This project demonstrates a machine learning pipeline for detecting fake news using Python. The workflow includes data loading, preprocessing, feature engineering, model training, and evaluation using multiple classifiers.

## Features
- Loads and merges real and fake news datasets
- Cleans and preprocesses text data
- Splits data into training and testing sets
- Vectorizes text using TF-IDF
- Trains and evaluates Logistic Regression, Random Forest, and Gradient Boosting models
- Provides a function to test new articles with all models 

## Dataset
- `resource/Fake.csv`: Fake news articles
- `resource/True.csv`: Real news articles
- `resource/manual_testing.csv`: For manual testing

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage
1. Open `fake_new_detections.ipynb` in Jupyter or VS Code.
2. Run all cells sequentially to reproduce the workflow.
3. Use the provided `testing(news)` function to classify custom news articles.

## Project Structure
- `upload/fake_new_detections.ipynb`: Main notebook
- `resource/`: Contains datasets

