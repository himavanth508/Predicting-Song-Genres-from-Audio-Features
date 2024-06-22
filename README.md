# Audio-Based Song Genre Classification Using Machine Learning
## Project Overview
This project aims to classify song genres based on audio data using various machine learning algorithms. The primary focus is on feature extraction, dimensionality reduction through PCA, and model evaluation to determine the most effective classifier.

## Table of Contents
1. Introduction
2. Dataset
3. Feature Extraction
4. Dimensionality Reduction
5. Model Selection and Evaluation
6. Results
7. Conclusion
8. Installation and Usage
9. References
## Introduction
Classifying music genres can enhance recommendation systems, music libraries, and streaming services. This project leverages machine learning techniques to predict song genres from audio features, ultimately identifying the Support Vector Machine (SVM) as the most effective model.

## Dataset
The dataset used includes various audio files labeled with their respective genres. Each audio file is processed to extract meaningful features for classification.

## Feature Extraction
Audio features such as Mel-frequency cepstral coefficients (MFCCs), chroma features, spectral contrast, and tonnetz are extracted from the audio files. These features serve as the basis for model training and classification.

## Dimensionality Reduction
To handle the high dimensionality of the feature set, Principal Component Analysis (PCA) is applied:

Reduced the number of features to 5 principal components, retaining essential information while reducing computational complexity.
## Model Selection and Evaluation
Five different machine learning models were evaluated:

Support Vector Machine (SVM)\
Logistic Regression\
Decision Tree\
K-Nearest Neighbors (KNN)\
Naive Bayes\
Each model was trained and evaluated on the resampled dataset to ensure robust performance.

## Results
SVM emerged as the best-performing model with an accuracy of 84.19%.\
Other models showed varying levels of accuracy but were outperformed by SVM in this context.
## Conclusion
The SVM model's superior performance highlights its effectiveness in classifying song genres from audio data. This project demonstrates the importance of feature selection, dimensionality reduction, and thorough model evaluation in machine learning tasks.

## Installation and Usage
Prerequisites\
Python 3.x\
Required libraries: numpy, pandas, scikit-learn, librosa, matplotlib
