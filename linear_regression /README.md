<h1> Linear Regression Using Scikit-Learn </h1>

<h2> Overview </h2>
This Python program demonstrates linear regression using the scikit-learn library. It creates a linear regression model, trains it on generated data, and visualizes the results. The program also explores the limitations of linear regression when dealing with non-linear relationships.

<h2> Introduction </h2>
Linear regression is a fundamental statistical method for modeling the relationship between a dependent variable (Y) and one or more independent variables (X). Scikit-learn provides a simple and efficient way to implement linear regression models.

<h2> Linear Regression with Linear Data </h2>
The program starts by generating linear data to fit the model. It creates 150 samples of X values and computes corresponding Y values using a linear equation with some random noise. The chosen model equation is: 
Y
=
16.9
+
0.88
X
Y=16.9+0.88X.

<ul> Model Parameters:
 
<li>Intercept (b): 16.9 </li>
<li> Slope (w): 0.88 </li>
 
</ul>
The linear regression model is trained using the generated data. The program visualizes the original data points (in yellow) and the regression line (in black) obtained from the trained model.

<h2> Limitation of Linear Regression with Non-Linear Data </h2>
The program then explores the limitations of linear regression when the relationship between variables is non-linear. It attempts to fit a cubic function (
X
=
Y
3
Y=X 
3
 ) using linear regression. However, as evident in the plot, linear regression fails to capture the non-linear pattern, leading to a poor fit. The original data points are shown in green, and the predicted values are connected with a black line.

<h2>Conclusion </h2>
This demonstration illustrates the effectiveness of linear regression when dealing with linear relationships between variables. However, it emphasizes the importance of choosing an appropriate model for non-linear relationships, as linear regression may not provide accurate predictions in such cases.

<h2> Usage </h2>
This program serves as a valuable resource for beginners learning about linear regression and its limitations. It provides hands-on experience with implementing linear regression using scikit-learn and offers insights into model visualization.

<h2> Important Note </h2>
Ensure that scikit-learn and Matplotlib libraries are installed to run the program successfully. Experiment with different data distributions and model complexities to gain a deeper understanding of linear regression and its applicability.

<h2> References </h2>
<ul> 
<li> Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., ... & Vanderplas, J. (2011). "Scikit-learn: Machine learning in Python." Journal of machine learning research, 12(Oct), 2825-2830.</li>
</ul>
