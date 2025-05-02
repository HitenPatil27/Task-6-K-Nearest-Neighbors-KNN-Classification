# Task6-knn-iris-classification
# Iris Dataset - K-Nearest Neighbors (KNN) Classification

This project was completed as part of the AI & ML Internship Task 6. The goal is to understand and implement KNN (K-Nearest Neighbors) for solving classification problems.

---

## Objective
Learn how to:
- Apply the KNN algorithm
- Normalize features for distance-based learning
- Choose the optimal value of K
- Evaluate model performance
- Visualize results

---

## Dataset
We used the classic [Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)

---

## Tools & Libraries
- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib & Seaborn** for visualization
- **Scikit-learn** for modeling, scaling, and evaluation

---

## Steps Performed

### 1. Loaded the Dataset
- Read the `Iris.csv` file using pandas.
- Dropped the unnecessary `Id` column.

### 2. Feature & Target Separation
- Separated input features and the target `Species`.

### 3. Normalized the Data
- Used `StandardScaler` to normalize numerical features for fair distance calculation.

### 4. Train-Test Split
- Split the data into 80% training and 20% testing using `train_test_split`.

### 5. KNN Modeling
- Trained multiple KNN models using `KNeighborsClassifier` from scikit-learn.
- Tested values of K from 1 to 20.

### 6. Evaluation
- Used accuracy score to determine the best value of K.
- Plotted Accuracy vs. K.
- Created a confusion matrix for the best model.

---

## Visualizations Included
- Accuracy vs K Plot
- Confusion Matrix Heatmap

---

## Final Outcome
- Identified the best K value for classification.
- Achieved high classification accuracy on the Iris dataset.
- Understood how KNN works and how normalization affects it.

