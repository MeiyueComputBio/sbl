# sbl
An R package implements sparse Bayesian learning method for QTL mapping and GWAS

## Introduction

`sbl`  The sparse Bayesian learning (SBL) method for quantitative trait locus (QTL) mapping and genome-wide association studies deals with
a linear mixed model. This is also a multiple locus model that includes all markers (random effects) in a single model with effects being
estimated simultaneously. SBL method adopts coordinate descent algorithm to update parameters by estimating one parameter at a time 
conditional on posterior modes of all other parameters. The parameter estimation process requires multiple iterations and the final 
estimated parameters take the values when the program converges. `sbl` can handle extremely large sample size (>100,000) and outcompetes
other multiple locus GWAS methods in terms of detection power and computing time.

## sbl manual

A user manual of `sbl` is available here: [sbl manual](https://github.com/MeiyueComputBio/sbl/blob/master/sbl%20manual/sbl.tutorial.Rmd)

## Installation

Please download the compressed package [sbl_0.1.0.tar.gz](https://github.com/MeiyueComputBio/sbl/tree/master/R%20packge) and run the following commond in R console

```R
install.packages('sbl_0.1.0.tar.gz", repos=NULL, type='source')
```
