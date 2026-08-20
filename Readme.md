
# OASIS INFOBYTE — Data Science Internship

A collection of practical Data Science and Machine Learning projects completed as part of my **Oasis Infobyte Data Science Internship (OIBSIP)**.

The internship focused on applying Data Science concepts to practical datasets through data cleaning, exploratory data analysis, visualization, feature engineering, machine learning, model evaluation, and prediction.

---

## Internship

- **Organization:** Oasis Infobyte
- **Program:** Data Science Internship
- **Duration:** 1 Month
- **Start Date:** 05 August 2026
- **Intern:** Saksham Chauhan

The internship provided hands-on exposure to Data Science concepts through practical project-based implementation.

---

# Projects

| Task   | Project                    | Type                      |
| ------ | -------------------------- | ------------------------- |
| Task 1 | Iris Flower Classification | Classification            |
| Task 2 | Unemployment Analysis      | Exploratory Data Analysis |
| Task 3 | Car Price Prediction       | Regression                |
| Task 4 | Email Spam Detection       | NLP Classification        |
| Task 5 | Sales Prediction           | Regression                |

---

# Tech Stack

### Programming & Data Analysis

- Python
- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-learn
- Logistic Regression
- Linear Regression
- Ridge Regression
- K-Nearest Neighbours
- Decision Tree
- Random Forest
- Extra Trees
- Multinomial Naive Bayes
- Linear SVM

### Natural Language Processing

- TF-IDF
- Text preprocessing
- Stopword removal
- N-gram features

### Development Tools

- Jupyter Notebook
- Git
- GitHub

---

# Skills Demonstrated

Across the five projects, I worked through an end-to-end Data Science and Machine Learning workflow.

- Dataset loading and inspection
- DataFrame creation and manipulation
- Data cleaning
- Missing-value analysis
- Duplicate detection
- Data-type handling
- Exploratory Data Analysis
- Statistical analysis
- Data visualization
- Correlation analysis
- Outlier detection
- Outlier removal
- Feature engineering
- Feature selection
- Categorical encoding
- Feature scaling
- Train-test splitting
- Classification
- Regression
- Natural Language Processing
- TF-IDF feature extraction
- Model training
- Model comparison
- Regularization
- Classification evaluation
- Regression evaluation
- Confusion-matrix analysis
- Residual analysis
- Feature importance
- Final prediction

---

# Task 1 — Iris Flower Classification

## Objective

Build a Machine Learning classification model capable of identifying the species of an Iris flower from its physical measurements.

The three target classes are:

- Setosa
- Versicolor
- Virginica

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Work Performed

- Loaded the Iris dataset using Scikit-learn.
- Inspected the dataset shape and structure.
- Checked data types and missing values.
- Generated descriptive statistics.
- Performed Exploratory Data Analysis.
- Created feature distribution visualizations.
- Created scatter plots and pair plots.
- Generated a correlation heatmap.
- Analyzed feature discriminative power.
- Selected relevant features for modelling.
- Performed train-test splitting.
- Applied feature scaling where required.
- Trained multiple classification algorithms.
- Evaluated models using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
- Compared the classification models.
- Selected the best-performing model.

## Key Finding

The analysis showed that **petal length and petal width are the most discriminative features** for separating Iris species.

The Setosa class is particularly easy to distinguish, while Versicolor and Virginica have greater overlap.

---

# Task 2 — Unemployment Analysis

## Objective

Analyze unemployment data in India to identify regional and temporal trends, with particular attention to the impact of the COVID-19 period.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Work Performed

- Loaded the unemployment dataset.
- Inspected dataset shape and structure.
- Checked for missing values.
- Converted and handled date-related columns.
- Performed descriptive statistical analysis.
- Calculated region-wise average unemployment rates.
- Analyzed month-wise unemployment trends.
- Created time-series visualizations.
- Compared unemployment trends across major states/regions.
- Identified states with higher average unemployment rates.
- Generated a correlation heatmap.
- Analyzed the relationship between:
  - Unemployment Rate
  - Employment Rate
  - Labour Participation Rate
- Compared pre-COVID and post-COVID unemployment levels.

## Key Findings

The analysis demonstrated that unemployment rates varied considerably across different regions of India.

The temporal analysis also showed significant changes around the COVID-19 period, highlighting the impact of the pandemic on employment conditions.

The project focused primarily on **Exploratory Data Analysis and interpretation rather than predictive Machine Learning**.

---

# Task 3 — Car Price Prediction

## Objective

Build a regression model capable of predicting the selling price of a used car based on vehicle characteristics.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Work Performed

- Loaded the vehicle dataset.
- Inspected the dataset structure.
- Cleaned unnecessary columns.
- Checked missing values and duplicates.
- Standardized categorical values.
- Extracted car brands from car names.
- Created a **Car Age** feature from the manufacturing year.
- Analyzed selling-price distributions.
- Investigated extreme price values.
- Analyzed mileage outliers.
- Performed feature selection.
- Encoded categorical variables.
- Split the dataset into training and testing sets.
- Trained multiple regression models.
- Compared model performance.
- Evaluated models using:
  - MAE
  - RMSE
  - R² Score
- Generated feature importance visualizations.
- Created actual-vs-predicted price visualizations.

## Model Improvement

