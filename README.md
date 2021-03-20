# [Neural Network/ ML] Multi-Layer Convolutional Neural Network
Multilayer Perceptron Learning Method and The Error Back-Propagation Algorithm For The Recognition Of Handwritten Digits.



# Introduction

- The objective of this project is to use the perceptron learning method and
    design an artificial neural network (ANN) to train a system for the
    recognition of handwritten digits (0, 1, ..., 9). Use the three-layer feed-
    forward network architecture (input layer, hidden layer, and output layer)
    with the multilayer perceptron learning method and the error back-
    propagation algorithm for the recognition of handwritten digits (0, 1,...., 9).
    Goal is to design a fully connected network structure of 784 input nodes
    and 10 output nodes.
- Design a fully connected network structure of input layer (784 input nodes),
    hidden layer (number of hidden nodes as 10 , 35, 100, 300, 500 ), and output
    layer (10 output nodes).

# Project methodology, equations and implementations

Python Packages Used: -

- Idx2numpy
- NumPy
- Matplotlib
- Pandas
- Tabulate

Main Task: -

- Select a subset of the MNIST database consisting around 100 00 images of
    handwritten digits (0,...,9) for training the system, and use another 1 000
    images for testing the system. Implement the multi-layer perceptron.
- Plot a learning curve that illustrates the mean square error versus
    iterations.
- Plot the percentage error in testing your handwritten digit recognition
    system as a bar chart.


Sub Tasks: -

- Task #1: Repeat this experiment for different learning rate parameters (at
    least 3 experiments. Start with a large value and gradually decrease to a
    small value).
- Task #2: Repeat Task #1 for different number of hidden nodes (10, 35, 100,
    300, 500).
- Compare your results with the SVM and SLP results.

Methodology and Implementations: -

- First step is to reshape the input images and transpose it for the later use
    and also categorize the input labels and transpose them for the later use as
    done in last project.
- Second step is to get the first 10000 images as training images and
    consecutive 1000 images as a testing set, similarly, take the 10000 labels as
    a training labels and consecutive 1000 labels as the testing labels.
- Start Implementing the neural network with the multi-layer perceptron.
- First step is to initialize weights as first weight has size (Hidden,Input) and
    the second weight has size (output,hidden) with the random generated
    values.
- Implement the for loop with the specific iteration and first do a dot product
    of w1 and training x and then implement the activation function.
- Take the dot product of w2 and activation function and implement
    activation function on them.
- Implement forward and backward propagation.


**References:**

NumPy: - https://numpy.org/

Idx2numpy: - https://pypi.org/project/idx2numpy/

Matplotlib: - https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html

Pandas: - https://pandas.pydata.org/


