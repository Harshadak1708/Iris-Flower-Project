# Iris Flower Classification

This project demonstrates building multiple machine learning models to classify Iris flower species based on their physical features.

---

## Project Overview

The Iris dataset contains 150 samples from three species of Iris flowers: *Iris-setosa*, *Iris-versicolor*, and *Iris-virginica*. Each sample has four features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The goal is to predict the species of an Iris flower based on these features.

---

## Stepwise Approach

### 1. Import Libraries

- Loaded essential Python libraries such as pandas, matplotlib, seaborn for data manipulation and visualization.
- Imported scikit-learn modules for data preprocessing, model building, and evaluation.

### 2. Load and Explore Data

- Loaded the Iris dataset.
- Explored data structure and types.
- Performed exploratory data analysis (EDA) with visualizations like pair plots and distribution plots to understand feature relationships and class separability.

### 3. Data Preprocessing

- Encoded the target labels from categorical to numeric form using `LabelEncoder`.
- Scaled numerical features using `StandardScaler` to standardize feature ranges.
- Split data into training and testing sets with `train_test_split`.

### 4. Model Building

- Implemented the following classifiers:
  - K-Nearest Neighbors (KNN)
  - Gaussian Naive Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Gradient Boosting Classifier
- Trained each model on the training data.

### 5. Model Evaluation

- Evaluated model performance on test data.
- Generated accuracy scores, classification reports (precision, recall, F1-score).
- Created confusion matrices and visualized them to assess model robustness.

### 6. Conclusion and Insights

- Compared the accuracy and performance metrics of all classifiers.
- Identified the best-performing model for this problem.
- Discussed potential improvements or future enhancements.

