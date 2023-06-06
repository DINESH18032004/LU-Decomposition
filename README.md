# LU Decomposition 

## AIM:

To write a program to find the LU Decomposition of a matrix.

## Equipments Required:

1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

Step 1:

Import numpy and scipy from the python library.

Step 2:

Get the input from the user in array format.

Step 3:

Calculate L and U matrix using lu() builtin function.

Step 4: 

Print the L matrix and U matrix.

Step 5:

End the program.

## Program:

(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: DINESH KUMAR R
RegisterNumber: 212222110010
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```

(ii) To find the LU Decomposition of a matrix
'''Program to solve a matrix using LU decomposition.
Developed by: DINESH KUMAR R
RegisterNumber: 212222110010
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

*/
```

## Output:
![lu decomposition]()
![5a maths](https://github.com/DINESH18032004/LU-Decomposition/assets/119477784/2db24f89-a897-42ef-8892-4cfaa11ff7fb)

![5b maths](https://github.com/DINESH18032004/LU-Decomposition/assets/119477784/8a834892-7ca8-477a-bead-c8ca65f6ac6b)

## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

