# Handwritten-Digit-recognition

An implementation of multilayer neural network using keras with an accuracy of 98.314% and using tensorflow with an accuracy over 99%.

About MNIST dataset:
The MNIST database (Modified National Institute of Standards and Technology database) of handwritten digits consists of a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. Additionally, the black and white images from NIST were size-normalized and centered to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.

Structure of Neural Network:
A neural network is made up by stacking layers of neurons, and is defined by the weights of connections and biases of neurons. Activations are a result dependent on a certain input.

This structure is known as a feedforward architecture because the connections in the network flow forward from the input layer to the output layer without any feedback loops. In this figure:

The input layer contains the predictors.
The hidden layer contains unobservable nodes, or units. The value of each hidden unit is some function of the predictors; the exact form of the function depends in part upon the network type and in part upon user-controllable specifications.
The output layer contains the responses. Since the history of default is a categorical variable with two categories, it is recoded as two indicator variables. Each output unit is some function of the hidden units. Again, the exact form of the function depends in part on the network type and in part on user-controllable specifications. Small Labelled Neural Network![image](https://github.com/user-attachments/assets/b43fbadc-799a-48ae-b28b-658f5125542c)
