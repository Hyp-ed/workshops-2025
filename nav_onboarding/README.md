## Navigation Onboarding

Welcome to navigation!
TODO: Add brief descritpion and simple rust excerises.

## Basic Linear Algebra
Make sure you are familiar with the following concepts:

### Matrix Addition
Matrix addition is performed element-wise. The matrices must have the same dimensions.

$A=\begin{bmatrix}1&2\cr3&4\end{bmatrix} B=\begin{bmatrix}5&6\cr7&8\end{bmatrix}$

$A + B = \begin{bmatrix}1+5 & 2+6 \\ 3+7 & 4+8\end{bmatrix} = \begin{bmatrix}6 & 8 \\ 10 & 12\end{bmatrix}$

### Matrix Multiplication
Matrix multiplication is performed by taking the dot product of the rows of the first matrix with the columns of the second matrix.

$A=\begin{bmatrix}1&2\cr3&4\end{bmatrix} B=\begin{bmatrix}5&6\cr7&8\end{bmatrix}$

$A \cdot B = \begin{bmatrix}1\cdot5+2\cdot7 & 1\cdot6+2\cdot8 \\ 3\cdot5+4\cdot7 & 3\cdot6+4\cdot8\end{bmatrix} = \begin{bmatrix}19 & 22 \\ 43 & 50\end{bmatrix}$

### Matrix Transpose
The transpose of a matrix $A$ is obtained by swapping the rows and columns. It is denoted by $A^T$.

$A=\begin{bmatrix}1&2\cr3&4\end{bmatrix}$
$A^T=\begin{bmatrix}1&3\cr2&4\end{bmatrix}$

### Identity Matrix

The identity matrix is a square matrix with ones on the diagonal and zeros elsewhere. It is denoted by $I$.

$I=\begin{bmatrix}1&0\cr0&1\end{bmatrix}$

### Matrix Inverse

The inverse of a matrix $A$ is denoted by $A^{-1}$. It is the matrix such that $A \cdot A^{-1} = I$, where $I$ is the identity matrix.












