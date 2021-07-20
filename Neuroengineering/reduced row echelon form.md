an equation system is in reduced row-echelon form if
- it is in row-echelon form
- every pivot is 1
- the pivot is the only nonzero entry in its column

Take the matrix $\begin{bmatrix}1&3&0&0&3\\0&0&1&0&9\\0&0&0&1&-4\end{bmatrix}$
Look at the non-pivot columns, which you express as a combination of the pivot columns
The second column is 3 times the first column
Therefore, to obtain 0, we need to subtract the second column from three times the first column
Again, to obtain 0, we need to subtract the fifth column from 3 times the first column, 9 times the third column, and -4 times the fourth column, giving our solution $\lambda_1\begin{bmatrix}3\\-1\\0\\0\\0\end{bmatrix}+\lambda_2\begin{bmatrix}3\\0\\9\\-4\\-1\end{bmatrix}$