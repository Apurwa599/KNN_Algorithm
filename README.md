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
