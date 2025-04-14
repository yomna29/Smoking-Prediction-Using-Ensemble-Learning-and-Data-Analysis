# Smoking Prediction Using Ensemble Learning and Data Analysis

## Overview
This project aims to predict smoking status based on health-related features using ensemble learning techniques. It includes data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and interpretability analysis.

## Features
- **Data Analysis**:
  - Univariate, bivariate, and multivariate analysis.
  - Correlation matrix and PCA visualization.
- **Feature Engineering**:
  - Scaling, outlier removal, and encoding categorical variables.
- **Model Training**:
  - Implementation of Bagging, Boosting, and Random Forest from scratch.
  - Hyperparameter tuning using GridSearchCV.
- **Model Interpretability**:
  - Feature importance analysis using SHAP and permutation importance.
  - LIME-based explanation for individual predictions.
- **Final Evaluation**:
  - Test set evaluation with accuracy and classification report.

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `lime`, `shap`, `plotly`

## Usage
1. Clone the repository and navigate to the project directory.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the notebook or script to execute the analysis pipeline:
   ```bash
   python 8175_lab3.ipynb
Results, including selected features, best model, and test accuracy, will be saved to analysis_results.txt.
File Structure
8175_lab3.ipynb: Main notebook containing the complete analysis pipeline.
data.csv: Input dataset for the analysis.
analysis_results.txt: Output file containing the results.
Results
Best-performing model with tuned hyperparameters.
Feature importance rankings.
Final test accuracy and classification report.
