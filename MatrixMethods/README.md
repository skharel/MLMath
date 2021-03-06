# MATRIX METHODS IN DATA ANALYSIS, SIGNAL PROCESSING, AND MACHINE LEARNING

# Lecture source

https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/

## Lecture videos

https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/video_galleries/video-lectures/

# My notes

1. [THE COLUMN SPACE OF A CONTAINS ALL VECTORS AX](1/README.md)
   - Column space
   - Rank One
   - A = CR
   - Rank Theroem: column rank = row rank
   - Sampling columns from large matrix
2. [MULTIPLYING AND FACTORING MATRICES](2/README.md)
   - Inner and outer product
   - Inner product as matrix multiplication
   - Rank 1 matrices as building blocks
   - `Why outer product is essential in Data Science?`
3. [ORTHONORMAL COLUMNS IN Q GIVE Q’Q = I](3/README.md)
   - Orthogonal & orthonormal
   - Qx => length of vectors does not change in output
   - Standard basis uses orthonormal vectors
   - Hadamard matrices
4. [EIGENVALUES AND EIGENVECTORS](4/README.md)
   - Ax = λx and A<sup>n</sup>x = λ<sup>n</sup>x
   - Factorization A = XΛX<sup>-1</sup>
5. [POSITIVE DEFINITE AND SEMIDEFINITE MATRICES](5/README.md)
   - Symmetric matrices: S = S<sup>T</sup>
     - all eigen values are real
     - all eigen vectors can be chosen to be orthogonal
   - x<sup>T</sup>Sx > 0 (Energy > 0)
     - Graph is bowl opening upwards
     - Optimization problems in Deep Learning tries to gets to E = 0
     - Connects Linear Algebra to Calculus
6. [SINGULAR VALUE DECOMPOSITION (SVD)](6/README.md)
   - Can be done for all Matrices
   - A = UΣV<sup>T</sup>
     - U and V are singular vectors
     - Σ is singular values
     - U is left singular value
     - V is right singular value
   - A is sum of r pieces of rank 1
   - `Why is SVD important for Data Science?`
     - Hint of Eckart-Young (PCA)
   - Geometry of SVD:
     - rotate, stretch and rotate
