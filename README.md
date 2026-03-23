# Social Media Usage and Mental Health Analysis

This project explores the relationship between social media consumption and various mental health indicators using statistical analysis and machine learning. [cite_start]By processing behavioral data, the study identifies patterns that correlate with mental health outcomes and evaluates the effectiveness of different classification models in predicting these states. [cite: 3, 4]

---

## Project Overview

The analysis is conducted through a structured data science pipeline implemented in a Jupyter Notebook:

### 1. Data Acquisition and Cleaning
* [cite_start]**Data Integration**: The project utilizes datasets hosted on Kaggle and integrates with Google Colab for streamlined processing. [cite: 4]
* [cite_start]**Pre-processing**: Standard data cleaning procedures are applied using `pandas` and `numpy` to prepare the features for statistical modeling. [cite: 4]

### 2. Exploratory Data Analysis (EDA)
* [cite_start]**Visual Correlation**: The analysis uses `matplotlib` and `seaborn` to visualize how social media usage metrics relate to mental health scores. [cite: 3, 4]
* [cite_start]**Feature Selection**: Identifying the most impactful social media behaviors to serve as predictors for the machine learning models. [cite: 3]

### 3. Machine Learning Models
The project implements and compares multiple classification algorithms to predict mental health status:
* [cite_start]**Logistic Regression**: Used to establish a baseline for classification, achieving high accuracy in identifying mental health categories based on usage data. [cite: 3]
* [cite_start]**Gaussian Naive Bayes**: An alternative probabilistic model was implemented, achieving an accuracy of approximately **94.4%** on the test dataset. [cite: 4]
* [cite_start]**Performance Evaluation**: Models are evaluated based on their accuracy scores and their ability to generalize to new, unseen data. [cite: 3, 4]

---

## Key Findings

* [cite_start]**Predictive Accuracy**: The high performance of the Gaussian Naive Bayes and Logistic Regression models suggests that social media usage patterns provide significant signals regarding an individual's mental health status. [cite: 3, 4]
* [cite_start]**Model Convergence**: Logistic Regression results were verified through iteration monitoring to ensure the model reached an optimal solution. [cite: 3]

---

## Requirements

To run this analysis, the following Python libraries are required:
* [cite_start]`pandas` [cite: 3, 4]
* [cite_start]`numpy` [cite: 3, 4]
* [cite_start]`matplotlib` [cite: 3]
* [cite_start]`seaborn` [cite: 3]
* [cite_start]`scikit-learn` [cite: 4]

---

## Usage

1. [cite_start]**Environment**: It is recommended to run the notebook in Google Colab or a local Jupyter environment. [cite: 3, 4]
2. [cite_start]**Data**: Ensure the required dataset (e.g., `smmh.csv`) is placed in the appropriate directory or linked via Google Drive as specified in the code. [cite: 3]
3. [cite_start]**Execution**: Run the notebook cells sequentially to execute the data cleaning, visualization, and model training phases. [cite: 3]
