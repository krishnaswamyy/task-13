====================================================
TASK 13: PCA – DIMENSIONALITY REDUCTION
====================================================

OBJECTIVE
---------
To apply Principal Component Analysis (PCA) on the
digits dataset in order to reduce dimensionality
and analyze its effect on classification accuracy.


DATASET
-------
Digits Dataset (built-in Scikit-learn dataset)
Number of Samples: 1797
Number of Features: 64
Classes: Digits 0 to 9

Note: No external dataset download is required.


LIBRARIES USED
--------------
- Python
- NumPy
- Matplotlib
- Scikit-learn


METHODOLOGY
-----------
1. Load the digits dataset using Scikit-learn
2. Perform feature scaling using StandardScaler
3. Split the data into training and testing sets
4. Train Logistic Regression without PCA
5. Apply PCA with different numbers of components
6. Train Logistic Regression with PCA-transformed data
7. Compare accuracy before and after PCA
8. Plot explained variance curve
9. Visualize data using 2D PCA


ALGORITHM USED
--------------
- Principal Component Analysis (PCA)
- Logistic Regression


EVALUATION METRICS
------------------
- Classification Accuracy
- Explained Variance Ratio


OUTPUTS
-------
- Accuracy without PCA
- Accuracy with PCA (2, 10, 30, 50 components)
- Explained Variance Plot
- 2D PCA Scatter Plot


CONCLUSION
----------
PCA successfully reduces the dimensionality of the
dataset while preserving most of the important
information. Classification accuracy remains high
even after dimensionality reduction, demonstrating
the effectiveness of PCA.
