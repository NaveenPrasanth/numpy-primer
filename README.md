# numpy-primer

## SET 01

1. Find indices of non-zero elements from [1,2,0,0,4,0]
1. Import the numpy package under the name ``np`` (★☆☆) 
1. Print the numpy version and the configuration (★☆☆) 
1. Create a null vector of size 10 (★☆☆) 
1. How to get the documentation of the numpy add function from the command line ? (★☆☆) 
1. Create a null vector of size 10 but the fifth value which is 1 (★☆☆) 
1. Create a vector with values ranging from 10 to 49 (★☆☆) 
1. Reverse a vector (first element becomes last) (★☆☆) 
1. Create a 3x3 matrix with values ranging from 0 to 8 (★☆☆) 
1. Find indices of non-zero elements from \[1,2,0,0,4,0\] 1(★☆☆) 
1. Create a 3x3 identity matrix (★☆☆) 
1. Create a 3x3x3 array with random values (★☆☆) 
1. Create a 10x10 array with random values and find the minimum and maximum values (★☆☆) 
1. Create a random vector of size 30 and find the mean value  (★☆☆) 
1. Create a 2d array with 1 on the border and 0 inside  (★☆☆) 
1. What is the result of the following expression ? (★☆☆)
1. Create a 5x5 matrix with values 1,2,3,4 just below the diagonal (★☆☆) 
1. Create a 8x8 matrix and fill it with a checkerboard pattern (★☆☆) 
1. Consider a (6,7,8) shape array, what is the index (x,y,z) of the 100th element ?
1. Create a checkerboard 8x8 matrix using the tile function (★☆☆) 
1. Normalize a 5x5 random matrix (★☆☆) 
1. Multiply a 5x3 matrix by a 3x2 matrix (real matrix product) (★☆☆) 
1. Given a 1D array, negate all elements which are between 3 and 8, in place.  (★☆☆)
1. Create a 5x5 matrix with row values ranging from 0 to 4 (★★☆) 
1. Create a vector of size 10 with values ranging from 0 to 1, both excluded (★★☆) 
1. Create a random vector of size 10 and sort it (★★☆) 
1. How to sum a small array faster than np.sum ? (★★☆) 
1. Consider two random array A anb B, check if they are equal  (★★☆) 
1. Make an array immutable (read-only) (★★☆) 
1. Create random vector of size 10 and replace the maximum value by 0 (★★☆) 
1. Create a structured array with ``x`` and ``y`` coordinates covering the
1. Given two arrays, X and Y, construct the Cauchy matrix C (Cij = 1/(xi - yj))
1. Print the minimum and maximum representable value for each numpy scalar type (★★☆) 
1. How to print all the values of an array ?  (★★☆)
1. How to find the closest value (to a given scalar) in an array ?  (★★☆)
1. Create a structured array representing a position (x,y) and a color (r,g,b) (★★☆)
1. How to convert a float (32 bits) array into an integer (32 bits) in place ?
1. What is the equivalent of `enumerate` for numpy arrays ? (★★☆)
1. Generate a generic 2D Gaussian-like array (★★☆) 
1. How to randomly place p elements in a 2D array ? (★★☆)
1. Subtract the mean of each row of a matrix (★★☆) 
1. How to I sort an array by the nth column ? (★★☆) 
1. How to tell if a given 2D array has null columns ? (★★☆) 
1. Find the nearest value from a given value in an array (★★☆) 
1. How to get the diagonal of a dot product ? (★★★) 
1. How to swap two rows of an array ? (★★★) 
1. How to compute averages using a sliding window over an array ? (★★★) 
1. How to negate a boolean, or to change the sign of a float inplace ? (★★★) 
1. Compute a matrix rank (★★★)
1. How to find the most frequent value in an array ?
1. Extract all the contiguous 3x3 blocks from a random 10x10 matrix (★★★) 
1. Create a 2D array subclass such that Z[i,j] == Z[j,i] (★★★) 
1. Consider a set of p matrices wich shape (n,n) and a set of p vectors with shape (n,1).
1. Consider a 16x16 array, how to get the block-sum (block size is 4x4) ? (★★★) 
1. How to implement the Game of Life using numpy arrays ? (★★★) 
1. How to get the n largest values of an array (★★★)
1. How to create a record array from a regular array ? (★★★) 
1. Considering a 10x3 matrix, extract rows with unequal values (e.g. [2,2,3]) (★★★) 
1. Convert a vector of ints into a matrix binary representation (★★★) 
1. Given a two dimensional array, how to extract unique rows ? (★★★) 
 

