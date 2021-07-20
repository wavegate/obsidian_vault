# Particular and general solution
Consider the system of equations $\begin{bmatrix}1&0&8&-4\\0&1&2&12\end{bmatrix}\begin{bmatrix}x_1\\x_2\\x_3\\x_4\end{bmatrix}=\begin{bmatrix}42\\8\end{bmatrix}$
Because it is in [[RREF]], a solution can immediately be found by taking 42 times the first column and 8 times the second column
Therefore, a solution is $\begin{bmatrix}42\\8\\0\\0\end{bmatrix}$
This solution is called a [[particular solution]] or a [[special solution]]
However, this is not the only solution
To capture all the other solutions, generate 0 in a non-trivial way using teh columns of the matrix
Express the third column using the first two columns: $\begin{bmatrix}8\\2\end{bmatrix}=8\begin{bmatrix}1\\0\end{bmatrix}+2\begin{bmatrix}0\\1\end{bmatrix}$
Which means $c_3=8c_1+2c_2$
So $0=8c_1+2c_2-1c_3+0c_4$ which gives us one infinite set of solutions (8,2,-1,0) (multiplying this by a scalar still leads to 0)
You can do the same for the fourth column to get (-4,12,0,-1)
Putting everything together, you obtain all solutions of the equation system, called the [[general solution]]
$\begin{bmatrix}42\\8\\0\\0\end{bmatrix}+\lambda_1\begin{bmatrix}8\\2\\-1\\0\end{bmatrix}+\lambda_2\begin{bmatrix}-4\\12\\0\\-1\end{bmatrix}$

The general approach involves the three steps:
