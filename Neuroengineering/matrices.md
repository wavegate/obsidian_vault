compactly represent systems of linear equations
also represent linear functions (linear mappings)

# Definition
With $m, n \in \mathbb{N}$ a real-valued $(m,n)$ matrix $A$ is an $m\cdot n$ tuple of elements $a_{ij},i=1,...,m,j=1,...,n$, which is ordered according to a rectangular scheme consisting of $m$ rows and $n$ columns:
$A = \begin{bmatrix}a_{11}&a_{12}&\cdots&a_{1n}\\a_{21}&a_{22}&\cdots&a_{2n}\\\vdots&\vdots&&\vdots\\a_{m1}&a_{m2}&\cdots&a_{mn}\end{bmatrix},a_{ij}\in\mathbb{R}.$
By convention $(1,n)$-matrices are called [[rows]] and $(m,1)$-matrices are called [[columns]]. These special matrices are also called [[row-column vectors]]

# Matrix addition and multiplication
Multiplication involves dot product
Can only be multiplied if "neighboring" dimensions match
If matrix A is n x k and matrix B is k x m, AB works, but BA doenst work if n is not equal to m; in other words, matrix multiplication is not commutative
Matrix multiplication is NOT element-wise... element-wise multiplication is called [[Hadamard product]]

[[identity matrix]] nxn matrix containing 1 on the diagonal and 0 everywhere else; multiplying matrix by identity matrix gives itself
[[associativity]] (AB)C = A(BC)
[[distributivity]] (A+B)C = AC+BC, A(C+D) = AC+AD

# Inverse and transpose
Let matrix B have the property that AB = $I_n$ = BA. B is called the [[inverse]] of A and is denoted by $A^{-1}$
- Not every matrix possesses an inverse; if one does exist, this is called [[regular invertible nonsingular]]; otherwise it is called [[singular noninvertible]]
- Basically the inverse of a matrix is what you can multiply that matrix with to get the identity matrix
- Example: B is $A^{-1}$:
- $A=\begin{bmatrix}1&2&1\\4&4&5\\6&7&7\end{bmatrix}, B=\begin{bmatrix}-7&-7&6\\2&1&-1\\4&5&-4\end{bmatrix}$

$b_{ij}=a_{ji}$ is the [[transpose]] of A, or $B=A^\top$
- In general $A^\top$ can be obtained by writing the columns of $A$ as the rows of $A^\top$
- Important properties of inverse and transpose:
	- $AA^{-1}=I=A^{-1}A$
	- $(AB)^{-1}=B^{-1}A^{-1}$
	- $(A+B)^{-1}\neq A^{-1}+B^{-1}$
	- $(A^\top)^\top=A$
	- $(A+B)^\top=A^\top+B^\top$
	- $(AB)^\top=B^\top A^\top$

# Symmetric
A matrix is [[symmetric]] if $A=A^\top$
Only (n,n)-matrices can be symmetric
We call (n,n)-matrices [[square matrices]] because they possess the same number of rows and columns
- The sum of symmetric matrices is always symmetric, but their product is generally not symmetric (but always defined)

# Multiplication by a scalar
Demonstrates associativity and 