# distributions

## About

This repository contains code for a sample python package called **distributions**. It will enable users to import it in their python projects and use it to perform operations on various statistical distributions. 

An object oriented approach has been followed, and all distributions are expected to inherit from parent class called `Distribution`, written in `Generaldistribution.py`.

The project follows a [test driven approach](https://engineering.pivotal.io/post/test-driven-development-for-data-science/), with the unit tests written in `test.py`.

This project stems from the AWS Machine Learning Foundations Course over Udacity.


## Current Progress

The following distributions have been covered yet:

* Gaussian Distribution
* Normal Distribution



## File Structure

Here is a description of each file and folder in this project

- `distributions`, which contains the code for the distributions package including `Gaussiandistribution.py` and `Generaldistribution.py` code.
- `setup.py` a file needed for building python packages with pip
- `test.py` unit tests to help you debug your code
- `numbers.txt` and `numbers_binomial.txt` are data files used as part of the unit tests



## Getting Started

Installing the distributions package

> To pip install your distributions package, in the terminal, assuming you are in the root directory of the project, type the following into the command line:
>
> ```
> pip install .
> ```
>
> Note that if you change the code in the distributions folder after pip installing the package, Python will not know about the changes. You'll need to run `pip install --upgrade .` when you make changes to the package files.

Testing your code

> When you're ready to test out your code, run the unit tests by typing:
>
> ```
> python -m unittest test
> ```



## Contribution Guidelines

* Every new distribution should be written in a new file inside the `distributions` folder.
* Every new distribution should preferably inherit from `Distributions` class written in `Generaldistribution.py`.
* The distributions should be imported inside the `__init.py__` file inside the `distributions` folder.
* Each distribution should at least have the `__add__` and `__repr__` magic functions available.
* Unit tests should be written in `test.py` in the root directory.
* Data for unit tests should also be in the root directory.

