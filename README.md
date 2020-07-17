# Python-Programming-for-Data-Science

Benefits of Python (McKinney, 2018, p. 2)
•	Used to quickly write small programs or scripts to automate other tasks.
•	Has large and active scientific computing and data analysis community.
•	Easy to integrate with C, C++, and FORTRAN. (Most modern computing environments hare a similar set of legacy FORTRAN and C libraries for doing linear algebra, optimization, integration, fast Fourier transforms, etc.)
•	It’s suitable for research, prototyping, and production systems.

Disadvantages of Python (McKinney, 2018, p. 3)
•	Interpreted code runs slower than compiled languages (i.e., Java or C++)
•	Challenging for building highly concurrent, multithreaded applications with many CPU-bound threads.  Its Global interpreter lock (GIL) prevents the interpreter from executing more than one Python instruction at a time.

Essential Libraries (McKinney, 2018, p. 3-8)
•	Numerical Python (NumPy) – provides data structures (ndarray), algorithms (linear algebra operations, Fourier transform, and random number generation), and library glue for scientific applications involving numerical data.
•	Python Data Analysis (Pandas) – provides high-level data structures and functions to make working with structured or tabular data fast, easy, and expressive.  Provides indexing functionality to make it easy to reshape, slice and dice, perform aggregations, and select subsets of data.
•	Matplotlib – library for producing plots and other two-dimensional data visualizations suitable for publication.
•	SciPy – a collection of packages  
o	.integrate --  numerical integration routines and differential equation solvers
o	.linalg – linear algebra routines and matrix decompositions
o	.optimize –function optimizers (minimizers) and root finding algorithms
o	.signal – signal processing tools
o	.sparse – sparse matrices and sparse linear system solvers
o	.special – wrapper around SPECFUN (a fortran library for common mathematical functions)
o	.stats – standard continuous and discrete probability distributions (density functions, samplers, continuous distribution functions), statistical tests, etc.
•	Scikit-learn – a general purpose machine learning toolkit.  Contains:
o	Classification: SVM, nearest neighbors, random forest, logistic regression
o	Regression: Lasso, ridge regression
o	Clustering: k-means, spectral clustering
o	Dimensionality reduction: PCA, feature selection, matrix factorization
o	Model selection: Grid search, cross-validation, metrics
o	Preprocessing: Feature extraction, normalization
•	Statsmodels – a statistical analysis package focused on statistical inference, uncertainty estimates, and p-values for parameters. Contains algorithms for classical (primarily frequentist) statistics and econometrics.  This includes:
o	Regression models: linear regression, generalized linear models, robust linear models, linear mixed effects models
o	Analysis of variance (ANOVA)
o	Time series analysis: AR, ARMA, ARIMA, VAR
o	Nonparametric methods: Kernel density estimation, kernel regression
o	Visualization of statistical model results

McKinney, W. (2018) Python for Data Analysis: Data Wrangling with Pandas, Numpy, and IPython. O’Reilly Media, Inc.
