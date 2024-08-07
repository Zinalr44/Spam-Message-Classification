# Spam Message Classification

## Overview

This repository provides a solution for classifying spam messages using machine learning algorithms. The script includes data preprocessing, feature extraction, and model evaluation using Support Vector Machine (SVM) and Decision Tree Classifier.

## Features

- **Data Preprocessing**: Cleans and prepares the dataset by removing unnecessary columns and encoding categorical values.
- **Exploratory Data Analysis (EDA)**: Visualizes message length distribution and relationship with spam/ham classification.
- **Feature Extraction**: Uses CountVectorizer to convert text data into numerical features.
- **Model Training and Evaluation**:
  - Trains Support Vector Machine (SVM) and Decision Tree models.
  - Evaluates model performance using accuracy scores.

## Prerequisites

Ensure you have the following Python packages installed:
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `plotly`

You can install the necessary packages using pip:

```bash
pip install pandas matplotlib seaborn scikit-learn plotly
