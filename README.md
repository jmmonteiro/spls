# spls
Sparse Partial Least Squares method using L1 and L2 norm constraints. Please check the paper by [Monteiro _et al._ 2016](http://www.sciencedirect.com/science/article/pii/S0165027016301327) for details.

The computation of the first weight vector pair (u,v) should be done using `spls.m`. Then, matrix deflation should be performed using `proj_def.m`, and the process repeated in order to find the next weight vector pair.
