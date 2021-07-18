[[linear algebra]]
[[mathematics]]
[[youtube]] https://www.youtube.com/watch?v=rNSRcZ18i_4&t=506s&ab_channel=Dr.TreforBazett
[[trefor bazett]]

# Geometric problem
- Suppose we have a list of vectors $\vec{a_{1}},...,\vec{a_n}$
- Is the span, or linear combinations, of these vectors the entire space $\mathbb{R}^m$?
- In other words, is $\operatorname{span}\{\vec{a_{1}},...,\vec{a_n}\} = \mathbb{R}^m$?
- Note that there are $m$ vectors, but each of these vectors has $n$ components.
- If our vectors are in line with each other, their span does not make up $\mathbb{R}^m$.
- Or, if all vectors are in one plane, then span is just one plane and not the entire 3D space.

# Algebraic problem
- $\begin{bmatrix}a_{11}x_1 & ... & a_{1n}x_n & b_1 \\ ... & ... & ... & ... \\ a_{m1}x_1 & ... & a_{mn}x_n & b_m\end{bmatrix} => A\vec{x} = \vec{b}$
- For every $\vec{b}$, can we solve for $\vec{x}$?

# The Big Theorem, Part 1
- The following are equivalent (TFAE):
	1) The columns of A span $\mathbb{R}^m$
	2) For every $\vec{b}\in\mathbb{R}^m$