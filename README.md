# sbl
An R package implementing sparse Bayesian learning method for QTL mapping and GWAS

## Introduction

`sbl`  The sparse Bayesian learning (SBL) method for QTL mapping and genome-wide association studies deals with a linear mixed model. This
is also a multiple locus model that includes all markers (random effects) in a single model and detect significant markers simultaneously.
SBL method adopts coordinate descent algorithm to update parameters by estimating one parameter at a time conditional on values of all 
other parameters. The parameter estimation process requires multiple iteration and the final estimated parameters take the values when the 
program converge.`sbl` can handle extremely large sample size (>100,000) and computationally efficient.

## sbl manual

A user manual of `sbl` is available here: [sbl manual](http://)

## Installatioin

Please download the compressed package [sbl_0.1.0.tar.gz](http://) and run the following commond in R

```R
install.packages('sbl_0.1.0.tar.gz", repos=NULL, type='source')
```
