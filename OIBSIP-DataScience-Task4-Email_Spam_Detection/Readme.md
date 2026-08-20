# Email Spam Detection with Machine Learning

## Overview

A compact NLP machine learning project that classifies messages as **Spam** or **Ham (legitimate)** using TF-IDF text features and three classification algorithms.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains **5,572 SMS messages**:

- Ham: 4,825 (86.59%)
- Spam: 747 (13.41%)

The dataset has no missing values.

## Project Workflow

1. Load and understand the dataset
2. Check class distribution
3. Clean and preprocess text
4. Convert text into TF-IDF features
5. Split data into training and testing sets
6. Train three classifiers
7. Evaluate accuracy, precision, recall and F1-score
8. Visualize the confusion matrix
9. Select the best model
10. Test the model on new messages

## Models Used

- Multinomial Naive Bayes
- Logistic Regression
- Linear SVM

## Model Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Linear SVM | 98.39% | 98.52% | 89.26% | 93.66% |
| Logistic Regression | 97.04% | 99.15% | 78.52% | 87.64% |
| Multinomial Naive Bayes | 96.95% | 99.15% | 77.85% | 87.22% |

**Best Model: Linear SVM**

Linear SVM achieved the highest accuracy and F1-score, making it the best overall model in this experiment.

## Confusion Matrix

The confusion matrix shows the number of messages correctly and incorrectly classified.

For this project:

- **True Negative (TN):** Ham correctly classified as Ham
- **False Positive (FP):** Ham incorrectly classified as Spam
- **False Negative (FN):** Spam incorrectly classified as Ham
- **True Positive (TP):** Spam correctly classified as Spam

For spam detection, **False Negatives are particularly important** because they represent spam messages that were missed and allowed to pass as legitimate messages.

The Linear SVM achieved approximately **89.26% recall for spam**, meaning it successfully detected most of the actual spam messages.

## Sample Predictions

The trained model correctly classified:

- Promotional prize message → **Spam**
- Normal meeting message → **Ham**

## Folder Structure

```text
DataScience-Task4-EmailSpamDetection/
│
├── Main.ipynb
├── spam.csv
└── README.md
```

## Objective

The goal is to demonstrate a complete NLP classification workflow using text preprocessing, TF-IDF feature extraction, multiple classifiers, evaluation metrics, and confusion-matrix analysis.
