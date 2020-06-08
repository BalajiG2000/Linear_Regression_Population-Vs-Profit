# Linear_Regression_Population-Vs-Profit


I have implemented the following concepts:

Implement the gradient descent algorithm from scratch.


Perform univariate linear regression with Numpy and Python.


Create data visualizations and plots using matplotlib.

Steps followed:
Introduction and Import Libraries: 

Introduction to the data set and the problem overview.

Import essential modules and helper functions from NumPy and Matplotlib

:Load the Data and Libraries 

Visualize the Data

For this dataset,  I made a  scatter plot using Seaborn to visualize the data, since it has only two variables: the profit and population.

Compute the Cost 𝐽(𝜃)

The objective of linear regression is to minimize the cost function J(𝜃).You can think of the cost as the error your model made in estimating a value.

Implement Gradient Descent from scratch in Python

We will adjust the new 𝜃_j to minimize the cost J(𝜃).

One way to do this is to use the batch gradient descent algorithm.

In batch gradient descent, each iteration performs the following update.

With each step of gradient descent, the parameters 𝜃_j come closer to the optimal values that will achieve the lowest cost J(𝜃).

Visualizing the Cost Function J(𝜃)

We can see that the cost function J(𝜃) is bowl-shaped and has a global minimum.

Plotting the Convergence

We will now plot the J values against the number of iterations

Training Data with Univariate Linear Regression Fit

Inference using the optimized 𝜃 values
Now I have used the final values for 𝜃 to make predictions on profits in cities of 40,000 and 83,000 people. 
