# Spaceship Titanic: End-to-End Machine Learning Project

A  Data Science project focused on exploratory data analysis, advanced feature engineering, and predictive modeling using the Kaggle Spaceship Titanic dataset.

## Project Overview

The objective of this project is to build a robust machine learning pipeline to predict which passengers were transported to an alternate dimension during a spaceship collision. This repository demonstrates a structured, step-by-step approach to solving binary classification challenges.

### Project Structure and Modules

The project is divided into logical development stages:

*   **1_data_preprocessing_and_eda**
    *   Conducting detailed Exploratory Data Analysis (EDA) to identify data patterns.
    *   Handling missing values through imputation and filtering anomalies.
    *   Data visualization using Matplotlib and Seaborn.

*   **2_baseline_models**
    *   Creating domain-specific features from raw data (Feature Engineering).
    *   Encoding categorical variables and performing feature scaling.
    *   Training baseline models like Logistic Regression and Decision Trees to establish benchmarks.

*   **3_advanced_models**
    *   Implementing advanced ensemble methods such as Random Forest and Gradient Boosting.
    *   Hyperparameter tuning to optimize and maximize model performance.
    *   Final model evaluation and comprehensive error analysis.

## Tech Stack and Libraries

*   Language: Python 3.x
*   Data Analysis: Pandas, NumPy
*   Machine Learning: Scikit-Learn
*   Visualization: Matplotlib, Seaborn
*   Environment: Jupyter Notebooks / PyCharm

## Setup and Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/DYB1517/spaceship_titanic_ml
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Navigate to any module folder and run the Python scripts or Jupyter notebooks to explore the workflow.

## Results and Key Findings

*   Extensive feature engineering, including parsing cabin locations and grouping expenses, significantly boosted model accuracy compared to the raw baseline.
*   The final optimized ensemble model achieved competitive performance on the validation set.
