<h1> Polynomial Regression </h1>
<h2> Overview </h2>
This Python program explores polynomial regression, a type of regression analysis used for modeling the relationship between a dependent variable and one or more independent variables by fitting a polynomial equation to the observed data. The program demonstrates polynomial regression using two different methods: direct calculation and gradient descent. It visualizes the polynomial regression predictions in both 2D and 3D spaces, providing insights into the polynomial regression process.

<h2> Polynomial Regression Using Direct Calculation </h2>
<h3> Key Components </h3>

<ol> 
  
<li>Polynomial Regression Function:</li>

The program defines a function to perform polynomial regression using direct calculation. It calculates the coefficients of the polynomial equation and returns the prediction for given x data.

<li>Visualization:</li>

The program generates a set of samples and applies polynomial regression. It visualizes the original samples and the polynomial regression predictions in a 2D plot.

</ol>
<h3> Insights </h3>

The program demonstrates how polynomial regression captures complex relationships between variables, allowing for nonlinear predictions.
<h2>Polynomial Regression Using Gradient Descent</h2>
<h3>Key Components</h3>

<ol>
<li> Gradient Descent Function:</li>

The program implements a gradient descent function to perform polynomial regression. It updates the coefficients iteratively to minimize the loss function.
<li>Normalization Function:</li>

A normalization function is applied to the features to standardize the input data.
<li> Visualization: </li>

The program generates 2D samples, normalizes the features, applies gradient descent for polynomial regression, and visualizes the predictions in both 2D and 3D spaces.

<h3> Insights </h3>
Gradient descent allows for finding optimal polynomial coefficients iteratively, enabling accurate predictions even for high-degree polynomials.

</ol>

<h2> Usage </h2>
This program is valuable for data scientists and machine learning practitioners interested in understanding and applying polynomial regression techniques. It demonstrates both direct calculation and gradient descent methods, providing a comprehensive view of polynomial regression concepts.

<h2> Important Note </h2>
Care should be taken while selecting the degree of the polynomial, as higher degrees might lead to overfitting the training data.
<h2> References</h2>

<ul>
<li> Hastie, T.; Tibshirani, R.; Friedman, J. (2009). "The Elements of Statistical Learning." Springer.</li>
<li> Bishop, C. M. (2006). "Pattern Recognition and Machine Learning." Springer.</li>
</ul>




