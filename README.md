# TSP(Traveling Salesman Problem) Solving with Simulated Annealing 

## Synopsis

In this exercise, I implemented the simulated annealing algorithm in a Jupyter notebook and used it to solve the Traveling Salesman Problem (TSP) between US state capitals. 

## Instructions

You need to setup the [Anaconda](https://www.continuum.io/downloads) environment.

## Start Guide

To launch the notebook, run the following command from a terminal with anaconda3 installed and on the application path:

    jupyter notebook AIND-Simulated_Annealing.ipynb

## Algorithm

You must complete the required functions in the 'solution.py' file (copy in code from the classroom where indicated, and add or extend with new code as described below). The `test_solution.py` file includes a few unit tests for local testing (See the unittest module for information on getting started.), but the primary mechanism for testing your code is the Udacity Project Assistant command line utility described in the next section.

1. Add the two new diagonal units to the `unitlist` at the top of solution.py. Re-run the local tests with `python -m unittest` to confirm your solution. 

1. Copy your code from the classroom for the `eliminate()`, `only_choice()`, `reduce_puzzle()`, and `search()` into the corresponding functions in the `solution.py` file.

1. Implement the `naked_twins()` function, and update `reduce_puzzle()` to call it (along with the other existing strategies). Re-run the local tests with `python -m unittest -v` to confirm your solution.

1. Write your own test cases to further test your code. Re-run the remote tests with `udacity submit` to confirm your solution. If any of the remote test cases fail, use the feedback to write new local test cases that you can use for debugging.





