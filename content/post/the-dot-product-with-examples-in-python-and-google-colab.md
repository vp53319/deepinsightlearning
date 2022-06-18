---
title: "The Dot Product With Examples in Python and Google Colab"
date: 2022-06-18T11:16:26-07:00
---

Scalar product or vector dot product is one of the basic operations of applied mathematics. Therefore, dot product is also one of the key operations in deep learning. Calculating the dot product is a simple procedure involving multiplication and summation. The result of the dot product is always a scalar, a number. We may use different symbols to represent the dot product. Sometimes we will see the dot product written as X * Y, where both X and Y are vectors. Other times we will see the dot product written as <X, Y>. But the most common notation we will see is X<sup>T</sup>Y, X transposes Y. So for each element respectively,  we multiply two elements in vectors X and Y, and then we add them together resulting in a single number. 

As a simple example to illustratate, let consider the dot product of two vector: X = [1, -8, 10, 6], and Y = [6, -9, -1, 5]. X<sup>T</sup> is: \begin{bmatrix} 1 \cr -8 \cr 10 \cr 6 \end{bmatrix}


 Then the dot product is: $$ x^Ty = 1\times 6 + (-8)\times (-9) + 10\times (-1) + 6\times 5 = 98$$
 
 To calculate the dot product between vector X and vector Y, so we multiply each element from both vectors in order.
 we take 1, the first element of X, times 6, the first element of Y. Next we take -8, the 2nd element of X, times -9, the second element of Y. We repeat this multiplication process for the remainder. Then we sum them up. This result in 98 for our example above. Because of the algorithm, will always be a single, scalar number, and the dot product only exists between vectors of the same number of elements or matrices of the same dimension, both matrices have to be 3x4 for example. We will see in our Colab example that trying to find the dot product of two vectors of different elements will result in error.

 A matrix is two dimensional with m rows and n columns. We can also compute the dot product with matrices. However both matrices have to same the same dimension. Let's take a look at the example below dot product of matrices

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

Then the dot product is: $$ x^Ty = (15\times 3 + 9\times 8 + (-2)\times (-17)) + ((-6)\times (-1) + (-5)\times 7 + 13\times (-6)) = 44$$

 
 the Y elements by a number. So once two plus zero times these eight terms you see here plus twice negative six plus five times one plus negative twice zero. And if you do all these individual multiplications and that gives you two minus 12 plus five, that gives you negative five. So the dot product between these two vectors is negative five. Note that the DOT product is a unique number. The DOT product between two vectors will always be a single, unique number. Now the DOT product is undefined for the two vectors. It is only defined for two vectors of the same number. So, to be of the same length or the same dimension, they must have the same number. And to illustrate this, you will try to calculate the DOT product between this vector V that is the same as the previous edge and this other vector W, which has fewer elements. So we have a five-element vector and a three-element vector. Now, you know, you can go on with a good DOT product, but there's no matching item here to duplicate. So you get five times, you know, nothing. You can't put zeros here because adding zeros here will actually give you another vector. It won't be the same vector as the W vector here. So the conclusion of this slide is that the DOT product is only defined between two vectors that have exactly the same number, the same number of elements in them. Of course, you can also truncate those last two numbers here, then you'll have a three-element vector like W, and then you can calculate the DOT product between them. OK, so here are the DOT products for the mold. You can also calculate. Sorry, I meant vectors. It is a dot product between vectors. We can also compute the DOT product in two dimensions and this is what we will do when we learn more about convolutional and cumulative neural networks or CNNs. And so the procedure is exactly the same. just more numbers to keep track of. So the DOT product between this matrix and this matrix is ​​this element times this element. So don't multiply one plus three times don't add two times six and so on. for each of these nine elements. This simplifies for these numbers. And it's actually pretty simple to compute now because we get all six canceled out and so we end up with the DOT product between these two matrices equaling 20. Again, with the product of We are a single number. No matter how large these vectors or matrices are, we always end up with a single number. And a second point of note is that the DOT product is only defined between two matrices or two vectors that have exactly the same shape and must have the same dimensions. So in this case, three times three.