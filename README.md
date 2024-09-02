# EXPERIMENT 2 - Numerical Python (NumPy)
This repository contains Python codes for solving the given programming problems for this experiment. Full details of each solutions using Python are included in this repository.

# 1. NORMALIZATION PROBLEM 
Library used: numpy as np 

Description: It is a Python library used for working arrays. Type "import numpy as np" to activate the NumPy library. 

Function: np.random.random((5, 5)) 

Description: This function is used to generate a 5x5 array of random numbers between 0 - 1. 

Funtion: X.mean and X.std 

Description: This function is used to compute for the mean and standard deviation of the given array. 

Function: X_normalized = (X - X_mean) / X_std 

Description: This function is used to normalize the given array. 

Funtion: np.save('X_normalized.npy', X_normalized)

Description: This function saves the normalized array to a file named 'X_normalized.npy'. 

Function : print("Original X:\n", X) and print("Normalized X:\n", X_normalized)

Description: It prints the arrays of the first X and the Normalized X. 
