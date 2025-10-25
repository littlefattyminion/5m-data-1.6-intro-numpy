# Assignment

## Brief

Write the Python codes for the following questions.

## Instructions

Paste the answer as Python in the answer code section below each question.

### Question 1

Given the following numpy array:

```python
arr = np.array([1, 2, 3, 4, 5])
```

Write a Python code to multiply each element in the array by 2.

Answer:

```
arr = np.array([1, 2, 3, 4, 5])
arr1 = arr*2
arr1

```

### Question 2

Given the following 2D numpy array:

```python
import numpy as np
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to select the second row of the array.

Answer:

```
arr2drow = arr2d[:2, :]
arr2drow

```

### Question 3

Create a 2D numpy array of shape (5, 5) filled with the number 1.

Answer:

```
import numpy as np
arrS = np.ones((5, 5), dtype=int)
arrS


```

### Question 4

Given the following 2D numpy array:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to calculate the sum of all the elements in each row.

Answer:

```
import numpy as np
arrA = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
arrSum = np.sum(arrA,axis=1)
arrSum

```

### Question 5

Given the following 2D numpy array:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to calculate the average of all the elements.

Answer:

```
Import numpy as np
arrA = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
arrAvg = np.average(arrA,axis=1)
#or arrAvg = np.mean(arrA,axis=1)
arrAvg

```

## Submission

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.
