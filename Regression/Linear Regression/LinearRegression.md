## REGRESSION
In statistics, linear regression is a linear approach to modeling the relationship between a scalar response (or dependent variable) and one or more explanatory variables (or independent variables). The case of one explanatory variable is called simple linear regression.

For linear regression, we use the mean squared error cost function. It is the average over the various data points (xi, yi) of the squared error between the predicted value y(x) and the target value ytrue.

![Linear Regression Cost funton](https://github.com/asarmohd/mlalgo.github.io/blob/master/Regression/Linear%20Regression/CostFuntion.jpeg)


```
>>> from sklearn import linear_model
>>> reg = linear_model.LinearRegression()
>>> reg.fit([[0, 0], [1, 1], [2, 2]], [0, 1, 2])
LinearRegression()
>>> reg.coef_
array([0.5, 0.5])
```
