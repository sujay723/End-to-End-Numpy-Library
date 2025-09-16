# Introduction to NumPy

This Jupyter Notebook provides a hands-on introduction to the fundamental features and operations of the NumPy library in Python.

## Concepts Covered

### Array Creation
* Creating NumPy arrays from other Python structures like lists and sets.
* Using intrinsic array creation functions:
    * `np.zeros()`: Creating arrays filled with zeros.
    * `np.arange()`: Creating arrays with a range of values.
    * `np.linspace()`: Creating arrays with evenly spaced values over a specified interval.
    * `np.empty()` & `np.empty_like()`: Creating uninitialized arrays.
    * `np.identity()`: Creating an identity matrix.

### Array Attributes
* `.shape`: Get the dimensions of the array.
* `.dtype`: Get the data type of the array's elements.
* `.size`: Get the total number of elements.
* `.ndim`: Get the number of dimensions.
* `.nbytes`: Get the total bytes consumed by the array's elements.

### Array Manipulation & Operations
* **Indexing and Slicing**: Accessing and modifying individual array elements.
* `.reshape()`: Changing the shape of an array without changing its data.
* `.ravel()`: Flattening a multi-dimensional array into a 1D array.
* `.sum(axis=...)`: Summing array elements along a specified axis (0 for columns, 1 for rows).
* `.T`: Transposing an array (swapping axes).
* `.flat`: Creating a 1-D iterator over the array.

### Searching & Sorting Functions
* `.argmax()`: Find the index of the maximum value in an array.
* `.argmin()`: Find the index of the minimum value in an array.
* `.argsort()`: Get the indices that would sort the array.
## Created By Sujay Roy
## Requirements

* Python 3.x
* NumPy
* Jupyter Notebook or JupyterLab

You can install the necessary libraries using pip:
```bash
pip install numpy jupyterlab
