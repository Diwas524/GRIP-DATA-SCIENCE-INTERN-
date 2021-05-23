# GRIP-DATA-SCIENCE-INTERN-

Supervised means to oversee or direct a certain activity and make sure it is done correctly. In this type of learning the machine learns under guidance. So, at school or teachers guided us and taught us similarly in supervised learning machines learn by feeding them label data and explicitly telling them that this is the input and this is exactly how the output must look. So, the teacher, in this case, is the training data.

Linear Regression
Logistic Regression
Support Vector Machine
Naive Bayes Classifier
Artificial Neural Networks, etc

Regression is the method which measures the average relationship between two or more continuous variables in term of the response variable and feature variables. In other words, regression analysis is to know the nature of the relationship between two or more variables to use it for predicting the most likely value of dependent variables for a given value of independent variables. Linear regression is a mostly used regression algorithm.

<h2>LINEAR REGRESSION</h2>

Linear Regression is a supervised method that tries to find a relation between a continuous set of variables from any given dataset. So, the problem statement that the algorithm tries to solve linearly is to best fit a line/plane/hyperplane (as the dimension goes on increasing) for any given set of data.

This algorithm use statistics on the training data to find the best fit linear or straight-line relationship between the input variables (X) and output variable (y). Simple equation of Linear Regression model can be written as:
                                Y=mX+c ;Here m and c are calculated on training

In the above equation, m is the scale factor or coefficient, c being the bias coefficient, Y is the dependent variable and X is the independent variable. Once the coefficient m and c are known, this equation can be used to predict the output value Y when input X is provided.

Mathematically, coefficients m and c can be calculated as:
                       m = sum((X(i) - mean(X)) * (Y(i) - mean(Y))) / sum( (X(i) - mean(X))^2 ) c = mean(Y) - m * mean(X) 


[Linear Regression From Scratch](https://aihubprojects.com/linear-regression-from-scratch/)
