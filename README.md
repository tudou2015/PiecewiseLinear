A collection of scripts used to check whether a pair of step functions (f, g), where f : U -> IR and g : U -> IR^n (the function and derivative information, respectively) are consistent, i.e. if there exists a third map 'h' that is approximated by the first component of the pair ('f') and whose derivative is approximated by the second component of the pair ('g'). Furthermore, if such a map exists, the program returns the least and greatest such maps, that have the added property of being piece-wise linear.

Dependencies:

The following libraries need to be installed:

* CVXOPT: http://cvxopt.org
* SYMPY:  http://www.sympy.org/en/index.html
* NUMPY:  http://www.numpy.org
