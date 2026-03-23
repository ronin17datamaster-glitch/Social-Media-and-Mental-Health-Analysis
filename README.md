# Social Media Usage and Mental Health Analysis

This project performs a comprehensive statistical and machine learning analysis to investigate the relationship between social media consumption patterns and mental health outcomes. The study utilizes data processing, visualization, and predictive modeling to identify key stressors and behavioral trends.

---

## Project Overview

The analysis is contained within a Jupyter Notebook (`smmh.ipynb`) and covers the following core areas:

### 1. Data Processing and Cleaning
* [cite_start]**Environment Setup**: Integration with Google Colab and Google Drive for data retrieval[cite: 3].
* [cite_start]**Data Handling**: Utilizing `pandas` and `numpy` for cleaning, handling missing values, and structuring behavioral data[cite: 3].

### 2. Exploratory Data Analysis (EDA)
* [cite_start]**Visualization**: Implementation of `matplotlib` and `seaborn` to identify correlations between time spent on social media and reported mental health metrics (such as anxiety, depression, and self-esteem)[cite: 3].
* [cite_start]**Feature Engineering**: Selection of relevant variables to improve the predictive power of the models[cite: 3].

### 3. Predictive Modeling
* [cite_start]**Logistic Regression**: A classifier was trained to categorize or predict specific mental health statuses based on usage patterns[cite: 3].
* [cite_start]**Performance Evaluation**: The model achieved an accuracy score of **100%** on the test set, indicating a very strong (or potentially overfit) relationship within the specific dataset provided[cite: 3].
* [cite_start]**Optimization**: Monitored the number of iterations performed by the model to ensure convergence during training[cite: 3].

---

## Key Findings

* [cite_start]**Statistical Correlation**: The analysis highlights how specific social media platforms and the duration of use correlate with mental health indicators[cite: 3].
* [cite_start]**Model Success**: The high accuracy of the Logistic Regression model suggests that social media usage metrics are highly deterministic of the mental health categories defined in the dataset[cite: 3].

---

## Requirements

To run the analysis, you need a Python environment with the following libraries:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

---

## Usage

1.  [cite_start]**Data Source**: Ensure the dataset (e.g., `smmh.csv`) is available in your environment or linked via Google Drive[cite: 3].
2.  **Execution**: Open `smmh.ipynb` in Google Colab or a local Jupyter server.
3.  [cite_start]**Analysis**: Run the cells sequentially to perform the data cleaning, visualization, and model training steps[cite: 3].

---

## Project Structure

* [cite_start]`smmh.ipynb`: Main analysis notebook containing code and visualizations[cite: 3].
* [cite_start]`smmh.csv`: (Required) The raw data used for the analysis[cite: 3].
