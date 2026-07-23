# Breast Cancer Classification using K-Nearest Neighbors (KNN)

## Project Overview
This project implements a K-Nearest Neighbors (KNN) machine learning model to classify breast cancer tumors as **Malignant** or **Benign** using the Breast Cancer Wisconsin Diagnostic Dataset. The project was developed in **Google Colab** as part of an academic assignment.

## Objectives
- Load the Breast Cancer Wisconsin Diagnostic Dataset.
- Perform data exploration and preprocessing.
- Handle unnecessary columns and prepare the dataset.
- Split the dataset into training and testing sets.
- Apply feature scaling using StandardScaler.
- Train a K-Nearest Neighbors (KNN) classifier.
- Evaluate the model using various performance metrics.
- Find the optimal value of K.
- Predict breast cancer diagnosis.

## Dataset
- **Dataset Name:** Breast Cancer Wisconsin Diagnostic Dataset
- **File Used:** `data.csv`
- **Target Variable:** `diagnosis`
  - `M` → Malignant
  - `B` → Benign
  - **Dataset link:** https://www.kaggle.com/datasets/uciml/breast-cancer-
wisconsin-data

## Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Project Workflow
1. Import required libraries.
2. Upload and load the dataset.
3. Explore the dataset.
4. Remove unnecessary columns.
5. Convert the target variable into numeric values.
6. Split the data into training and testing sets.
7. Perform feature scaling.
8. Train the KNN classifier.
9. Predict test data.
10. Evaluate the model using:
    - Accuracy Score
    - Confusion Matrix
    - Classification Report
11. Find the best value of K.
12. Plot Accuracy vs. K.
13. Draw the final conclusion.

## Results
The K-Nearest Neighbors (KNN) model successfully classified breast cancer tumors with high accuracy. Different values of K were tested to identify the best-performing model. The final classifier demonstrated strong performance in distinguishing malignant and benign tumors.

## Repository Structure

```
Breast-Cancer-KNN-Classification/
│── Breast_Cancer_KNN_Classification.ipynb
│── data.csv
│── README.md
└── requirements.txt
```

## Author
**Prachi Walke**
