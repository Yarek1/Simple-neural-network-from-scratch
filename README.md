# Simple-neural-network-from-scratch

Most introductory texts to Neural Networks brings up brain analogies when describing them. 
With delving into brain analogies, we can imagine our brain like a lot of neurons, connected with each other.
In this case we have simple matrix and we want to "learn" our neural network predict output given by vector.

Neural Networks consist of the following components:

-An input layer

-An  hidden layers

-An output layer

-A set of weights and biases between each layer, W and b

-A activation function - in this model Sigmoid activation function.

Of course, the right values for the weights and biases determines the strength of the forecasts. 
Updating the weights and biases from the input data is known as training the Neural Network.
Each iteration of the training process rely on:

-Computing the predicted output ŷ. We call this process as a feedforward

-Calculating derivatives with respect chain rule

-Updating the weights and biases. We call this process as a backpropagation

For a deeper understanding of the application of calculus and the chain rule in backpropagation, I recommend video by 3Blue1Brown:
https://www.youtube.com/watch?v=tIeHLnjs5U8

