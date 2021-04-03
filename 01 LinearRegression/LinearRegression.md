# Simple Linear Regression
### What is simple linear regression?
When our output variable is dependent on only one independent variable then it is called simple linear regression. In the given data set y is only dependent on x, so it is a simple regression.
<p align="center">
<img src="https://github.com/santanunandi01/LinearRegression/blob/master/Images/xy1.PNG" width=82 height=115>
</p>

## Steps: -
1. At first we import all the required libraries(pandas, numpy and pyplot).
2. We import our data file using pandas **read_csv** method.
3. Our data set has two columns **x** and **y** as it is a Simple Linear Regression model.
4. In the next step we create our dependent variable **X** and independent variable **y** using pandas **iloc** method.
5. Then we plot our data.
<p align="center">
<img src="https://github.com/santanunandi01/LinearRegression/blob/master/Images/xvsy.png" height=350 width=700>
</p>

As we can see our plot is almost linear so the error of our model will be very less.
6. Now our task is to find the intercept and coefficient. And the formula is
<p align="center">
<img src="/Images/m.PNG" height=100 wodth=300>
<br>
<img src="/Images/c.PNG" height=45 wodth=190>
</p>
7. 