The initial Random Forest model achieved approximately:

**R² Score: 0.587**

After improving the preprocessing, feature engineering, feature selection and modelling workflow, the final experiment achieved:

### Best Model — Extra Trees

- **R² Score:** 0.8299
- **MAE:** 72,838.83
- **RMSE:** 108,132.84

## Key Findings

The modelling process demonstrated that data preparation can have a major effect on regression performance.

Important predictive factors included:

- Car Age
- Kilometres Driven
- Transmission
- Fuel Type
- Brand

**Car Age** was one of the strongest features in the final tree-based model.

The improvement from approximately **58.7% R² to 82.99% R²** demonstrated the importance of proper data preprocessing and model selection.

---

# Task 4 — Email Spam Detection

## Objective

Build an NLP-based binary classification system that distinguishes between legitimate messages and spam.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- NLP
- TF-IDF
- Jupyter Notebook

## Dataset Distribution

The dataset contained:

- **5,572 total messages**
- **4,825 Ham messages**
- **747 Spam messages**

Class distribution:

- Ham: **86.59%**
- Spam: **13.41%**

## Work Performed

- Loaded the SMS spam dataset.
- Checked the class distribution.
- Checked missing values.
- Performed text preprocessing.
- Converted text to lowercase.
- Removed unnecessary punctuation.
- Processed stopwords.
- Converted text into numerical features using TF-IDF.
- Split the dataset into training and testing sets.
- Trained multiple classification models.
- Evaluated models using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
- Compared the classification algorithms.
- Tested the final model on sample messages.

## Models

Three classifiers were evaluated:

1. Multinomial Naive Bayes
2. Logistic Regression
3. Linear SVM

## Results

| Model                   |         Accuracy |        Precision |           Recall |         F1-Score |
| ----------------------- | ---------------: | ---------------: | ---------------: | ---------------: |
| Multinomial Naive Bayes |           96.95% |           99.15% |           77.85% |           87.22% |
| Logistic Regression     |           97.04% |           99.15% |           78.52% |           87.64% |
| **Linear SVM**    | **98.39%** | **98.52%** | **89.26%** | **93.66%** |

## Best Model

### Linear SVM

**Accuracy: 98.39%**

Linear SVM achieved the highest overall accuracy and F1-score among the three tested models.

## Key Finding

Recall is particularly important for spam detection because a false negative means that an actual spam message is incorrectly classified as legitimate.

The Linear SVM achieved a spam recall of approximately **89.26%**, making it the strongest model among the tested approaches.

The project demonstrated the practical use of:

- Text preprocessing
- TF-IDF
- NLP feature extraction
- Binary classification
- Precision/Recall trade-offs
- Confusion-matrix analysis

---

# Task 5 — Sales Prediction

## Objective

Build a regression model to predict product sales based on advertising expenditure across different media channels.

The primary features are:

- TV
- Radio
- Newspaper

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Work Performed

- Loaded the advertising dataset.
- Inspected the dataset.
- Checked missing values.
- Generated descriptive statistics.
- Removed unnecessary/non-predictive columns.
- Created pair plots.
- Analyzed Sales vs TV advertising.
- Analyzed Sales vs Radio advertising.
- Analyzed Sales vs Newspaper advertising.
- Generated a correlation heatmap.
- Investigated potential outliers.
- Performed feature selection.
- Used ANOVA F-score analysis to compare feature importance.
- Performed train-test splitting.
- Trained Linear Regression as a baseline.
- Applied Ridge Regression for regularization.
- Trained a tree-based regression model.
- Compared model performance.
- Evaluated models using:
  - MAE
  - RMSE
  - R² Score
- Performed residual analysis.
- Analyzed which advertising channel had the strongest relationship with sales.

## Feature Selection

Feature analysis was performed to understand which advertising channels contributed most strongly to predicting Sales.

The analysis compared:

- TV
- Radio
- Newspaper

using statistical feature-selection techniques.

## Regularization

Ridge Regression was incorporated to reduce the risk of overfitting and improve the stability of the linear regression model.

## Key Finding

The project demonstrated that different advertising channels do not contribute equally to sales prediction.

The feature-selection and model-analysis stages were used to identify the advertising channel with the strongest predictive relationship with Sales.

---

# Overall Model Summary

| Task   | Problem Type       | Main Technique                          | Best Model / Approach                     |
| ------ | ------------------ | --------------------------------------- | ----------------------------------------- |
| Task 1 | Classification     | Feature Analysis + Classification       | Best classifier based on test performance |
| Task 2 | EDA                | Statistical & Temporal Analysis         | Exploratory Analysis                      |
| Task 3 | Regression         | Feature Engineering + Ensemble Learning | **Extra Trees — R² 0.8299**       |
| Task 4 | NLP Classification | TF-IDF + Classification                 | **Linear SVM — 98.39% Accuracy**   |
| Task 5 | Regression         | Regression + Regularization             | Model selected through evaluation         |

---

# End-to-End Data Science Pipeline

The projects collectively followed an end-to-end Pipeline:

```text
Dataset
   ↓
Data Loading
   ↓
Data Inspection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Visualization
   ↓
Feature Engineering
   ↓
Feature Selection
   ↓
Encoding / Scaling
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Best Model Selection
   ↓
Prediction & Interpretation
```
