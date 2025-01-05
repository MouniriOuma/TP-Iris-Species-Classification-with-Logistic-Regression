# Iris Species Classification with Logistic Regression

This project demonstrates a simple machine learning workflow for classifying iris species using logistic regression. The dataset used is the classic Iris dataset, which contains measurements of sepal length, sepal width, petal length, and petal width for three species of iris flowers: Setosa, Versicolor, and Virginica.


## Project Overview

The goal of this project is to build a logistic regression model to classify iris species based on their sepal and petal measurements. The workflow includes:
- Loading and preprocessing the dataset.
- Splitting the data into training and testing sets.
- Scaling the features using `StandardScaler`.
- Training a logistic regression model.
- Evaluating the model's performance using accuracy and a classification report.
- Visualizing the confusion matrix.


## Code Explanation

The code is structured as follows:

1. **Import Libraries**:
   - Libraries like `numpy`, `pandas`, `matplotlib`, and `seaborn` are imported for data manipulation and visualization.
   - Scikit-learn modules are imported for machine learning tasks.

2. **Load and Preprocess Data**:
   - The dataset is loaded from a CSV file (`TP2_dataset.csv`).
   - Missing values are removed using `dropna()`.

3. **Prepare Features and Target**:
   - Features (`sepal_length` and `sepal_width`) and the target (`species`) are extracted from the dataset.

4. **Split Data**:
   - The dataset is split into training and testing sets using `train_test_split`.

5. **Feature Scaling**:
   - Features are standardized using `StandardScaler` to ensure all features are on the same scale.

6. **Train the Model**:
   - A logistic regression model is trained on the training data.

7. **Evaluate the Model**:
   - Predictions are made on the test set, and the model's accuracy and classification report are computed.

8. **Visualize Results**:
   - A confusion matrix is created and visualized using a heatmap.

