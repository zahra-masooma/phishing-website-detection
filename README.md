# Phishing Website Detection

A machine learning project that classifies websites as phishing or legitimate based on URL structure, domain features, and webpage characteristics.

## What's in this project
- **Baseline models:** Logistic Regression, KNN, SVM, Random Forest, Decision Tree — compared on accuracy, F1-score, and confusion matrices
- **Hyperparameter tuning:** GridSearchCV with 5-fold cross-validation for each model
- **Deep learning:** A feedforward neural network (FFNN) and a 1D CNN
- **Unsupervised feature learning:** A PyTorch autoencoder used to compress features, with classifiers re-trained on the compressed representation

## Tools used
Python, scikit-learn, TensorFlow/Keras, PyTorch, Plotly, pandas

## Notes
This project started as a course assignment and was extended independently with additional model comparisons, real cross-validation, and deep learning approaches. AI assistance (Claude) was used to help debug an evaluation bug and add proper cross-validation to the hyperparameter tuning step; all written analysis and interpretation is my own.
