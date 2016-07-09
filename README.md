# No-U-Turn-Sampler (Matlab implementation)
This repository contains a Matlab implementation of No-U-Turn-Sampler (NUTS) by Hoffman and Gelman (2014). The script 'getting_started_with_NUTS_and_dual_averaging_algorithm.m' illustrates the use of the main functions 'NUTS' and 'dualAveraging.' Additional examples can be found under the 'Example' folder.

The code here is suitable for research purposes as it provides access to the inner workings of NUTS and is customizable. (The implementation here in particular allows one to use NUTS as a Gibbs step.) The code should also be useful for those who want better understanding of how NUTS and HMC work (and when it might perform poorly). For applied Bayesian modelling, however, using Stan would be the easiest way to take advantage of the generality of NUTS and HMC.

## Acknowledgement
The code for the main functions 'NUTS' and 'dualAveraging' is mostly based on the implementation by Hoffman. 

## License
There are very few restrictions on the use of the codes here - see the LICENSE.md file for details.

