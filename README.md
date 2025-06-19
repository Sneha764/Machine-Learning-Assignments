# Answer Relevance Prediction using NLP Embeddings and Regression Models

## Overview
This project focuses on automatically checking how relevant a student’s answer is to a given question, especially across different subjects like Math, History, Chemistry, and Computer Science.
I have used powerful language models like BERT, RoBERTa, and GPT-2 to turn each student's answer into a meaningful vector (i.e., numerical representation of the text). Then, I feed these vectors into regression models to predict a relevance score from 0 to 5 (0 = not applicable, 5 = correct).

In short, this system:
- Understands the meaning of student answers using language models.
- Learns to predict a score that tells how correct or relevant an answer is.
- Helps automate answer grading across subjects using machine learning.

## Methodology
### Embedding Models (to convert text to vectors)
- RoBERTa
- BERT
- GPT-2

### Traditional Regression Models
- Linear Regression
- Polynomial Regression
- Lasso Regression
- Logistic Regression
- Bayesian Linear Regression

### Non-Traditional Regression Models
- Support Vector Regression (SVR)
- Decision Tree Regression
- Random Forest Regression
- Gaussian Process Regression
- K-Nearest Neighbors (KNN) Regression

### Evaluation Metrics
- Accuracy
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)

### ML Tools & Libraries
- scikit-learn (for ML models, GridSearchCV, metrics)
- transformers (HuggingFace) (for RoBERTa, BERT, GPT-2 embeddings)
- pandas, NumPy (for data handling)
- matplotlib, seaborn (for visualizations)

## Author
Sneha Yadav
