# Creating a Basic Neural Network in Keras

March 21, 2020

## Brief Introduction to Neural Networks

### Neural Network Architecture

### Neural Network Mathematics

### Loss Functions and Optimizers

 

### Keras

Keras is a easy to use front-end code for the machine learning library Tensorflow.

## Practice Dataset

Neural networks can be used to many different types of datasets, but since the type of dataset is not important in this tutorial a very simple dataset will suffice for the purposes of testing the neural network.  This code will test a neural network's ability to approximate the function `f(x) = sin(x)`.

## Code

``` python
# For matrices and calculations
import numpy as np
# For graphing
import matplotlib.pyplot as plt
# For machine learning (backend for keras)
import tensorflow as tf
# User-friendly machine learning library
import keras
# Different methods from Keras needed to create an MLP and an RNN
# Creates an input layer to a neural network
from keras.layers import Input
# Creates a Model, which holds a neural network
from keras.models import Model, Sequential 
# Creates hidden layers 
from keras.layers.core import Dense
```

``` python
def nn (input_dim, hidden_neurons, output_dim):
    # define the keras model
    model = Sequential()
    # Add the first hidden layer as well as an input layer of the correct size
    model.add(Dense(hidden_neurons, input_dim=input_dim, activation='relu'))
    # Add the second hidden layer
    model.add(Dense(hidden_neurons, activation='relu'))
    # Add an output layer
    model.add(Dense(output_dim, activation='relu'))
    # Compile the keras model with a loss function and optimizer
    model.compile(loss='mean_squared_error', optimizer='adam')
    return model
```

``` python
X_train = np.arange (-1, 1, 0.1)
Y_train = np.sin (X_train)
```

``` python
X_test = np.arange (-1, 1, 0.01)
Y_test = np.sin (X_train)
```

``` python
nn_sin = nn(1, 500, 1)

nn_sin.fit(X_train, Y_train, epochs=250, verbose = True)
```

``` python
nn_sin_prediction = nn_sin.predict (X_test)
```

``` python
plt.plot (X_test, Y_test, linewidth = 4, label = 'actual')
plt.plot (X_test, nn_sin_prediction, '--', linewidth = 4, label = 'predicted')
plt.legend ()
plt.show ()
```


