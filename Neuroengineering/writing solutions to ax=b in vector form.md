[[linear algebra]]
- 
- Say you have $A\vec{x}=\vec{b}$
- Reduce it to row echelon form:$\Rightarrow\begin{pmatrix}1&0&2&0&\vdots&0\\0&1&0&1&\vdots&1\\0&0&0&0&\vdots&0\end{pmatrix}$
- Take the rows without leading 1s and set them to a variable, e.g. $x_3=s$ and $x_4=t$
- Which makes $x_2=1-t$ and $x_1=-2s$
- $\Rightarrow\vec{x}=\begin{pmatrix}x_1\\x_2\\x_3\\x_4\end{pmatrix}=\begin{pmatrix}0\\1\\0\\0\end{pmatrix}+s\begin{pmatrix}-2\\0\\1\\0\end{pmatrix}+t\begin{pmatrix}0\\-1\\0\\1\end{pmatrix}$
- And so we have two $\infty$-families of solutions