# network_intrusion_detection-using-ml
network_intrusion_detection using ml

#### KNN (K-Nearest Neighbors):
- KNN is a simple and intuitive algorithm used for classification and regression tasks.
- It works by finding the K nearest data points to a given data point based on a distance metric (e.g., Euclidean distance).
- For classification, the class label of the majority of the K nearest neighbors is assigned to the query point.
- For regression, the average of the target values of the K nearest neighbors is assigned to the query point.
- Train Score: 0.987751
- Test Score: 0.982403

#### Logistic Regression:
- Despite its name, logistic regression is used for binary classification tasks.
- It models the probability that a given input belongs to a particular class using the logistic function.
- It learns the relationship between the input features and the binary outcome through a linear regression model followed by a logistic (sigmoid) activation function.
- Train Score: 0.925768
- Test Score: 0.931993

#### Decision Tree:
- Decision trees are versatile supervised learning algorithms used for classification and regression tasks.
- They partition the feature space into a set of rectangular regions and make predictions based on the majority class or average target value within each region.
- The tree structure is constructed recursively by selecting the best feature to split on at each node based on a criterion such as Gini impurity or entropy.
- Train Score: 0.998979
- Test Score: 0.994708

#### Random Forest:
- Random Forest is an ensemble learning technique that builds multiple decision trees during training.
- It introduces randomness in the tree-building process by selecting a random subset of features for each tree and using bootstrapped samples of the training data.
- The final prediction is obtained by averaging the predictions of all individual trees (for regression) or by taking a majority vote (for classification).
- Train Score: 0.99983
- Test Score: 0.996957

#### GBM (Gradient Boosting Machine):
- GBM is another ensemble learning technique that builds an additive model of weak learners (typically decision trees) in a forward stage-wise manner.
- It minimizes a differentiable loss function by adding weak learners sequentially, with each new learner correcting the errors made by the existing ensemble.
- GBM is known for its high predictive accuracy and robustness.

#### XGBM (Extreme Gradient Boosting):
- XGBM is an optimized implementation of gradient boosting with additional features such as regularization, sparsity-awareness, and parallelization.
- It is designed for speed and performance and is widely used in various machine learning competitions and applications.

#### Adaboost (Adaptive Boosting):
- Adaboost is another ensemble method that combines multiple weak learners (often decision trees) to build a strong classifier.
- It assigns higher weights to misclassified data points in each iteration to focus on the difficult examples.
- The final prediction is obtained by weighted majority voting of all individual weak learners.

#### Light GBM:
- Light GBM is a gradient boosting framework that is designed for speed and efficiency.
- It uses a histogram-based algorithm to find the best split point for each feature, which allows for faster training and lower memory usage.
- Light GBM supports parallel and distributed training and is suitable for large-scale datasets.

#### CatBoost:
- CatBoost is a gradient boosting library developed by Yandex that is designed to handle categorical features seamlessly.
- It automatically handles categorical variables by encoding them using various techniques and improves prediction accuracy without extensive preprocessing.
- CatBoost also supports GPU acceleration and offers robust handling of missing values.

#### Naive Bayes Model:
- Naive Bayes is a probabilistic classifier based on Bayes' theorem with the "naive" assumption of feature independence.
- Despite its simplicity, it often performs well in practice, especially for text classification and document categorization tasks.
- Naive Bayes models are efficient and scalable, making them suitable for large datasets.

#### Voting Classifier:
- The Voting Classifier is an ensemble method that combines the predictions of multiple individual classifiers (e.g., decision trees, logistic regression, SVM) by majority voting (for classification) or averaging (for regression).
- It can improve predictive performance by leveraging the strengths of different algorithms and reducing overfitting.


#### SVM (Support Vector Machine):
- SVM is a powerful supervised learning algorithm used for classification, regression, and outlier detection tasks.
- It works by finding the optimal hyperplane that separates the data points of different classes in the feature space with the maximum margin.
- SVM can handle linear and non-linear decision boundaries using kernel functions, making it versatile for various applications.
- Train Score: [Your train score here]
- Test Score: [Your test score here]

  ### Model Predictions

| Model               | Train Score | Test Score |
|---------------------|-------------|------------|
| KNN                 | 0.987751    | 0.982403   |
| Logistic Regression | 0.925768    | 0.931993   |
| Decision Tree       | 0.998979    | 0.994708   |
| Random Forest       | 0.99983     | 0.996957   |
| GBM                 | 0.994613    | 0.993517   |
| Adaboost            | 0.981683    | 0.984917   |
| Light GBM           | 1           | 0.997221   |
| CatBoost            | 0.998639    | 0.997089   |
| Naive Bayes Model   | 0.894976    | 0.903149   |
| Voting              | 1           | 0.997221   |

