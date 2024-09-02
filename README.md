# EXPERIMENT 2 - Numerical Python (NumPy)
This repository contains Python codes for solving the given programming problems for this experiment. Full details of each solution using Python are included in this repository.

# 1. NORMALIZATION PROBLEM 
Library: numpy as np 

Description: It is a Python Library used for working arrays. Type "import numpy as np" to activate the NumPy library. 

Function: np.random.random((5, 5)) 

Description: This function generates a 5x5 array of random numbers between 0 - 1. 

Function: X.mean and X.std 

Description: This function is used to compute the mean and standard deviation of the given array. 

Function: X_normalized = (X - X_mean) / X_std 

Description: This function is used to normalize the given array. 

Funtion: np.save('X_normalized.npy', X_normalized)

Description: This function saves the normalized array to a file named 'X_normalized.npy'. 

Function : print("Original X:\n", X) and print("Normalized X:\n", X_normalized)

Description: It prints the arrays of the first X and the Normalized X. 

### Running this script will produce the file X_normalized.npy containing the normalized data.

# 2. DIVISIBLE BY 3 PROBLEM
Library: numpy as np 

Function: A = np.arange(1, 101).reshape(10, 10) ** 2

Description: This function generates an array with numbers from 1-100, making it a 10x10 array with the '.reshape(10, 10)' function and squaring the elements with '** 2' to produce the array that is asked with the given problem. 

Function: div_by_3 = A[A % 3 == 0]

Description: This function determines the divisible elements by 3 with the given array. It generates a boolean mask that, for elements divisible by 3, is 'True.' An array of those elements is obtained by applying this mask to 'A.'

Function: np.save('div_by_3.npy', div_by_3) 

Description: This function saves the array of elements divisible by 3 to a file named 'div_by_3.npy'.

### Running this script will produce the file div_by_3.npy containing the elements of the array that are divisible by 3.


