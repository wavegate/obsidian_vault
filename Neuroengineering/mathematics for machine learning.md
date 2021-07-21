https://mml-book.github.io/book/mml-book.pdf

two ways to read this book
bottom up:
- building up from concepts from foundational to more advanced
- preferred approach in more technical fields such as mathematics
- reader is at all times able to rely on prevoiusly learned concepts
- many foundational concepts are not particularly interesting by themselves
- lack of motivation means most foundatoinal definitions are quickly forgotten
top-down:
- from practical needs to more basic requirements
- readers know at all times why they need to work on a particular concept
- clear path of required knowledge
- potentially shaky foundations
- have to remember a set of words that they do not have any way of understanding

pillars of machine learning: regression, dimensionality reduction, density estimation, and classification
![[Pasted image 20210719195401.png]]

we represent numerical data as vectors and represent a table of such data as a matrix
the study of vectors and matrices is called [[linear algebra]]

vectors that are similar should be predicted to have similar outputs by our machine learning algorithm (our predictor)
to formalize the idea of similarity between vectors, we need to introduce operations that take two vectors as input and return a numerical value representing their similarity
construction of similarity and distances is central to [[analytic geometry]]

[[matrix decomposition]]

quantification of uncertainty is the realm of [[probability theory]]

to train machine learning models, we typically find parameters that maximize some performance measure
many optimization techniques require the concept of a gradient, which tells us the direction to which to search for a solution [[vector calculus]]

[[optimization]] to find maxima/minima of functions

[[linear regression]] objective is to find functions that map inputs $x \in \mathbb{R}^D$ to corresponding observed function values $y \in \mathbb{R}$
- [[classical model fitting]][[parameter estimation]] via maximum likelihood and maximum a posteriori estimation
- [[Bayesian linear regression]] - integrate parameters out instead of ptimizing them

[[dimensionality reduction]] using principal component analysis
- key objective is to find a compact, lower=dimensional representation of high-dimensional data $x \in \mathbb{R}^D$, which is often easier to analyze than the original data
- unlike regression, there are no labels associated with data points

[[density estimation]] - objective is to find a probability distribution that describes a given dataset
- [[Gaussian mixture models]]

[[classification model]]

[[algebra]] - construct a set of objects (symbols) and a set of rules to manipulate these objects

[[geometric vector]] familiar from high school math and physics
- directed segments that can be drawn in 2D

[[polynomial]] are also vectors; they can be multiplied by scalar
- abstract concepts as opposed to concrete drawings in geometric vectors

audio signals are vectors
elements of $\mathbb{R}^n$ (tuples of $n$ real numbers) are vectors

[[closure]] the question: what is the set of all things that can result from my proposed operations?
- in the case of vectors: what is the set of vectors that can result by starting with a small set of vectors, and adding them to each other and scaling them? this resluts in a [[vector space]]