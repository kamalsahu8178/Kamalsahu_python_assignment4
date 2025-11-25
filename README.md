Question no 1  Explain the key features of NumPy and highlight the major differences between NumPy arrays and Python lists with appropriate examples.  

1. High-Performance N-dimensional Array Object
2. 2.Integration with Other Libraries and Languages
3. 3.Vectorized Operations


Question no 2  Develop a Python program using NumPy to create one-dimensional and two-dimensional arrays, and display their shape, dimensions, and data
type.  
Python List: Can store elements of different data types (heterogeneous). For example, a list can contain integers, strings, and even other lists.
NumPy Array: Stores elements of a single, uniform data type (homogeneous). All elements in a NumPy array must be of the same type (e.g., all integers, all floats). This homogeneity is key to its performance advantages. 

2. Performance and Efficiency:
Python List: Generally less efficient for numerical operations, especially on large datasets, due to the need to handle various data types and the overhead of Python's object model.
NumPy Array: Significantly faster and more memory-efficient for numerical computations. This is because NumPy arrays store data in contiguous memory blocks and leverage optimized C and Fortran routines for operations, enabling "vectorized" operations that apply to entire arrays at once.

3. Functionality and Operations:
Python List: Provides general-purpose methods for list manipulation (append, insert, remove, sort, etc.). Arithmetic operations are typically applied element-wise using loops.
NumPy Array: Offers a rich set of mathematical functions and operations optimized for array manipulation (e.g., element-wise arithmetic, linear algebra, Fourier transforms, random number generation). It supports advanced indexing and broadcasting, simplifying complex data manipulations without explicit loops.

4. Memory Usage:
Python List: Can be less memory-efficient for large datasets because each element carries overhead for type information and reference counting.
NumPy Array: More memory-efficient for large, homogeneous datasets due to storing data contiguously and eliminating individual element overhead.
