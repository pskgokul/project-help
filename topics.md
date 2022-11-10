# Topics to choose from (34)

The below are listed by chapter. 

1.  Scientific Computing
	1. Floating point number systems. Include some examples of non-standard (non-IEEE) floating point systems. When one might use various types of floating point systems. How they are implemented in software and hardware. Why different hardware may only natively support certain types of floating point numbers.
	2. Floating point arithmetic, how floating point errors can grow and how to prevent it. Catestrophic cancellation. 
	3. Backward and forward errors. Include how they can be used to compute stability of an algorithm, the relative pitfalls of each (including how one actually computes them), and how they are used in practice.

2. Systems of linear equations
	1. Solution methods for general linear systems (assume no knowledge of the matrix $A$ is known. Include discussion of conditioning, sensitivity.
	2. Solution methods for "special" but dense linear systems, including SPD, and symmetric. Including conditioning, sensitivity.
	3. How to solve sparse linear systems of equations, including banded, and what adjustments should be made from methods for dense matrices.
	4. Software for linear equations, LAPACK, BLAS, and vendor-specific varieties on them. How they are used. How supercomputers are benchmarked using them. Why supercomputers are benchmarked using them.

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
	1. What are nonlinear equations and why is solving them challenging? How do we know if a solution exists? How do we check? Discuss conditioning and uniqueness. Discuss why iterative methods are needed (as opposed to direct methods). How nonlineawr equations and root finding are equivalent.
	2. Derivative free methods for rootfinding: Bisection, Secant, etc. How they work, why they work, what could go wrong. 
	3. Fixed-point iteration methods and Newton's method. How they work, why they work, what gould go wrong. 

6. Optimization
	1. Overview of optimization, constrained vs unconstined optimization, how optimization problems are defined, relevance of convexity and optimality conditions. Degenerate cases where things can go "wrong". Linear vs. quadratic vs. nonlinear programming.
	2. 1D unconstained optimization algorithms. Parabolic interpolation, Newton's method, etc. How they work, rates of convergence, why they work, pros and cons of the various different methods.
	3. 2D optimization algorithm(s). Steepest descent. How the methods work.
	4. Equality constrained optimization. Lagrangians. How they work, example, what can go wrong.

7. Interpolation
	1. What is interpolation, what is it used for (broadly construed, including in the context of numerical integration), how one should choose what kind of interpolation method to use, differences between least squares fitting.
	2. Basis function options/choices, pros and cons of each. Include examples. Include orthogonal polynomials of multiple flavors. 
	3. Piecewise interpolation. Why we do it. Include discussion of splines, including B-splines (not explicitly discussed in class). How splines differ from other types of interpolants.

8. Numerical integration and differentiation
	1. Newton-Cotes quadrature. How it works, what makes it different from other types of quadrature. When it might be used over other quadrature rules. How one derives different such quadrature rules of different "degree". Extension to composite quadrature rules.
	2. Gaussian quadrature. How it differs from other types of quadrature and its relative advantages and disadvantages. Different "types" of Gaussian quadrature.
	3. Finite differences. Different types, and when one might pick one over the others.

9. Initial value problems for ODEs
	1. Types of numerical methods for time stepping. Relative advantages of different methods. 
	2. Accuracy and stability of different types of time stepping methods. How they are derived and why they are what they are.
	3. Implicit time stepping. Example methods and when it should/shouldn't be used.

10. Boundary value problems for ODEs 
