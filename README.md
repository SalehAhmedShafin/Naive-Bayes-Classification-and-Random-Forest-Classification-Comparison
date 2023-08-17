# Naive-Bayes-Classification-and-Random-Forest-Classification-Comparison

Naive Bayes Classification:<br>
Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem, which assumes that the features are conditionally independent given the class. It's particularly useful for text classification and other problems where the "naive" assumption of independence holds.

Random Forest Classification:<br>
Random Forest is an ensemble learning algorithm that constructs multiple decision trees during training and outputs the mode of the classes (classification) of the individual trees. It helps reduce overfitting and improves generalization.

Dataset: HeartDisease.csv

Implementation Steps:
1. Import important libraries like pandas, NumPy, scikit-learn.
2. Divide dataset for input and target
3. Using Kfold to divide data frame.
4. Scale data using StandardScaler
5. Run models using scikit-learn library
6. Calculate accuracy, precision, recall and f1 for all flods.
7. Calculate mean accuracy, precision, recall and f1
8. We have used different plots to show difference between models’ performances.
