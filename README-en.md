# vanilla-knn

<!-- [![PyPI version](https://badge.fury.io/py/vanilla-knn.svg)](https://badge.fury.io/py/vanilla-knn) -->

A simple implementation of the k-nearest neighbors (KNN) algorithm without using external libraries.

## Installation

You can install `vanilla-knn` using pip:

```bash
pip install vanilla-knn
```

## Usage

```bash
from vanilla_knn.knn import k_neighbors_classifier

# Create a KNN model
modelo = k_neighbors_classifier(n_neighbors=3)

# Train the model
X_train = [...]  # Your training data
y_train = [...]  # Your training labels
modelo.fit(X_train, y_train)

# Make predictions
X_test = [...]  # Your test data
y_pred = modelo.predict(X_test)

# Print the predictions
print("Previsões:", y_pred)
```

## Contributions

If you want to contribute to the development of this project, feel free to send pull requests or report issues.