Introduction to NumPy

NumPy is a library that helps us handle large and multidimensional arrays and matrices. It provides a large collection of powerful methods to do multiple operations.

NumPy Arrays
NumPy arrays are n-dimensional arrays containing data of the same type in the form of rows and columns. We can create these arrays in the following way:

Example of creating a numpy array:

import numpy as np
#importing the module numpy and creating a short form as np
arr=np.array([1,2,3,4]) #creating a numpy array
print(f"The array is {arr} and the type is {type(arr)}")


NumPy arrays vs Lists
The following are the reasons for giving preference to the numpy array over lists:
1. Numpy arrays occupy lesser memory
2. They are faster
3. They are also comparatively convenient to use, especially when we deal with multiple dimensions

ways of creating NumPy arrays-:
1. Using arange():
2. Using random():
3. Using ones():
4. Using zeros():
5.  Using linspace():

Operations on Python NumPy Arrays
1. Checking Data type:
2. Finding Dimension:
3. Finding ByteSize:
4. Reshaping:
5. Memory Layout:

Mathematical Functions on NumPy arrays
1. add():
2. subtract():
3. multiply():
4. divide():
5. sqrt():


