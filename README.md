# How-Gradient-Discent-works-in-Linear-Regression-
### what is gradient discent ? 
* It is an optimization algorithm to find the minimum of a function. We start with a random point on the function and move in the negative direction of the gradient of the function to reach the local/global minima. 
### how its work ?
* Its works by starting with random values for each coefficient. The sum of squared errors are calculated for each pair of input and output variables.

* A learning rate is used for each pair of input and output values. It is a scalar factor and coefficients are updated in direction towards minimizing error. The process is repeated until a minimum sum squared error is achieved or no further improvement is possible.

* When using this method, learning rate alpha determines the size of improvement step to take on each iteration of procedure. In practise, Gradient Descent is useful when there is a large dataset either in number of rows or number of columns.

* In short ,it is a minimization algorithm meant for minimizing a given activation function.
