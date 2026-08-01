This repository verifies the linear independence of F_p,k1,k2,c for different p 
by testing the non-singularity of the matrix formed by their Fourier coefficients. 
To run it, copy the code from the first 3 files into Sage, and use the function below:
example_1 = analyze_F(d,
    p1, ... , pd,
    k1, k2, c,
    displayed_coefficients=n,
    print_full_matrix=False,
) 
Here, the inputs are as follows
d: number of primes; 
p1,...,pd: the chosen primes; 
n: the first n coefficients;
k1,k2,c: the indices of F.
