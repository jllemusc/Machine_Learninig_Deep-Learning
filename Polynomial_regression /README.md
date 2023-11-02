Polynomial Regression
Overview
This Python program explores polynomial regression, a type of regression analysis used for modeling the relationship between a dependent variable and one or more independent variables by fitting a polynomial equation to the observed data. The program demonstrates polynomial regression using two different methods: direct calculation and gradient descent. It visualizes the polynomial regression predictions in both 2D and 3D spaces, providing insights into the polynomial regression process.

Polynomial Regression Using Direct Calculation
Key Components
Polynomial Regression Function:

The program defines a function to perform polynomial regression using direct calculation. It calculates the coefficients of the polynomial equation and returns the prediction for given x data.
Visualization:

The program generates a set of samples and applies polynomial regression. It visualizes the original samples and the polynomial regression predictions in a 2D plot.
Insights
The program demonstrates how polynomial regression captures complex relationships between variables, allowing for nonlinear predictions.
Polynomial Regression Using Gradient Descent
Key Components
Gradient Descent Function:

The program implements a gradient descent function to perform polynomial regression. It updates the coefficients iteratively to minimize the loss function.
Normalization Function:

A normalization function is applied to the features to standardize the input data.
Visualization:

The program generates 2D samples, normalizes the features, applies gradient descent for polynomial regression, and visualizes the predictions in both 2D and 3D spaces.
Insights
Gradient descent allows for finding optimal polynomial coefficients iteratively, enabling 
