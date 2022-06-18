---
title: "The Dot Product With Examples in Python and Google Colab"
date: 2022-06-18T11:16:26-07:00
---

Scalar product or vector dot product is one of the basic operations of applied mathematics. Therefore, dot product is also one of the key operations in deep learning. Calculating the dot product is a simple procedure involving multiplication and summation. The result of the dot product is always a scalar, a number. We may use different symbols to represent the dot product. Sometimes we will see the dot product written as X * Y, where both X and Y are vectors. Other times we will see the dot product written as <X, Y>. But the most common notation we will see is X<sup>T</sup>Y, X transposes Y. So for each element respectively, we multiply two elements in vectors X and Y, and then we add them together resulting in a single number. 

As a simple example to illustratate, let consider the dot product of two vector: X = [1, -8, 10, 6], and Y = [6, -9, -1, 5]. X<sup>T</sup> is: \begin{bmatrix} 1 \cr -8 \cr 10 \cr 6 \end{bmatrix}


 Then the dot product is: $$ x^Ty = 1\times 6 + (-8)\times (-9) \\\ + 10\times (-1) + 6\times 5 = 98$$
 
 To calculate the dot product between vector X and vector Y, so we multiply each element from both vectors in order.
 we take 1, the first element of X, times 6, the first element of Y. Next, we take -8, the 2nd element of X, times -9, the second element of Y. We repeat this multiplication process for the remainder. Then we sum them up. This result in 98 for our example above. Because of the algorithm, will always be a single, scalar number, and the dot product only exists between vectors of the same number of elements or matrices of the same dimension, both matrices have to be 3x4 for example. We will see in our Colab example that trying to find the dot product of two vectors of different elements will result in error.

 A matrix is two dimensional with m rows and n columns. We can also compute the dot product with matrices. However, both matrices have the same dimension. Let's take a look at the example below dot product of matrices

 If the matrix X is 

 $$
\begin{bmatrix}
  15 & 9 & -2 \cr
  -6 & -5 & 13 
\end{bmatrix}
$$

and the matrix Y is 

 $$
\begin{bmatrix}
  3 & 8 & -17 \cr
  -1 & 7 & -6 
\end{bmatrix}
$$

Then the dot product is: $$ x^Ty = (15\times 3 + 9\times 8 + (-2)\times (-17))  \\\ + ((-6)\times (-1) + (-5)\times 7 + 13\times (-6)) = 44$$


As we can see from both examples, the dot product will compute to a single number. No matter if we have large vectors or matrices with many elements, we will always calculate the dot product to a single number. The other caveat is that the dot product is only defined between two matrices or two vectors that have exactly the same shape and dimensions. In our examples both vectors have 4 elements, and both matrices are 3x2.

One interpretation of the dot product is that it represents the similarity or commonality between two entities, a correlation or coefficient of covariance of X and Y in statistics for example. We can think of the correlation as just a quirky way of calculating the dot product. Either way, the unique number of the dot product reflects common characteristics between the two objects. Now the objects can be represented mathematically as vectors, matrices, or tensors. Then mathematically, the dot product a number that reflects the common ground between two mathematical objects in the set of numbers. In fact, the dot product is the backbone of calculations for many of the things we are already familiar with, even if the term dot product is new to us. For example, the role of the dot product is prominent in correlation and least square in statistics, Fourier transform in signal processing, convolution and matrix multiplication in deep learning, and quantum mechanics in physics, etc.
