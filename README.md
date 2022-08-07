# AIML-LAB
Objective:  To use NumPy python library and perform various Pre-processing operations

Part A
1.	Creating NumPy arrays (10)
a)	Check the version of NumPy and create 1D, 2D arrays. 
b)	Check the data type and dimension of created arrays
c)	Find the size of each element in the arrays. 
d)	Find the number of rows and columns of 2D array.
e)	An array of shape (2, 3) given, reshape the array into (3, 2).
2.	Slicing of arrays (10)
a)	A 1D array is given as [4, 5, 6, 3, 9, 7]. Slice the array to get [6, 3, 9].
b)	A 2D array is given as [[1, 2, 3] [4, 5, 6]]. Slice the array to get [ [1, 2]].
3.	Join and splitting of NumPy Arrays (15)
a)	Concatenate two 1D arrays [4,5,6,7] and [3,4,1].
b)	Perform concatenation of two 2D arrays in row-by-row manner.
c)	Split the array [4, 5, 6, 3, 9,] into 3 sub-arrays.
d)	Split the array the 2D array [[ 1, 2, 3] [ 4, 5, 6],[ 7,  8,  9],[10, 11, 12]] into 3 sub-arrays.
4.	Searching elements in an array (10)
a)	Given an array [1, 2, 3, 4, 5, 4, 4]. Find the index of element 4.
b)	Given a 2d array [[ 1, 2, 3],[ 4, 5, 6],[ 7,  8,  9],[10, 11, 12]]. Find the index of element 5.
c)	Given an array [1, 2, 3, 4, 5, 6, 7, 8], find out the indices of odd elements and even elements.
5.	Sorting of Arrays (10)
a)	Sort the elements of given 1D array [6, 5, 1, 2, 9, 10, 36, 7] in ascending and descending order.
b)	Sort the elements of given 2D array [[5, 3, 7], [8, 10, 6], [40, -2, 7]] in ascending and descending order.
6.	Random number generation in NumPy arrays (15)
a)	Generate a 1-D array containing 6 random integers from 0 to 20.
b)	Generate a 1-D array containing 5 random floats.
c)	Generate a 2-D array with 3 rows, each row containing 5 random integers from 0 to 50.
d)	Generate a 2-D array with 3 rows, each row containing 5 random numbers.
e)	Given a 1-D array [6, 5, 1, 2, 9, 10, 36, 7]. Shuffle the elements of the array randomly.
f)	Given a 2-D array [[ 1, 2, 3] [ 4,  5,  6][ 7,  8,  9] [10, 11, 12]]. Shuffle the elements of the array randomly.

Part B
1.	Go to UCI machine learning repository and download the wine-quality dataset (red and/or white) from the link  https://archive.ics.uci.edu/ml/datasets/Wine%2BQuality (5)
2.	Read the dataset using read_csv() of pandas Lib and store it in variable wine_data (5)
3.	Convert the wine_data into NumPy Array (5)
4.	Check the shape (5)
5.	Slicing the matrix: From the matrix wine_data, create a new variable: (15)
a)	Y, which contains the last column (quality of wine) of XY. Print its shape.
b)	X, all the other columns except last from XY. Print its shape.
6. Compute the following statistical values using NumPy in-built functions wherever possible. (15)
a)	Mean for all columns in X.
b)	Mode of the last column, Y (i.e., quality of wine)
c)	Standard deviation for all columns in X.
