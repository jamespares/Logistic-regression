**Iris Species Classification using Logistic Regression**

This project employs logistic regression to classify different species of Iris flowers based on their sepal and petal measurements.

**Data:**

Iris Dataset: A standard dataset readily available within scikit-learn.
Process:

**Data Import and Exploration:**

Libraries (NumPy, pandas, Matplotlib) are imported.
The Iris dataset is loaded using sklearn.datasets.load_iris().
A preview of the data is provided with data.head().

**Data Preprocessing:**

Features (sepal length, sepal width, petal length, petal width) are selected and stored in X.
Target labels (species) are stored in y.
Features are scaled using preprocessing.scale(X) for improved model fitting.

**Data Splitting:**

Data is divided into training (75%) and testing (25%) sets using train_test_split() for model training and evaluation.

**Model Training:**

A logistic regression model is instantiated using sklearn.linear_model.LogisticRegression().
The model is fit to the training data to learn the relationship between features and species.

**Model Evaluation:**

Accuracy: The model's overall accuracy on the test set indicates its prediction success rate.
Confusion Matrix: Provides insight into correct and incorrect predictions within each species class.
F1 Score, Precision, Recall: Offer detailed performance metrics, especially valuable for imbalanced datasets..
