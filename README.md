# freeCodeCamp-Machine-Learning-with-Python-Certification (TensorFlow)
Complete Summary for the Machine Learning with Python Certification course. Certificate available on freeCodeCamp's site after completion.

## Introduction: Machine Learning Fundamentals
Q: Which statement below is **false**? <br>
A: Neural networks are modeled after the way the human brain works.

## Introduction to TensorFlow
Q: Which of the following is **not** a type of tensor? <br>
A: Flowing

## Core Learning Algorithms
Q: Which type of analysis would be best suited for the following problem?: You have the average temperature in the month of March for the last 100 years. Using this data, you want to predict the average temperature in the month of March 5 years from now. <br>
A: Linear regression

## Core Learning Algorithms: Working with Data
Q: What does the pandas `.head()` function do? <br>
A: By default, shows the first five rows or entries in a data frame.

## Core Learning Algorithms: Training and Testing Data
Q: What is categorical data? <br>
A: Any data that is not numeric.

## Core Learning Algorithms: The Training Process
Q: What are epochs? <br>
A: The number of times the model will see the same data.

## Core Learning Algorithms: Classification
Q: What is classification? <br>
A: The process of separating data points into different classes.

## Core Learning Algorithms: Building the Model
Q: What kind of estimator/model does TensorFlow recommend using for classification? <br>
A: `DNNClassifier`

## Core Learning Algorithms: Clustering
Q: Which of the following steps is **not** part of the K-Means algorithm? <br>
A: Shuffle the K points so they're redistributed randomly.

## Core Learning Algorithms: Hidden Markov Models
Q: What makes a Hidden Markov model different than linear regression or classification? <br>
A: It uses probability distributions to predict future events or states.

## Core Learning Algorithms: Using Probabilities to make Predictions
Q: What TensorFlow module should you import to implement `.HiddenMarkovModel()`? <br>
A: `tensorflow_probability`

## Neural Networks with TensorFlow
Q: A densely connected neural network is one in which...: <br>
A: all the neurons in the current layer are connected to every neuron in the previous layer.

## Neural Networks: Activation Functions
Q: Which activation function squishes values between -1 and 1? <br>
A: Tanh (Hyperbolic Tangent)

## Neural Networks: Optimizers
Q: What is an optimizer function? <br>
A: A function that implements the gradient descent and backpropagation algorithms for you.

## Neural Networks: Creating a Model
Q: Fill in the blanks below to build a sequential model of dense layers:
<br>
'model = __A__.__B__([
    __A__.layers.Flatten(input_shape=(28, 28)),
    __A__.layers.__C__(128, activation='relu'),
    __A__.layers.__C__(10, activation='softmax')
])'
<br>
A: A: `keras` , B: `Sequential` , C: `Dense`
