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