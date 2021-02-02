# Gradient-Decent
Optimization is a big part of machine learning. Almost every machine learning algorithm has an optimization algorithm at its core.

(m = no of rows is dataset , n = no of properties on which y depends )
Linear regression assumes linear relation between x and y.
The hypothesis function for linear regression is y = m1.x1 + m2.x2 + m3.x3 + … + mn.xn +b where m1 , m2 , m3 are called the parameters and b is the intercept of the line.
This equation shows that the output variable y is linearly dependent on the features x1 , x2 , x3. 
The more you are dependent on a particular feature, more will be the value of corresponding m for that feature.
We can find out which feature is more important or which feature is more affecting the result by varying the values of m one at a time and see if it is affecting the result, that is , the value of y.
So, here in order to predict the values of y for given features values ( x values) we use this equation. But what we are missing here is the values of parameters (m1 , m2 , m3 , … and b).
So, we will be using our training data (where the values of x and y are already given) to find out values of parameters and later on predict the value of y for a set of new values of x.



Gradient descent is an optimization algorithm used to find the values of parameters (coefficients) of a function (f) that minimizes a cost function (cost).
Gradient descent is best used when the parameters cannot be calculated analytically or when you need an optimized way to calculate those parameters.



Feature Scaling is a data preprocessing technique. 
By preprocessing, we mean the transformations that are applied to the data before it is fed into some algorithm for some processing.
Feature Scaling is a technique where we standardize the range of all independent features of a data-set. It is also called Normalization.
