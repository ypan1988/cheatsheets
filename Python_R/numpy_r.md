# N-dimensional Arrays Computation using Numpy (Python) and Base R

To load **Numpy** in **Python**, run `import numpy as np`.

No need to load any package in **R** (only build-in types will be used). 

## 1. Data structures

|    | Numpy   | Base R |
| -- | :-      | :-     |
| 1d | ndarray | Atomic vector |
| 2d | ndarray | Matrix |
| nd | ndarray | Array  |

**Numpy**:
+ Create a 2x3 matrix (ndarray):
  ```
  arr = np.array([[1,2,3],[4,5,6]])

  # Check number of dimensions and shape of arr
  arr.ndim    # 2
  arr.shape   # (2, 3)
  ```
**R**:
1. Create a Atomic vector (1d array):
    ```
    arr1d = c(1,2,3)

    # Check length of arr1d
    length(arr1d)   # [1] 3
    ```
2. Create a Matrix (2d array):
    ```
    # Note that arr2d 
    arr2d = matrix(1:6, nrow=2, ncol=3)

    # Check shape of arr2d
    dim(arr2d)      # [1] 2 3
    ```
3. Create a Array (nd array):
    ```
    arr3d = array(1:12, c(2, 3, 2))

    # Check shape of arr2d
    dim(arr3d)      # [1] 2 3 2
    ```

  
