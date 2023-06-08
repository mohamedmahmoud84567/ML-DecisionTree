# ML-DecisionTree
In this section, we'll use decision trees to fit a given sample dataset.

Before we do that, let's go over the tools required to build this model.

For our decision tree model, we'll be using scikit-learn's Decision Tree Classifier class. This class provides the functions to define and fit the model to your data

>>> from sklearn.tree import DecisionTreeClassifier
>>> model = DecisionTreeClassifier()
>>> model.fit(x_values, y_values)
In the example above, the model variable is a decision tree model that has been fitted to the data x_values and y_values. Fitting the model means finding the best tree that fits the training data. Let's make two predictions using the model's predict() function.
