## Random Forest — Brief Overview

*Random Forest* is a supervised machine learning algorithm used for both classification and regression tasks. It is an ensemble method that builds multiple decision trees and combines their outputs to improve accuracy and reduce overfitting.

### How It Works
- Constructs multiple decision trees using random subsets of the data (bagging)
- At each split, considers a random subset of features
- Aggregates results:
  - Classification → majority vote
  - Regression → average prediction

### Key Concepts
- *Ensemble Learning*: Combines multiple models to improve performance
- *Bagging (Bootstrap Aggregation)*: Reduces variance by training on random samples
- *Feature Randomness*: Prevents trees from becoming too similar

### Advantages
- High accuracy and robustness
- Handles large datasets and high-dimensional data
- Reduces overfitting compared to a single decision tree
- Works well with both numerical and categorical data

### Limitations
- Less interpretable than a single decision tree
- Can be computationally expensive with many trees
- May require tuning for optimal performance

### Common Use Cases
- Classification problems (e.g., spam detection)
- Regression tasks (e.g., price prediction)
- Feature importance estimation