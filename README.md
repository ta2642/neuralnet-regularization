# neuralnet-regularization

In this project, we use the LeNet-5 model.

We use the MNIST dataset, which has 10 output classes.

We experiment with batch normalization and drop out.

I compare performance when using no normalization, batch normalization of hidden layers, batch normalization of input and hidden layers, dropout of 0.2 in input layer and 0.5 in hidden layer, and lastly I take a look at when we use both dropout and batch normalization.

The resuls show that batch normaliztion of input and hidden layers led to the best test accuracy of 96%
