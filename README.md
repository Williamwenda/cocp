Learning convex optimization control policies
=============================================

This repository accompanies the paper [Learning convex optimization control policies](http://web.stanford.edu/~boyd/papers/pdf/learning_cocps.pdf). It contains the source code for the examples therein as IPython notebooks.

Our examples make use the Python package
[cvxpylayers](https://github.com/cvxgrp/cvxpylayers) to differentiate through
convex optimization problems.

## Abstract
Many control policies used in various applications determine the input or
action by solving a convex optimization problem that depends on the current
state and some parameters. These types of control policies are tuned by varying
the parameters in the optimization problem, such as the linear quadratic
regulator weights, to obtain good performance, judged by application-specific
metrics. Our paper introduces a method to automate this process, by adjusting
the parameters using an approximate gradient of the performance metric with
respect to the parameters. Our procedure relies on recently developed methods
that can efficiently evaluate the derivative of the solution of a convex
optimization problem with respect to its parameters.

## Citing
```
@article{agrawal2019cocp,
    author       = {Agrawal, Akshay and Barratt, Shane and Boyd, Stephen and Stellato, Bartolomeo},
    title        = {Learning Convex Optimization Control Policies},
    journal      = {arXiv},
    archivePrefix = {arXiv},
    eprint = {1912.09529},
    primaryClass = {math.OC},
    year    = {2019},
}
```
