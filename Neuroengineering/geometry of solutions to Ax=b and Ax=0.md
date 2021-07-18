[[linear algebra]]
# Equation 1
- Take $A\vec{x}=\vec{b}$
- For example, this augmented matrix $\begin{pmatrix}1&2&\vdots&1\\0&0&\vdots&0\end{pmatrix}$
- Take each row without a leading one and convert that to a variable: $x_2=s$ and $x_1=1-2s$
- Convert this into vector form: $\vec{x_p}=\begin{pmatrix}1\\0\end{pmatrix}+s\begin{pmatrix}-2\\1\end{pmatrix}$

# Equation 2
- Take $A\vec{x}=\vec{0}$
- For example, this augmented matrix $\begin{pmatrix}1&2&\vdots&0\\0&0&\vdots&0\end{pmatrix}$
- Take each row without a leading one and convert that to a variable: $x_2=s$ and $x_1=-2s$
- Convert this into vector form: $\vec{x_h}=s\begin{pmatrix}-2\\1\end{pmatrix}$
- In other words, the solution to the matrix is 