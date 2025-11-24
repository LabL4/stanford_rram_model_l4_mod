# Modified Stanford RRAM model by the University of Granada.

This repository contains the verilog A code for a modified version of the Stanford RRAM model. There are two main modifications:

    1. The model includes the effect of the series resistance, which has been shown to improve the fitting of experimental data from HfO2-based RRAM devices [1]. For other types of RRAM devices, the series resistance effect can be disabled by setting the parameter r_series to 0.
    2. The model incorporates tanh smoothing functions to avoid convergence issues during simulations caused by the original piecewise definitions for the gap and gamma variables.
    


# References
[1]D. Maldonado et al., “Experimental study of the series resistance effect and its impact on the compact modeling of the conduction characteristics of HfO2-based resistive switching memories,” Journal of Applied Physics, vol. 130, no. 5, Aug. 2021, doi: 10.1063/5.0055982.
  

