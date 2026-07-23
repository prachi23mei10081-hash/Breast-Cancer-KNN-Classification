# Breast Cancer Classification using K-Nearest Neighbors (KNN)

## Project Description
This project implements a **K-Nearest Neighbors (KNN)** machine learning model to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer Wisconsin Diagnostic Dataset. The project was developed in **Google Colab** as part of an academic assignment.

## Objectives
- Load the Breast Cancer Wisconsin Diagnostic Dataset.
- Explore and understand the dataset.
- Perform data preprocessing.
- Split the dataset into training and testing sets.
- Apply feature scaling using StandardScaler.
- Train a K-Nearest Neighbors (KNN) classifier.
- Evaluate the model using different performance metrics.
- Predict breast cancer classes using the trained model.

## Dataset
- **Dataset Name:** Breast Cancer Wisconsin Diagnostic Dataset
- **Source:** Scikit-learn (`load_breast_cancer`)
- **Number of Samples:** 569
- **Number of Features:** 30
- **Target Classes:**
  - 0 – Malignant
  - 1 – Benign

## Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Machine Learning Workflow
1. Import required libraries.
2. Load the dataset.
3. Explore the dataset.
4. Check for missing values.
5. Separate features and target.
6. Split data into training and testing sets.
7. Apply feature scaling.
8. Train the KNN classifier.
9. Make predictions.
10. Evaluate the model using:
    - Accuracy Score
    - Confusion Matrix
    - Classification Report
11. Draw conclusions based on model performance.

## Results
The KNN classifier successfully classified breast cancer tumors with high accuracy. The evaluation metrics indicate that the model performs well for binary classification on the Breast Cancer Wisconsin Diagnostic Dataset.

## Repository Structure

```
Breast-Cancer-KNN-Classification/
│── Breast_Cancer_KNN_Classification.ipynb
│── README.md
└── requirements.txt
```

## Author
**Prachi Walke**
