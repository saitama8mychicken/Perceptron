# Perceptron
## Single Layer Perceptron

he computation of a single layer perceptron is performed over the calculation of sum of the input vector each with the value multiplied by corresponding element of vector of the weights. The value which is displayed in the output will be the input of an activation function

![img](https://www.tutorialspoint.com/tensorflow/images/single_layer_perceptron.jpg)

In the above two single layer perceptrons have been designed

1 - Single layer perceptron for housing data
      (https://github.com/saitama8mychicken/Perceptron/blob/master/single%20layer%20perceptron.ipynb)
      
2 - Single layer perceptron for mnist data
      (https://github.com/saitama8mychicken/Perceptron/blob/master/mnist%20using%20single%20layer%20perceptron.ipynb)


## Multi Layer Perceptron

![img](https://miro.medium.com/proxy/1*eloYEyFrblGHVZhU345PJw.jpeg)

The multilayer perceptron is the hello world of deep learning: a good place to start when you are learning about deep learning.

A multilayer perceptron (MLP) is a deep, artificial neural network. It is composed of more than one perceptron. They are composed of an input layer to receive the signal, an output layer that makes a decision or prediction about the input, and in between those two, an arbitrary number of hidden layers that are the true computational engine of the MLP. MLPs with one hidden layer are capable of approximating any continuous function.

Multilayer perceptrons are often applied to supervised learning problems3: they train on a set of input-output pairs and learn to model the correlation (or dependencies) between those inputs and outputs. Training involves adjusting the parameters, or the weights and biases, of the model in order to minimize error. Backpropagation is used to make those weigh and bias adjustments relative to the error, and the error itself can be measured in a variety of ways, including by root mean squared error (RMSE).

Feedforward networks such as MLPs are like tennis, or ping pong. They are mainly involved in two motions, a constant back and forth. You can think of this ping pong of guesses and answers as a kind of accelerated science, since each guess is a test of what we think we know, and each response is feedback letting us know how wrong we are.

In the forward pass, the signal flow moves from the input layer through the hidden layers to the output layer, and the decision of the output layer is measured against the ground truth labels.

In the backward pass, using backpropagation and the chain rule of calculus, partial derivatives of the error function w.r.t. the various weights and biases are back-propagated through the MLP. That act of differentiation gives us a gradient, or a landscape of error, along which the parameters may be adjusted as they move the MLP one step closer to the error minimum. This can be done with any gradient-based optimisation algorithm such as stochastic gradient descent. The network keeps playing that game of tennis until the error can go no lower. This state is known as convergence.

Multi layer perceptron has been implemented in the above code as
1 - https://github.com/saitama8mychicken/Perceptron/blob/master/mnist%20using%20mlp.ipynb