## SET 02

1. Import the numpy package under the name `np`
2. Print the Julia version
3. Create a null vector of size 10
4. Create a null vector of size 10 and set the fifth value to 1
5. Create a vector with values ranging from 10 to 99
6. Create a 3x3 matrix with values ranging from 0 to 8
7. Find indices of non-zero elements from [1,2,0,0,4,0]
8. Create a 3x3 identity matrix
9. Create a 5x5 matrix with values 1,2,3,4 just below the diagonal
10. Create a 10x10x10 array with random values
 

1. Create a 8x8 matrix and fill it with a checkerboard pattern
2. Create a 10x10 array with random values and find the minimum and maximum values
3. Create a checkerboard 8x8 matrix using the tile function
4. Normalize a 5x5 random matrix (between 0 and 1)
5. Multiply a 5x3 matrix by a 3x2 matrix (real matrix product)
6. Create a 10x10 matrix with row values ranging from 0 to 9
7. Create a vector of size 1000 with values ranging from 0 to 1, both excluded
8. Create a random vector of size 100 and sort it
9. Consider two random matrices A anb B, check if they are equal.
10. Create a random vector of size 1000 and find the mean value

1. Make an array immutable (read-only)
2. Consider a random 10x2 matrix representing Cartesian coordinates, convert them to polar coordinates
3. Create random vector of size 100 and replace the maximum value by 0
4. Create a structured array with x and y coordinates covering the [0,1]x[0,1] area.
5. Print the minimum and maximum representable value for each Julia scalar type
6. Create a structured array representing a position (x,y) and a color (r,g,b)
7. Consider a random vector with shape (100,2) representing coordinates, find point by point distances
8. Generate a generic 2D Gaussian-like array
9. Consider the vector [1, 2, 3, 4, 5]. How to build a new vector with 3 consecutive zeros interleaved between each value?
10. Find the nearest value from a given value in an array


2. Consider a generator function that generates 10 integers and use it to build an array
3. Consider a given vector, how to add 1 to each element indexed by a second vector (be careful with repeated indices)?
4. How to accumulate elements of a vector (X) to an array (F) based on an index list (I)?
5. Considering a (w,h,3) image of (dtype=ubyte), compute the number of unique colors
6. Considering a four dimensional array, how to get sum over the last two axis at once?
7. Considering a one-dimensional vector D, how to compute means of subsets of D using a vector S of same size describing subset indices?

1. Consider a one-dimensional array Z, build a two-dimensional array whose first row is (Z[0],Z[1],Z[2]) and each subsequent row is shifted by 1 (last row should be (Z[-3],Z[-2],Z[-1])
2. Consider a set of 100 triplets describing 100 triangles (with shared vertices), find the set of unique line segments composing all the triangles.
3. Given an array C that is a bincount, how to produce an array A such that np.bincount(A) == C?
4. How to compute averages using a sliding window over an array?

1. Considering a 100x3 matrix, extract rows with unequal values (e.g. [2,2,3])
2. Convert a vector of ints into a matrix binary representation.

1. Consider an arbitrary array, write a function that extracts a subpart with a fixed shape and centered on a given element (pad with a fill value when necessary)

1. Consider two arrays A and B of shape (8,3) and (2,2). How to find rows of A that contain elements of each row of B regardless of the order of the elements in B?
2. Extract all the contiguous 3x3 blocks from a random 10x10 matrix.
3. Create a 2D array subclass such that Z[i,j] == Z[j,i]
4. Consider a set of p matrices with shape (n,n) and a set of p vectors with shape (n,1). How to compute the sum of the p matrix products at once? (result has shape (n,1))

1. Given a two dimensional array, how to extract unique rows?
