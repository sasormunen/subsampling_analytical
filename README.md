# subsampling_analytical


Here you can find the code for obtaining the analytical results in section IVC in the paper Distinguishing subsampled power laws from other heavy-tailed distributions (Sormunen, Leskelä & Saramäki, ArXiv: ). In short, the code is used for calculating how the method of Clauset et al. [1] would behave on samples from different probability distributions as the sample size $n \to \infty$. The functions for optimizing parameters of the distributions are modified versions of those of the \emph{powerlaw} package by Alstott et al. [2], as the goal has been to replicate the results of this implementation as faithfully as possible with the exception that we are dealing with theoretical probability distributions instead of empirical or simulated samples.  

[1] A. Clauset, C. Shalizi, and M. Newman, Power-law distributions in empirical data, SIAM Review \textbf{51} (2007).
[2] J. Alstott, E. Bullmore, and D. Plenx, powerlaw: a Python package for analysis of heavy-tailed distributions, PLoS ONE 9(4): e95816 (2014). 
