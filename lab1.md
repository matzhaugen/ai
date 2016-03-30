---
layout: page
mathjax: true
---


<!-- Here is a link to the [Python/Numpy Tutorial](http://cs231n.github.io/python-numpy-tutorial/) covered in class.  -->

The goal of this lab is first of all to get familiar with the python and ipython framework. We will do this by going through some mathematical and programmatic questions. By the end of this lab we will understand:

- Python functions
- Python classes with methods.
- Modular programming.
- How to solve a sudoku puzzle.

# Introduction
1. Get Ipython up and running
2. Make a function using __def__ that squares a list of numbers and throws and error if the list contains something that does not have a number. 
3. Given the list `[1,2,3,4,5,6]` do the same thing as in point 2 but with a lambda function.
4. Devise an experiment to figure out whether list indexing is $O(1)$ time. Only an outline of the experiment is needed, no code.

# The Fraction Class
5. Make a Python Class called Fraction. This function will contain an `__init__` function that takes a numerator and a denominator.
6. Implement the `__add__` method.
7. Implement the simple methods 'getNum' and 'getDen' that will return the numerator and denominator of a fraction.
8. Implement the remaining simple arithmetic operators `__sub__`, `__mul__`, and `__truediv__`.
9. Implement the remaining relational operators `__gt__`, `__ge__`, `__lt__`, `__le__`, and `__ne__`.
10. Modify the constructor for the fraction class so that it checks to make sure that the numerator and denominator are both integers. If either is not an integer the constructor should raise an exception.
11. In the definition of fractions we assumed that negative fractions have a negative numerator and a positive denominator. Using a negative denominator would cause some of the relational operators to give incorrect results. In general, this is an unnecessary constraint. Modify the constructor to allow the user to pass a negative denominator so that all of the operators continue to work properly.
12. Implement `__iadd__`.
# 


# Sudoku (For lab 2)
99. Make a function that solves a sudoku puzzle. This is the main question for this lab. 
- [Ref: Peter Norvik's sudoku post](http://norvig.com/sudoku.html)