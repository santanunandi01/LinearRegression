# Simple Linear Regression
In this tutorial we create our data set using **numpy** package. We do not implement the model step by step,
rather than we import inbuilt LinearRegression model from **sklearn.linear_model**.

## Steps: -
Firstly we import all the required modules. Then we create our independent variable **X** using numpy.
```python
X = np.random.randint(0, 1000, 100)
```
Then we create our dependent or output variable.
```python
y = X*2 + 3
```
So, the value of **X** and **y** are continious and the relation between X and y is 100% linear. So, our model will be 100% efficient.\
In the next step we create the object of our linear model.
```python
lm = LinearRegression()
```
A linear regression model takes two 2D array to fit, but our X and y is 1D array. So, we need to convert X and y to a 2D array.
```python
X = X.reshape(len(X), 1)
```
Now our X has multiple rows and a single column, each row is an 1D array.\
Everything is ready now we need fit our dependent and independent variable to our object.
```python
lm.fit(X, y)
```
Let's find the intercept and coefficenct of our model.
```python
>>> lm.coef_
array([[2.]])
```
```python
>>> lm.intercept_
array([3.])
```
Now we can predict values using our model.
```python
>>> lm.predict([[1032]])
array([[2067.]])
```
### Finding errors
To find the error we import an object **metrics** form **sklearn**.
```python
from sklearn import metrics
metrics.mean_squared_error(y, prediction)
```
 and the error is-\
 `0.0`

### Note: -
1. The method used here is inbulit in **sklearn**. So, we do not need to implement the Regression model step by step. If you want to learn the step by step process 
 <a href= "https://github.com/santanunandi01/LinearRegression/tree/master/01%20LinearRegression" target="_blank">click here.</a>
2. The intercept and coefficient of our data is same for every row, thats why we don't have any error.
