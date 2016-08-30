
# This code is an implementation of Algorithm 2 in the paper:
T. Le, V. Subramanian, R. Berry, **Quantifying the Utility of Noisy Reviews in Stopping Information Cascades**, manuscript submitted to IEEE CDC, 2016. Archived version available at: https://archive.org/details/CDC2016Archive

## The algorithm calculates, for the case of bad product, the probability of the time until a correct information cascade happens (i.e., people learn the true value of the product and stop buying it), $P[\tau = n|h_1]$. Here we are conditioning on $h_1$, the state of the system after the first agent's action choice and his review.

## The algorithm idea is to build a breadth-first tree conditioned on $h_1$.

## Here, n is the first agent who starts the correct cascade.
Computational power of my laptop allows up to around 17.

## The outputs are written to .csv files for different values of the private signal $p$. Then these results are read to MATLAB for further processing and generatting the plots.
