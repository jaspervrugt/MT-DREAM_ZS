# MT-DREAM_ZS: Multi-try implementation of MCMC simulation with the DREAM_ZS algorithm 

## Description

Spatially distributed hydrologic models are increasingly being used to study and predict soil moisture flow, groundwater recharge, surface runoff, and river discharge. The usefulness and applicability of such complex models is increasingly held back by the potentially many hundreds (thousands) of parameters that require calibration against some historical record of data. The current generation of search and optimization algorithms is typically not powerful enough to deal with a very large number of variables, and summarize parameter and predictive uncertainty. In a previous paper \citep{Vrugt2008}, we have presented a general-purpose Markov Chain Monte Carlo (MCMC) algorithm for Bayesian inference of the posterior probability density function of hydrologic model parameters. This method, entitled DiffeRential Evolution Adaptive Metropolis (DREAM), runs multiple different Markov chains in parallel and uses a discrete proposal distribution to evolve the sampler to the posterior distribution. The DREAM approach maintains detailed balance and shows excellent performance on complex, multi-modal, search problems. Here, we present our latest algorithmic developments, and introduce MT-DREAM_{(ZS)}, which combines the strengths of multi-try sampling, snooker updating, and sampling from an archive of past states. This new code is especially designed to solve high-dimensional search problems, and receives particularly spectacular performance improvement over other adaptive MCMC approaches when using distributed computing. Four different case studies with increasing dimensionality up to 241 parameters are used to illustrate the advantages of MT-DREAM_{(ZS)}.

## Getting Started

### Installing

* Download and unzip the zip file 'MATLAB_pcode_MTDREAM_ZS_V1.0.zip'.
* Add the toolbox to your MATLAB search path by running the script 'install_MTDREAM_ZS.m' available in 'MATLAB_pcode_MTDREAM_ZS_V1.0'
* You are ready to run the examples.

### Executing program

* After intalling, you can simply direct to each example folder and execute the local 'example_X.m' file.
* Please make sure you read carefully the instructions (i.e., green comments) in 'install_MTDREAM_ZS.m' and the attached paper in PDF !!!  

## Authors

* Vrugt, Jasper A. (jasper@uci.edu) 

## Version History

* 1.0
    * Initial Release

## Acknowledgments
