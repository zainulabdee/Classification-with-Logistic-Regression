Task 4: Classification with Logistic Regression
Dataset: Breast Cancer Wisconsin (from scikit-learn)
Objective: Build and evaluate a binary classification model using logistic regression.

----

Overview
This project applies logistic regression to classify tumors as malignant or benign using medical imaging features. The goal is to train a predictive model and evaluate its performance using appropriate classification metrics.

------

Dataset Details
1. Source: Scikit-learn built-in dataset
2. Target Variable: target
   >   0 = Malignant
   >   1 = Benign
3. Features: Mean values of nuclear properties (radius, texture, area, etc.)

-----

Tools Used
1. Python
2. Pandas
3. NumPy
4. Scikit-learn
5. Matplotlib

----

Steps Performed
1. Loaded and explored the dataset
2. Split the data into training and testing sets
3. Standardized features using StandardScaler
4.Trained a logistic regression model using LogisticRegression
5. Evaluated the model using:
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC Score
6. Plotted the ROC Curve
7. Visualized and explained the sigmoid function

-----

Evaluation Metrics
- Confusion Matrix: Shows true positives, true negatives, false positives, and false negatives
- Precision: How many predicted positives are truly positive
- Recall: How many actual positives were correctly predicted
- ROC-AUC Score: Measures overall model performance

-----

Sigmoid Function
The sigmoid function is used in logistic regression to map any real-valued number into a probability between 0 and 1.
Formula:
  sigmoid(z) = 1 / (1 + e^(-z))

-----
Conclusion
Logistic Regression was successfully used to classify breast cancer samples. The model performed well across all key metrics, and the ROC curve and sigmoid function provided deeper insights into model confidence and decision thresholds.

