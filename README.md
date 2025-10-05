### 🧮 NumPy Practice Code
```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])
print("Sum:", np.sum(a))

# numpy_practice.py
# Basic NumPy Practice File

import numpy as np

# 1️⃣ Create arrays
a = np.array([1, 2, 3, 4, 5])
b = np.array([[10, 20, 30], [40, 50, 60]])

print("Array a:", a)
print("Array b:\n", b)

# 2️⃣ Basic operations
print("\nSum of a:", np.sum(a))
print("Mean of a:", np.mean(a))
print("Maximum value in b:", np.max(b))
print("Minimum value in b:", np.min(b))

# 3️⃣ Reshaping and indexing
reshaped_b = b.reshape(3, 2)
print("\nReshaped b (3x2):\n", reshaped_b)
print("Element at row 1, column 2 of b:", b[0, 1])

# 4️⃣ Mathematical operations
c = np.array([5, 10, 15, 20, 25])
print("\nArray c:", c)
print("a + c:", a + c)
print("a * 2:", a * 2)
print("Square roots of c:", np.sqrt(c))

# 5️⃣ Useful functions
print("\nZeros array:", np.zeros((2, 3)))
print("Ones array:", np.ones((3, 2)))
print("Random 2x2 matrix:\n", np.random.rand(2, 2))

# 6️⃣ Matrix operations
x = np.array([[1, 2], [3, 4]])
y = np.array([[5, 6], [7, 8]])
print("\nMatrix x:\n", x)
print("Matrix y:\n", y)
print("Matrix addition:\n", x + y)
print("Matrix multiplication (dot):\n", np.dot(x, y))
print("Transpose of x:\n", x.T)
