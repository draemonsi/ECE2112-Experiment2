# Programming-Assignment-2

Experiment 2

Numerical Python (NUMPY)

Intended Learning Outcomes:
1. To identify the codes and functions incorporated in the Numpy library
2. To be able to apply and use the different codes and functions in creating a Python program using a
Numpy library

NORMALIZATION PROBLEM: Normalization is one of the most basic preprocessing techniques in
data analytics. This involves centering and scaling process. Centering means subtracting the data from the
mean and scaling means dividing with its standard deviation. Mathematically, normalization can be
expressed as:
𝑍 = (𝑋 − 𝑥̅) / 𝜎
In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and
.std() calls.
In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized
ndarray as X_normalized.npy

DIVISIBLE BY 3 PROBLEM: Create the following 10 x 10 ndarray.
𝐴 =
[
1 4 ⋯ 81 100
⋮ ⋮ ⋱ ⋮ ⋮
⋮ ⋮ ⋱ ⋮ ⋮
⋮ ⋮ ⋱ ⋮ ⋮
8281 8464 ⋯ 9801 10000]
which are the squares of the first 100 positive integers.
From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy
