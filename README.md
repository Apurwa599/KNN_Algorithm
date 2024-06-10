## KNN_Algorithm
K-Nearest Neighbors (KNN) is a simple, instance-based learning algorithm used for both classification and regression tasks. 
The main idea is to predict the value or class of a new sample based on the (k)closest samples (neighbors) in the training dataset.
For classification, the predicted class is the most common class among the (k) nearest neighbors. 
For regression, the predicted value is the average (or weighted average) of the values of the ( k) nearest neighbors.

### Key points:
- Distance Metric: Common distance metrics include Euclidean distance, Manhattan distance, and Minkowski distance.
- Choosing \( k \): The value of \( k \) is a crucial hyperparameter that needs to be chosen carefully.
- Smaller \( k \) values can lead to noise sensitivity, while larger \( k \) values can smooth out the decision boundary.

### Implementation 
Import Python Libraries such as numpy ,pandas,matplotlib or seaborn.

### Explanation of the Code

1. Libraries
2. Data Preparation
3. Train-Test Split
4. Model Training
5. Predictions
6. Evaluation.
7. Visualization

### Evaluation Metrics

- Confusion Matrix: Shows the counts of true positives, true negatives, false positives, and false negatives.
- Classification Report: Provides precision, recall, F1-score, and support for each class.

### Decision Boundary

The decision boundary plot helps to visualize how the KNN classifier separates the different classes in the feature space. 
KNN decision boundaries can be quite complex, reflecting the non-linear separability of the data.

KNN is intuitive and simple but can be computationally expensive, especially with large datasets, since it requires storing and searching through all training instances during prediction.
The choice of \( k \) and the distance metric are critical to the model's performance.
