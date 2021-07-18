[[linear algebra]]

1) $\vec{0}$ is always a solution. $A(\vec{0}\in\mathbb{R}^n)=0\vec{a_1}+0\vec{a_2}+\cdots+0\vec{a_n}=(\vec{0}\in\mathbb{R}^m)$
2) If I have two homogeneous solutions, then their sum will also be homogeneous.
	- $A\vec{x_1}=A\vec{x_2}=\vec{0}$
	- $A(\vec{x_1}+\vec{x_2})=A\vec{x_1}+A\vec{x_2}=\vec{0}$
3) Every solution to $A\vec{x}=\vec{b}$ can be written as the sum of a homogeneous solution and a particular solution:
	- Say you have $A\vec{x_p}=\vec{b},A\vec{x}=\vec{b}$ where $x_p$ is a particular solution and $x$ is any solution.
	- $A(\vec{x}-\vec{x_p})=A\vec{x}-A\vec{x_p}=\vec{b}-\vec{b}=\vec{0}$
	- In other words, $\vec{x}-\vec{x_p}=\vec{x_h}$

Therefore, if you have found a homogeneous solution and just any one particular solution, then you can find all particular solutions.