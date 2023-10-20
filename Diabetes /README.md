Diabetes Progression Prediction using Mass Index

Overview


This Python program demonstrates a regression analysis using the Diabetes dataset from scikit-learn. The dataset comprises ten baseline variables, including age, sex, body mass index (bmi), average blood pressure (bp), and six blood serum measurements, for 442 diabetes patients. The goal is to predict a quantitative measure of disease progression one year after baseline based on the mass index feature. The program uses linear regression to create a predictive model and assesses its performance on both training and testing data.

Dataset Description


Number of Instances: 442
Number of Attributes: 10 (numeric predictive values)
Target: Quantitative measure of disease progression one year after baseline (numeric)


Attribute Information:


Age: Age in years
Sex: Binary variable indicating gender
BMI: Body mass index
BP: Average blood pressure
S1-S6: Various blood serum measurements


Code Overview


The code imports necessary libraries including matplotlib.pyplot, numpy, datasets, linear_model, mean_squared_error, and train_test_split. It then loads the Diabetes dataset, focuses on the mass index feature, and splits the data into training and testing sets. Linear regression is applied to create a predictive model, and mean squared error is used to evaluate its performance on both the training and testing data.

Data Visualization


Plot 1: A line chart showing the mass index and blood pressure relationship for all patients.
Plot 2-4: Scatter plots displaying the relationship between mass index, age, sugar level, and blood pressure, respectively.
Regression Analysis
The regression analysis in this program focuses on predicting disease progression using the mass index feature. After splitting the data, a linear regression model is trained using the training set. The program evaluates the model's performance on both the training and testing sets using mean squared error (MSD). The results are visualized in two plots, one for the training set and another for the testing set.

Results and Conclusion


The program successfully applies linear regression to predict diabetes progression based on the mass index feature. The mean squared error provides a measure of the model's accuracy, with lower values indicating better performance. These results are valuable for understanding the relationship between mass index and disease progression, aiding in medical research and patient care.

For more detailed information about the dataset and regression analysis, you can refer to the source URL: Diabetes Dataset

This README provides an overview of the regression analysis performed on the Diabetes dataset, offering insights into disease progression prediction based on the mass index feature. It serves as a valuable resource for researchers, data scientists, and healthcare professionals interested in diabetes-related studies and predictive modeling.
