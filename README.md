# Parameter_Optimization_SVM
## About Parameter Optimization in SVM

Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification and regression analysis. It works by finding a hyperplane that best separates the classes in the input data. SVM is particularly useful for binary classification problems but can be extended to multi-class classification.

Parameter optimization is the process of finding the best hyperparameters for a machine learning algorithm that yields the best performance. In the case of SVM, the hyperparameters to be optimized include C and gamma. C is a regularization parameter that balances the margin maximization and the minimization of classification error. A small value of C creates a wider margin but allows more misclassifications, while a large value of C creates a narrow margin but allows fewer misclassifications. Gamma is a parameter that controls the shape of the decision boundary. A small value of gamma creates a simple decision boundary, while a large value of gamma creates a more complex decision boundary.

To optimize the SVM algorithm, we need to search for the best combination of C and gamma that yields the best accuracy. One common approach is to use grid search, where we define a range of values for each hyperparameter, and the algorithm trains and tests the SVM for all possible combinations of the hyperparameters in the defined range. Another approach is to use randomized search, where the algorithm randomly samples a predefined number of combinations of the hyperparameters in the defined range and returns the best combination.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 10129

Number of Attributes: 16

## Final Result Table

| Sample | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| ------ | -------------| -----------| --------| ------------ |
| 1      | 0.99         | poly       | 2.68    | 3.37         |
| 2      | 0.99         | poly       | 6.41    | 4.33         |
| 3      | 0.99         | poly       | 1.10    | 6.52         |
| 4      | 1.00         | linear     | 2.37    | 7.54         |
| 5      | 0.99         | poly       | 0.79    | 0.81         |
| 6      | 0.99         | poly       | 8.82    | 2.29         |
| 7      | 0.99         | linear     | 2.31    | 3.99         |
| 8      | 0.99         | poly       | 9.81    | 6.80         |
| 9      | 0.99         | poly       | 0.58    | 8.98         |
| 10     | 0.99         | linear     | 4.90    | 9.93         |

## Convergence Graph
![graph]()
