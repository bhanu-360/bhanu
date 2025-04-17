
import numpy as np

# 1. One-dimensional array sorting
arr_1d = np.array([10, 5, 2, 7, 1])
sorted_1d = np.sort(arr_1d)
print("1D Sorted Array:\n", sorted_1d)
1D Sorted Array:
 [ 1  2  5  7 10]
import numpy as np
arr_2d = np.array([[3, 2, 1],
                   [6, 5, 4]])
sorted_2d = np.sort(arr_2d)  # row-wise by default
print("\n2D Sorted Array (row-wise by default):\n", sorted_2d)
sorted_2d_row = np.sort(arr_2d, axis=1)  # axis=1 for rows
print("\n2D Row-wise Sorted:\n", sorted_2d_row)
2D Sorted Array (row-wise by default):
 [[1 2 3]
 [4 5 6]]

2D Row-wise Sorted:
 [[1 2 3]
 [4 5 6]]
import numpy as np
