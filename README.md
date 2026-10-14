#  Dimensionality Reduction Mini Project using PCA



##  Project Overview

This project demonstrates how Principal Component Analysis (PCA)
can be used to reduce the number of features in a dataset while
preserving as much useful information as possible.

The project combines PCA with Logistic Regression to understand
how dimensionality reduction affects a machine learning model.

It also compares different numbers of principal components using
explained variance and model evaluation.

The project follows a basic machine learning workflow, including
data splitting, feature scaling, dimensionality reduction,
model training, and evaluation.

---

##  Objectives

- Understand dimensionality reduction in Machine Learning.
- Implement PCA using Scikit-learn.
- Split data into training and testing sets.
- Apply StandardScaler for feature scaling.
- Train a Logistic Regression classification model.
- Compare different numbers of PCA components.
- Analyze explained variance.
- Implement a Scikit-learn Pipeline.
- Understand how preprocessing and PCA work together.

---

##  Concepts Learned

### 1. Train-Test Split

The dataset is divided into training and testing sets.

- Training data is used to fit the model.
- Testing data is used for final evaluation.

### 2. Feature Scaling

StandardScaler standardizes features using the training data's
mean and standard deviation.

This is important because PCA is sensitive to feature scales.

### 3. Principal Component Analysis (PCA)

PCA transforms the original features into a smaller set of
principal components.

These components capture directions of variation in the data.

The goal is to reduce dimensionality while retaining useful
information.

### 4. Explained Variance

Explained variance helps us understand how much of the dataset's
variance is retained by the selected principal components.

A higher cumulative explained variance generally means that
more of the original variance is retained.

### 5. Logistic Regression

Logistic Regression is used as the classification algorithm.

We compare its performance when trained using different numbers
of principal components.

### 6. Scikit-learn Pipeline

A Pipeline combines preprocessing and model-training steps
into a single workflow.

For example:

StandardScaler → PCA → Logistic Regression

This helps organize the workflow and reduces the risk of
data leakage when used correctly.

---

##  Project Workflow

1. Load the dataset.
2. Separate features and target.
3. Split the data into training and testing sets.
4. Standardize the features.
5. Apply PCA with different component counts.
6. Train Logistic Regression models.
7. Compare model performance.
8. Examine explained variance.
9. Use a Scikit-learn Pipeline.
10. Evaluate the final model on the test set.

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- PCA
- Logistic Regression
- StandardScaler
- Train-Test Split
- Pipeline

---

##  Experiments

Different numbers of principal components were tested to
understand their impact on dimensionality reduction and
classification performance.

The experiments focus on:

- Number of components selected.
- Cumulative explained variance.
- Classification performance.
- Trade-off between dimensionality and predictive performance.

The best component count should be selected based on
training-only cross-validation rather than choosing it solely
from test-set results.

---

##  Key Learnings

Through this project, I learned how to:

- Prepare data for Machine Learning.
- Split data into training and testing sets.
- Scale numerical features correctly.
- Reduce feature dimensions using PCA.
- Compare models with different PCA component counts.
- Interpret explained variance.
- Combine preprocessing and modeling using Pipeline.
- Understand the importance of avoiding data leakage.
- Improve model selection using cross-validation.

---

##  Future Improvements

- Use cross-validation to select the best PCA component count.
- Compare PCA with and without dimensionality reduction.
- Evaluate models using Accuracy, Precision, Recall, and F1-score.
- Visualize cumulative explained variance.
- Compare Logistic Regression with other classifiers.
- Perform hyperparameter tuning.
- Evaluate the final selected pipeline on an untouched test set.

---

##  What This Project Demonstrates

This project demonstrates a practical understanding of
dimensionality reduction and its integration into a
classification workflow.

It serves as a foundation for exploring more advanced
Machine Learning techniques and model optimization.

---

##  Author

Md Asad Aftab

Aspiring Machine Learning Engineer | Python | Machine Learning


---

 If you find this project useful, consider giving it a star!
