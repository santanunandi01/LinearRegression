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
<img src="https://github.com/santanunandi01/LinearRegression/blob/master/Images/xvsy.png" height=350 width=700><br>
</p>

    
6.  Now our task is to find the intercept and coefficient. And the formula is
  <p align="center">
  <img src="/Images/m.PNG" height=100 wodth=300>
  <br>
  <img src="/Images/c.PNG" height=45 wodth=190>
  </p>


7. Now to calculate **m** and **c** using Python we use Least Square Method. And the calculation is
  <p align="center">
  <img src="https://github.com/santanunandi01/LinearRegression/blob/master/Images/logic.PNG" height=350 width=600>
  </p>

8. Now let's check the value of coefficent and intercept of our model.
   <p align="center">
     <img src="https://github.com/santanunandi01/LinearRegression/blob/master/Images/mandc.PNG" height=250 width=600>
   </p>
   
9. Now,  we can predict values using any random inputs.
10. Now, let us, calculate the error of our model. The rule for is
    <p align="center">
     <img src="https://github.com/santanunandi01/LinearRegression/blob/master/Images/error.PNG" height=80 width=250>
    </p>
    
    This formula finds the **Mean square error**. If we want to find **Root Mean Square Error**, we need to make root of the error.\
    Our Root Mean Square Error is 1.3064885238484265.
11. In the final step let find the score of our model.
    <p align="center">
     <img src="https://github.com/santanunandi01/LinearRegression/blob/master/Images/score.PNG" height=180 width=450>
    </p>

**Note: -**
1. The data set we have imported is created by me.
2. The data set is available here.\
     https://www.kaggle.com/santanunandi01/data-for-simple-linear-regression
3. All the images used here is also created by me.
4. If this tutorialis helpful, then follow me @santanunandi01
