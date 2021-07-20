central part of [[linear algebra]]

# Example
A company produces products $N_1,...,N_n$ for which resources $R_1,...,R_m$ are required. To produce a unit of product $N_j$, $a_{ij}$ units of resource $R_i$ are needed, where $i=1,...,m$ and $j=1,...,n$.
The objective is to find an optimal production plan, i.e., a plan of how many units $x_j$ of product $N_j$ should be produced if a total of $b_i$ units of resource $R_i$ are available and (ideally) no resources are left over.
If we produce $x_1,...,x_n$ units of the corresponding products, we need a total of $a_{i1}x_1+\cdots+a_{in}x_n$ many units of resource $R_i$. An optimal production plan $(x_i,...,x_n)\in\mathbb{R}^n$, therefore, has to satisfy the following system of equations:
$\begin{matrix}a_{11}x_1+\cdots+a_{1n}x_n=b_1 \\
\vdots\\a_{m1}x_1+\cdots+a_{mn}x_n=b_m\end{matrix}$
where $a_{ij}\in\mathbb{R}$ and $b_i\in\mathbb{R}$.