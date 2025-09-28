# NumPy README

## What is NumPy?

NumPy (Numerical Python) is a Python library for fast mathematical operations on large datasets. It provides the foundation for data science in Python by enabling efficient array computations.

---

## Why Use NumPy?

* **Speed**: Operations are implemented in C, making them much faster than Python lists.
* **Efficiency**: Handles multi-dimensional data easily.
* **Convenience**: Comes with built-in math, statistics, and linear algebra functions.
* **Integration**: Forms the base for Pandas, SciPy, scikit-learn, TensorFlow, PyTorch, and more.

---

## Key Features

1. **N-dimensional Arrays**: Core object for data storage.
2. **Vectorized Operations**: Perform calculations without explicit loops.
3. **Broadcasting**: Apply operations on arrays of different shapes.
4. **Mathematical Functions**: Built-in stats, algebra, and random number generation.
5. **Interoperability**: Works with other scientific libraries.

---

## Common Workflows

```python
import numpy as np

# Create arrays
arr = np.array([1, 2, 3, 4])
mat = np.arange(9).reshape(3,3)

# Basic operations
print(arr.sum(), arr.mean())

# Indexing & slicing
print(arr[1:3])  # [2 3]

# Reshaping
arr2 = np.arange(12)
print(arr2.reshape(3,4))  # reshape into 3x4

# Combining arrays
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
print(np.concatenate([a, b]))  # [1 2 3 4 5 6]

# Stacking
mat1 = np.array([[1, 2], [3, 4]])
mat2 = np.array([[5, 6]])
print(np.vstack([mat1, mat2]))
print(np.hstack([mat1, mat2.T]))

# Random numbers
print(np.random.rand(3))
```

✅ NumPy is the backbone of Python data science. Master it before moving on to Pandas and machine learning.
