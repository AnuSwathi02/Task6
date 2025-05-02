# Anu Swathi - Task6
# K-Nearest Neighbors (KNN) Classification - Iris Dataset 🌸

This repository contains a comprehensive implementation of the **K-Nearest Neighbors (KNN)** classification algorithm using the **Iris dataset**. The objective of this project is to understand how KNN works for classification problems, experiment with different 'k' values, and visualize decision boundaries.

## 📌 Objective

1.Understand and implement KNN for classification tasks.

2.Explore the impact of feature normalization and different 'k' values.

3.Evaluate model performance using accuracy, confusion matrix, and classification report.

4.Visualize decision boundaries using two features.

## 🛠️ Tools & Libraries

1.Python 🐍

2.Scikit-learn

3.Pandas

4.Matplotlib

5.Seaborn

6.NumPy

## 📊 Dataset

- **Name**: Iris Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Features**: Sepal length, Sepal width, Petal length, Petal width
- **Target**: Species (Iris-setosa, Iris-versicolor, Iris-virginica)

## 🚀 Project Steps

1. **Load and preprocess the dataset**  
   (i) Drop `Id` column
   (ii) Encode species labels
   (ii) Normalize feature values using `StandardScaler`

2. **Split the dataset**  - 80% training, 20% testing

3. **Train the model**  - Use `KNeighborsClassifier` from `scikit-learn` with default `k=5`

4. **Model evaluation**  
   (i) Accuracy
   (ii) Confusion matrix
   (iii) Classification report

5. **Hyperparameter tuning**  
   (i) Experiment with `k` values from 1 to 20
   (ii) Plot accuracy vs. `k`

6. **Decision boundary visualization**  
   (i) Use first 2 features for 2D visualization
   (ii) Highlight class regions

## 📷 Visual Outputs

1.Accuracy vs. K plot

2.Decision boundary plot (using two features)


