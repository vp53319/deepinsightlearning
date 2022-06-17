---
title: "The Transpose Operation with Examples in Python and Google Colab"
date: 2022-06-16T15:31:05-07:00
---

This tutorial describes the transpose operation of vectors and matrices in linear algebra with Python examples in Google Colab. The transpose operation is a basic and simple operation in linear algebra, but it is often used in machine and deep learning. The Transpose operation is often represented by the superscript capital letter T, and it basically switches the rows and columns of vectors and matrices. For example, if we have a 1x4 (1 row 4 columns) row vector V of [3.7 8.9 9.8 3.7]. These numbers represent gravity of Mercury, Venus, Earth, and Mars respectively.  Then the transpose of V is V<sup>T</sup>: 

\begin{bmatrix} 3.7 \cr 8.9 \cr 9.8 \cr 3.7 \end{bmatrix}

V <sup>T</sup> now becomes a 4x1 (4 rows 1 column) column vector with the same order of numbers as V. The only change is its orientation from row to column vector.  9.8 is the 3rd element of V with the position of 1x3 (1st row 3rd column). The transpose of this element is the same 9.8 but the position is switched to 3x1 (3rd row 1st column). If you take the vector V<sup>T</sup> and apply the transpose of operation, you’ll get the original vector back: (V<sup>T</sup>)<sup>T</sup> = V. Thus, double transposing brings us back to the original vector. Now, transposing a matrix is the same concept. You just have to be more careful about switching more rows and columns so the MxN matrix would transpose to NxM. Similarly, a transpose of a transposed matrix (double transposing) would result in the original matrix.

Right Click and open the link below in new tab to see Colab notebook:

[Google Colab Notebook of Transpose Examples using Python Numpy and PyTorch libraries](https://colab.research.google.com/drive/1twWSeWpqJ71ARhZScozzo-AJvJdkQiTX?usp=sharing)

![Colab Picture 1 of Transpose Operation](/img/transpose-01.jpg)
![Colab Picture 2 of Transpose Operation](/img/transpose-02.jpg)


