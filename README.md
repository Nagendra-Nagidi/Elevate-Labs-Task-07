# Elevate-Labs-Task-07

In the above Taskfolder you can find all the necessary files regarding Task 7. In the Jupyter file 'task7_solutions.ipynb', I have implemented Support Vector Machine  to diagnose breast cancer tumors as malignant or benign using the Wisconsin Diagnostic Breast Cancer dataset. I have mainly used the scikit learn library in python for creating the SVM model  and for evaluating it in the following manner.

#### Data Preprocessing:
Loaded and inspected the dataset containing 30 tumor features \
Encoded categorical labels (Malignant/Benign → 1/0) \
Split data into training (70%) and testing (30%) sets \
Standardized features.

#### Model Training & Evaluation:
Trained two SVM classifiers: \
1.Linear kernel SVM (simple decision boundary) \
2.RBF kernel SVM (complex non-linear boundary) \

####  Decision Boundary Visualization:
Reduced dimensionality to 2D using PCA  \
Visualized decision boundaries showing clear separation between classes \
Linear kernel: Straight boundary \
RBF kernel: Non-linear, flexible boundary \

#### Hyperparameter Tuning:
Performed grid search for RBF kernel parameters: \
Tuned C (regularization) and gamma (kernel influence) \
Best parameters: C=100, gamma=0.01 \
Improved RBF test accuracy to 94%

#### Model Validation:
Used 5-fold cross-validation to evaluate robustness.

