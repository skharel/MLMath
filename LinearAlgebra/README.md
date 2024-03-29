# Lecture source

https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/

## Lecture videos

https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/ax-b-and-the-four-subspaces/the-geometry-of-linear-equations/

## Provided lecture notes

- Every lecture videos has accompanying lecture Note

## Other Useful links

1. [3 Blue 1 Brown - Essence of linear algebra](https://www.youtube.com/watch?v=kjBOesZCoqc&list=PL0-GT3co4r2y2YErbmuJw2L5tW4Ew2O5B)
2. [Immersive linear algebra](http://immersivemath.com/ila/tableofcontents.html)
   - Interactive content on Linear Algebra
3. [Interactive Linear Algebra](https://textbooks.math.gatech.edu/ila/index2.html)
   - This linear algebra content with visualization by GATech

# My notes

1. [The Geometry of Linear Equations](1/README.md)
   - column picture
   - linear combination
2. [Elimination with Matrices](2/README.md)
   - Gaussian Elimination
   - Upper Triangular form (U)
   - Singular, Non-Singular
   - Laws for matrix
     - Associative law: A(BC) = (AB)C is fundamental law
   - Elimination Matrix: `EA=U`
     - do bunch of eliminations and get from A to U
3. [Multiplication and Inverse Matrices](3/README.md)
   - Inverses
   - Gauss-Jordan elimination for finding inverse
   - Inverses of product (socks and shoes analogy)
4. [Factorization into A = LU](4/README.md)
   - A = LU
   - Cost of matrix elimination
   - Transpose
5. [Transposes, Permutations, Symmetric Matrices and Vector Spaces](5/README.md)
   - Permutation matrix and properties
     - P P<sup>T</sup> = I = P<sup>T</sup> P
     - P<sup>-1</sup> = P<sup>T</sup>
   - Symmetric Matrix: S<sup>T</sup> = S
     - inverse of symmetric is also symmetric
   - Non-symmetric (R) to symmetric
     - R<sup>T</sup> R is always symmetric
   - `Vector spaces`: R<sup>n</sup>
     - R<sup>n</sup> means every vector has n entries
     - spaces means think all vectors not just 1 or 2
   - `Subspaces`
   - Column space intro
6. [Column Space and Nullspace](6/README.md)
   - Column space
   - Solvability of `Ax = b`
   - Null Space
   - For A = m x n
     - C(A) is subspace of R<sup>m</sup>
     - N(A) is subspace of R<sup>n</sup>
7. [Solving Ax = 0: Pivot Variables, Special Solutions](7/README.md)
   - Computing all Null spaces of a matrix: x<sub>null</sub>
   - Pivot variables & Rank of a matrix
   - Free Variables
   - Special solutions
   - True size of a linear system
8. [Solving Ax = b: Row Reduced Form R](8/README.md)
   - Solve for non zero b: x<sub>particular</sub>
   - Find complete solution to Ax = b
     - x<sub>complete</sub> = x<sub>particular</sub> + x<sub>null</sub>
   - Solvability condition on b
   - Rank:
     - Full Column Rank
     - Full Row Rank
     - Full column rank & full row rank: Full Rank
9. [Independence, Spans, Basis and Dimension](9/README.md)
   - Independence
   - Spans
   - Basis (for a vector space)
     - Standard Basis => think I
     - Basis for C(A)
     - Basis for N(A)
   - Dimension
10. [Four Fundamental subspaces](10/README.md)
    - from A and A<sup>T</sup>
    - Column space and null space of A
    - Row space and left null space of A<sup>T</sup>
11. Matrix Spaces; Rank 1; Small world Graphs
    - Skipped notes writing for this
    - [lecture provided notes link](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/ax-b-and-the-four-subspaces/matrix-spaces-rank-1-small-world-graphs/MIT18_06SCF11_Ses1.11sum.pdf)
12. Graphs, Networks, Incidence Matrices
    - Skipped notes writing for this too!
    - [lecture provided notes link](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/mit18_06scf11_ses1-12sum/)
13. [Orthogonal Vectors and subspaces](13/README.md)
    - The 90<sup>o</sup> chapter: vectors perpendicular to each other
    - Orthogonal subspaces
    - Part-II of Fundamental Theroem of linear algebra
    - Orthogonal Complements
      - X = x<sub>r</sub> + x<sub>n</sub>
      - `What does Ax really do?`: Big picture again
    - Singular Value Decomposition importance of pseudoinverse
    - Valuable facts about bases
    - When is square matrix A<sup>T</sup>. A invertible?
      - N(A<sup>T</sup>A) = N(A)
      - rank (A) = rank (A<sup>T</sup>. A)
      - A<sup>T</sup> A is invertible exactly when A has independent columns
14. [Projections](14/README.md)
    - Why project?
    - Projecting onto a line and Projection matrix
    - Higher dimension projection
    - Horizontal and vertical projection
    - Key equation : A<sup>T</sup>Ax = A<sup>T</sup>
    - Projection matrix: P = A (A<sup>T</sup>A)<sup>-1</sup>A<sup>T</sup>
    - Key property about projection matrix:
      - P<sup>2</sup> = P
      - P<sup>T</sup> = P
15. [Projection Matrices and Least Squares](15/README.md)
    - Application of projection
      - Fit a straight line: Linear regression (without outliers)
      - Minimize squared error => least squares
    - Proof about A<sup>T</sup> A invertability
16. [Orthogonal Matrices and Gram-Schmidt](16/README.md)
    - Orthonormal vectors
      - Orthogonal (13) to Orthonormal
    - Orthogonal Matrix: `Q`
    - Gram-Schmidt: A to Q
    - Factorization: `A = QR`
      - R is upper triangular (opposite of L)
      - R = Q<sup>T</sup>A
17. [Determinants](17/README.md)
    - Properties of Determinants
18. Determinant Formulas and Cofactors
    - Skipped this
    - [lecture notes](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/mit18_06scf11_ses2-6sum/)
19. Cramer's Rule, Inverse Matrix and Volume
    - Skipped this
    - [lecture notes](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/mit18_06scf11_ses2-7sum/)
20. [Eigenvalues and Eigenvectors](20/README.md)
    - For when time comes into play: dynamically evolving systems
    - Key idea: What is the thing that changes with time?
    - Eigen Vectors and Eigen Values
      - `Ax = λx`
      - Eigen value equation: `det (A - λI) = 0`
      - Trace = sum of main diagonals = sum of eigen values
      - n x n matrix has n eigen values
    - Triangular Matrices - eigen values are entry on the diagonal
21. [Diagonalization and powers of A](21/README.md)
    - `AS = SΛ`
      - S is eigen vector matrices of A (and is square matrix)
      - Λ is the diagonal eigen value matrix
    - Diagonalization: S<sup>-1</sup>AS = Λ
    - Factorization of A: A = SΛS<sup>-1</sup>
    - Powers of A: A<sup>K</sup>x = λ<sup>K</sup>x
    - `Skipped notes on dynamic systems`
      - difference equation
      - Fibonacci sequence
22. Differential Equations and exp(At)
    - Skipped this
    - [lecture notes](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/mit18_06scf11_ses2-10sum/)
23. Markov Matrices; Fourier Series
    - skipped this
    - [lecture notes](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/mit18_06scf11_ses2-11sum/)
24. [Symmetric Matrices and Positive Definiteness](24/README.md)
    - Symmetric Matrices: A = A<sup>T</sup>
      - Props:
        - 1. has real eigen values
        - 2. Eigen vectors can be chosen to be orthonormal
    - Factorization of symmetric matrix: A = QΛQ<sup>T</sup>
      - This is `Spectral Theorem` - combination of pure eigen values and eigen vectors
    - \# number of positive pivots = \# number of positive eigen values
    - Also from earlier lecturs:
      - product of pivots = determinant = product of eigen values
    - All symmetric matrices are diagonalizable
    - Special case:
      - Symmetric matrices has all positive eigen values if all pivots are positive: `Positive Definite Matrices`
25. COMPLEX MATRICES; FAST FOURIER TRANSFORM (FFT)
    - Skipped this
    - [lecture notes](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/mit18_06scf11_ses3-2sum/)
26. [Positive Definite Matrices and Minima](26/README.md)
    - Positive definite matrix
    - x<sup>T</sup>Ax is positive except when x is 0
    - Sum of positive definite matrix, results in positive definite matrix
    - Right on the border line? `Positive Semidefinite matrix`
    - lecture notes:
      - tests for minimum
      - `Hessian` matrix
27. [Similar Matrices](27/README.md)
    - Similar matrices means same eigen values
    - lecture notes:
      - see rest on lecture notes
28. [Singular Vector Decomposition: SVD](28/README.md)
    - A = UΣV<sup>T</sup>
      - U and V are singular vectors
      - Σ is singular values
    - U comes from AA<sup>T</sup>
    - V comes from A<sup>T</sup>A
    - Principal Component

## What next?

[MATRIX METHODS IN DATA ANALYSIS, SIGNAL PROCESSING, AND MACHINE LEARNING](../MatrixMethods/)
