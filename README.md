# Bayesian spatial temporal crime risk model

The projects aim is to model the risk of violant crime using Bayesian spatial-temporal models. In this repository, you will find the posterior samples generated from all the models we fit. This was for my final year university project.

**summary.csv**: This file contains the summary statistics for each parameter estimated by the model, including the mean, standard deviation, Monte Carlo error and the 2.5% and 97.5% quantiles.

Notation:

$SP_i = \alpha + S_i + U_i$

spatial.rr = exp($SP_i - \alpha$) $=$ exp($S_i + U_i$)

temporal.rr = exp($v_t$)
