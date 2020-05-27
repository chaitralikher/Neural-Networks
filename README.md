# Neural-Networks
Using Neural Network to Classify MNIST Data

This is neural network implementation from scratch using NumPy library for computations and ScikitLearn library for measuring the accuracy of the model.Pandas library has been used for converting labels to one-hot encoding and matplotlib has been used for data Visualization and accuracy graphs.

The configuration for the Model is:

Number of Hidden layers: 2

Number of neurons per layer:

Layer 1:128

Layer 2:64

Activation: tanh()

Output Layer Activation: Softmax()

Loss Function: Cross Entropy Loss

Data Split (Train:Test): 80:20

The parameter for activation function, 'act' can be set to 'sigmoid' or as in the code to 'tanh'. Using each of these for one layer also works.

Different hyperparameters can be experimented on for both the activations to find better accuracy.
