# Machine Learning Algorithms Implementation

This project is a collection of machine learning algorithms applied to various datasets. It was developed as part of a bootcamp where the goal was to understand and implement different supervised and unsupervised learning models in Python.

## Algorithms Implemented

1. **Linear Regression (with Polynomial Regression):**
   - Implemented using a vectorized approach to minimize computational time.
   - Calculated Root Mean Square Error (RMSE) to evaluate model performance.
   - Regularization (L2) added to Polynomial Regression to address overfitting.

2. **Logistic Regression:**
   - Built using the sigmoid function for binary classification.
   - Utilized one-vs-all classification for multi-class problems.
   - Trained with gradient descent and achieved 75.57% accuracy.

3. **K-Nearest Neighbors (KNN):**
   - Implemented distance-based classification using a matrix-based simulation to reduce computational cost.
   - Accuracy achieved: 79.1% (using 1000 test examples).

4. **K-Means Clustering:**
   - Implemented unsupervised clustering by repeatedly adjusting the cluster centers based on data point proximity until convergence.

5. **Neural Networks:**
   - Multi-layer neural network implemented with customizable hidden layers and nodes.
   - Forward and backpropagation used for model training.
   - Achieved an accuracy of 53.57% on training data and 52.07% on test data.

## Technology Stack

- **Programming Language:** Python
- **Libraries:** 
  - NumPy (for numerical computations)
  - Pandas (for data manipulation)
  - Matplotlib (for data visualization)
- **Tools:** 
  - Jupyter Notebook
  - Google Colaboratory (for cloud-based execution)

## How to Run the Project

1. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib
2. Open the Jupyter Notebook or Google Colaboratory environment.
3. Load the dataset and follow the individual algorithm implementation steps provided in the notebooks.