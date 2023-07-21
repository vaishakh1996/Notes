---
# --- Learn more about "How to use tags": https://forum.obsidian.md/t/how-to-use-tags/
aliases:
lead: Lead paragraph goes here
visual: "![[image.jpg]]"
# --- Install plugin: https://github.com/blacksmithgu/obsidian-dataview
created: 21-07-2023, 03:35
modified: 21-07-2023, 03:35
# --- Install plugin: https://github.com/beaussan/update-time-on-edit-obsidian
template-type: Note
template-version: "1.7"
# --- Find latest updates: https://github.com/groepl/Obsidian-Templates
---

# Numpy
tags: #python #machine_learning

<!-- Main content of my thoughts really -->

> [!Note]
>1. Numpy => Numerical Python
>	compared : List and tuples
>		- faster
>		- more operations
>
>[[modules or libraries]] : predefined  collection of [[functions]] and [[classes]]

## Creating a numpy array 
` import numpy as np

### 1D 
`np_arr = np.array([1, 2, 3]) 

### 2D
`np_arr = np.array([(1, 2, 3)], [4, 5, 6])

### Defining dtype
`np_arr = np.array([1, 2, 3], dtype = float)

## Initial place holders 
Initial values in a array

### Zeros
`arr_0 = np.zeros((2,3)) # ((shape))

### Ones
`arr_1 = np.ones((2,3))

### Particular values
`z = np.full((5,4), 5) # 5*4 array of all 5

### Identity matrix
`arr_eye = np.eye(4) # 4 by 4 identity matrix

### Random values
`arr_rand = np.random.rand((3,4)) # 3 by 4 array with values b/w 0 and 1

#### random int values
`arr_rand_int = np.randint(30,60,(5,3)) # 5*3 matris with random int values between 30 and 60

### Equally spaced : no of values, o/p is a list
`arr_lin = np.linspace(10,30, 6)

#### random equally stepped :skip values, o/p is a list
`arr_step = np.array(20,40,2) # skip value of 2 1D array

## List -> Numpy array
`arr_1 = np.asarray(list_1)

## Analyzing numpy array
1. arr.shape - o/p shape of the array
2. arr.dim : dimension of arr , o/p is an int
3. arr.size : no of elements in the array
4. arr.dtype : data type of elements in the array

## Mathematical operation

### Element wise 
1. addiition : arr_1 + arr_2 or np.add(arr_1, arr_2)
2. np.sub()
3. np.multiply()
4. np.division()

## Array manipulation
 1. Transpose : arr_1.T or np.transpose(arr_1)
 2. Reshaping : arr_1.reshape(2,3)
		 New size should be same as old size 
		 (2, ) auto fills columns 



---
## Questions
<!-- What remains for you to consider? --> 
- 

## Terms
<!-- Links to definition pages -->
- 

## References
<!-- Links to pages not referenced in the content -->
- 