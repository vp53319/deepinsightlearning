---
title: "The Transpose Operation with Examples in Python and Google Colab"
date: 2022-06-16T15:31:05-07:00
---

This tutorial describes the transpose operation of vectors and matrices in linear algebra with Python examples in Google Colab. The transpose operation is a basic and simple operation in linear algebra, but it is often used in machine and deep learning. The Transpose operation is often represented by the superscript capital letter T, and it basically switches the rows and columns of vectors and matrices. For example, if you have a 1x4 (1 row 4 columns) row vector V of [3.7 8.9 9.8 3.7]. These numbers represent gravity of Mercury, Venus, Earth, and Mars respectively.  Then the transpose of V is V<sup>T</sup>: 

\begin{bmatrix} 3.7 \cr 8.9 \cr 9.8 \cr 3.7 \end{bmatrix}

V <sup>T</sup> now becomes a 4x1 (4 rows 1 column) column vector with the same order of numbers as V. The only change is its orientation from row to column vector.  9.8 is the 3rd element of V with the position of 1x3 (1st row 3rd column). The transpose of this element is the same 9.8 but the position is switched to 3x1 (3rd row 1st column). If you take the vector V<sup>T</sup> and apply the transpose of operation, you’ll get the original vector back: (V<sup>T</sup>)<sup>T</sup> = V. Thus, double transposing brings us back to the original vector. Now, transposing a matrix is the same concept. You just have to be more careful about switching more rows and columns so the MxN matrix would transpose to NxM. Similarly, a transpose of a transposed matrix (double transposing) would result in the original matrix.

You can create vector and matrix by first importing the Python Numpy and PyTorch libraries. It is better to create a row vector using the double bracket. This is because it will give us a two-dimensional array of 1 one row and n columns. When you do a transpose, it will then give us the correct dimension of n rows and 1 column.

You can take a look at the Colab notebook below to see how the transpose operation is implemented in Python. Right Click and open the link below in new tab to see Colab notebook: 

[Google Colab Notebook of Transpose Examples Using Python Numpy and Pytorch Libraries](https://colab.research.google.com/drive/1twWSeWpqJ71ARhZScozzo-AJvJdkQiTX?usp=sharing) . 

I also made a YouTube video discussing the same examples of the transpose operation in Google Colab: {{< youtube 2PNbdVPrpfE >}} 

I included screenshots of the Colab notebook so you can follow along. The first thing I did in Colab is importing the NumPy and PyTorch (torch). Next, I created 2 row vectors and stored them in variables vector and vector_1d. Notice that I created one vector with double brackets and the other with single bracket. It does not matter in other situations, but in this case, you want to create the vector using double brackets instead of single bracket. This is because the single bracket will create a vector of one dimension, whereas the double brackets will create a two-dimension vector. The double brackets vector then has two dimensions of one row and four columns. In NumPy, the transpose operation is represented by the letter capital T. When you do the transpose with the letter T the two-dimension double brackets vector, it will give us the correct transformation to a column vector of one column and four rows, as you can see. If you do a transpose on the one-dimension single bracket vector_1d, NumPy will just return the same one-dimension row vector as the original. So, use the double brackets to create a vector 

The transpose operation is used often in machine learning and deep learning. The transpose operation (T) is basically just switching the row and column element by element. For example, if you look at the vector variable in Colab, the position of 9.8 is the first row and third columns, so if you do the transpose, then the element would change to third row and first column. The order of the elements is going to be the same, it is the shape or orientation that switches. Notice also that if you can apply the transfer twice double transfer (T.T), it could give us back the original vector.

You can see the type of the variables by applying the type() method. Both vector variables have the type ndarray. You can access the shape parameter to find that the original vector has a shape of 1 row x 4 columns whereas the transposed vector has the shape of 4 rows x 1 column.  I also show in the next example another way to create a vector using [np.newaxis] option.  As you can see from the print() method, the vector, the transposed vector, and the double transposed vector gives us essentially the same results as the double brackets procedure. By the way, the original vector or matrix is unchanged from the operation. You can assign the transposed result to a new variable for later use.

You can also create matrices using the NumPy library. In the next Colab example I created a two by four matrix of two rows and four columns and stored it in the variable matrix. Then I apply the transpose operation with a capital T to the matrix (matrix.T) which would return a four by two a matrix. For example, if the number 11 is first row third column in the original matrix, then after transpose, it will switch around and be at the position third row and first column as seen in Colab.  You can check the shape and type of the matrix by accessing the shape parameter and applying the type() method. The original matrix of two by four becomes a four by two after transposed. Both of the matrix and the transposed matrix have the type of ndarray.

Now you don't have to use the NumPy to create vectors and matrices.  You can also the PyTorch library to create them, but the type of these vectors and matrices will be tensor.  Once created as seen in my Colab notebook, you can use the same capital T operation to transpose or the double transpose (T.T).  In our example, a transpose (T) would result in a a column vector, and then the double transpose (T.T) would result back the original vector. Similarly, you can also check the shape and type of the vectors: 1x4 for the original vector and 4x1 for the transposed vector. However, both vectors are of type tensor. For the second to last example, I created a 2x4 matrix of type tensor using the PyTorch. Apply the transpose T results in a 4x2 matrix also of type tensor.  Double transposed (T.T) result in the original matrix again. Finally, if you want to create a column vector, you can do it like the last example in my Colab notebook.  From the print out, you see that it’s a column vector with the shape of four rows and one column. Then the transposed vector becomes a row vector with the shape of one row and four columns!


![Colab Picture 1 of Transpose Operation](/img/transpose-01.jpg)
![Colab Picture 2 of Transpose Operation](/img/transpose-02.jpg)
![Colab Picture 1 of Transpose Operation](/img/transpose-03.jpg)
![Colab Picture 2 of Transpose Operation](/img/transpose-04.jpg)



