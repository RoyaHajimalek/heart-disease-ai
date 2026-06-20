# Heart Disease Detection using Deep Learning

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
Roya Hajimalek - AI Researcher# heart-disease-ai
Heart disease detection using Deep Learning and SMOTE
