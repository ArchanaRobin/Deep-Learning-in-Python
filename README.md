## Deep-Learning-in-Python

![img12](https://user-images.githubusercontent.com/84294406/151674828-25d168b2-1f18-4a52-8754-5693b43ea765.png)


## Optimizing a neural network with backward propagation
Making accurate predictions gets harder with multiple points. First of all, at any set of weights, we have many values of the error, corresponding to the many points we make predictions for. We use something called a loss function to aggregate all the errors into a single measure of the model's predictive performance.

a common loss function for regression tasks is mean-squared error. You square each error,and take the average of that as a measure of model quality. The loss function aggregates all of the errors into a single score.

## Loss function
Lower values mean a better model, so our goal is to find the weights giving the lowest value for the loss function. We do this with an algorithm called gradient descent. An analogy may be helpful.

## The need for optimization
Predictions with multiple points
Making accurate predictions gets harder with more points
At any set of weights, there are many values of the error corresponding to the many points we make predictions for
## Loss function
Aggregates errors in predictions from many data points into single number
Measure of model's predictive performance
Lower loss function value means a better model
## Goal: Find the weights that give the lowest value for the loss function
 - Gradient Descent
 - Graduent Descent
 - start at random point
 - Until you are somewhere flat:
 - Find the slop
 - Take a step downhill
 - Calculating model errors
For the exercises in this chapter, you'll continue working with the network to predict transactions for a bank.

What is the error (predicted - actual) for the following network using the ReLU activation function when the input data is [3, 2] and the actual value of the target (what you are trying to predict) is 5? It may be helpful to get out a pen and piece of paper to calculate these values.
