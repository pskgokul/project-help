# Topics to choose from (34)

The below are listed by chapter. 

1.  Scientific Computing
	1. Floating point number systems and their arithmetic
	2. Backward and forward errors. Include how they can be used to compute stability of an algorithm, the relative pitfalls of each, and how they are used in practice.

2. Systems of linear equations
	1. Solution methods for general linear systems (assume no knowledge of the matrix $A$ is known. Include discussion of conditioning, sensitivity.
	2. Solution methods for "special" types of linear systems, including tridiagonal, SPD, and symmetric. Including conditioning, sensitivity.
	3. Software for linear equations, LAPACK, BLAS, and vendor-specific varieties on them. How they are used. 

3. Linear least squares
	1. The normal equations. What they are, what you are used for, what the problem with them is, when one might consider using them, why one might learn about them.
	2. Gram-Schmidt orthogonalization (standard and motified versions), including potential for loss of orthogonality. What problems it is and is not practical for.
	3. The SVD. What is it, what it can be used for, how it can be computed. 

4. Eigenvalue problems
	1. What is an eigenvalue problem? What is a generalized eigenvalue problem? What are they used for, when do they come up? Include both practical applications/exapmles as well as how they can show up or be useful for numerical methods.
	2. Power method. How it works, why its used, its limitations and strengths, how it can be improved. Include discussion of normalization and shifting.
	3. QR iteration. How it works, why its used, its limitations and strengths.
	4. Subspace methods. Their history, what they are particularly good for, why they work quite well for some problems.
	5. Software: How does one compute eigenvalues for big problems in practice? What about for specific types of matrices, like symmetric or SPD? Examples should be libraries used in HPC applications (not Python implemenations).

5. Nonlinear equations
	1. What are nonlinear equations and why is solving them challenging? How do we know if a solution exists? How do we check? Discuss conditioning and uniqueness. Discuss why iterative methods are needed (as opposed to direct methods).
	2. 

6. Optimization

7. Interpolation

8. Numerical integration and differentiation

9. Initial value problems for ODEs

10. Boundary value problems for ODEs 
