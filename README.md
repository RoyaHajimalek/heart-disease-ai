# Heart Disease Detection using Deep Learning

> This is the baseline version of this project. For an advanced version with multiple model comparisons (Logistic Regression, Random Forest, XGBoost) and cross-validation analysis, see [heart-disease-model-comparison](https://github.com/RoyaHajimalek/heart-disease-model-comparison).

## Overview
This project uses Deep Learning and SMOTE to detect heart disease risk factors from a dataset of 319,795 patients.

## Dataset
- Source: [Kaggle - Personal Key Indicators of Heart Disease (2020)](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)
- Size: 319,795 records, 18 features
- Target: HeartDisease (Yes/No)

## Methods
- Data preprocessing and encoding
- SMOTE for handling imbalanced data
- Neural Network with Dropout layers

## Results
| Model | Accuracy | Recall | AUC |
|-------|----------|--------|-----|
| Baseline (No SMOTE) | 91% | 2% | 0.50 |
| With SMOTE | 81% | 64% | 0.83 |

## Tools
- Python, TensorFlow, Keras
- Scikit-learn, Imbalanced-learn
- Google Colab

## Author
Roya Hajimalek - AI Researcher

## How to Run
1. Download the dataset from the Kaggle link above
2. Open the notebook `heart_disease_ai.ipynb` in Google Colab
3. Upload the dataset CSV file when prompted
4. Run all cells in order
5. Install required packages: `pip install -r requirements.txt`
