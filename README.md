# Chapter 5, Heterogeneous Treatment Effects

R code and walkthrough for a Heterogeneous Treatment Effects analysis chapter. The main file is [`code/Walkthrough of Heterogeneous Treatment Effects Analysis.Rmd`](code/Walkthrough%20of%20Heterogeneous%20Treatment%20Effects%20Analysis.Rmd).

## Overview

Demonstrates a complete workflow for identifying and estimating heterogeneous treatment effects using a simulated dataset (N=400, binary treatment, continuous outcome, 20 covariates).

**CATE Estimation:** S-Learner, T-Learner, X-Learner, Causal Forest (`grf`)

**Subgroup Identification:** Virtual Twins, Model-Based Recursive Partitioning (MOB), `personalized` package

**Subgroup Treatment Estimation:** Naive (unadjusted), Bootstrap (refit), Debiased Bootstrap

## Key Packages

`benchtm`, `grf`, `ranger`, `partykit`, `personalized`, `boot`

## Output

A rendered HTML walkthrough is included: [`code/Walkthrough-of-Heterogeneous-Treatment-Effects-Analysis.html`](code/Walkthrough-of-Heterogeneous-Treatment-Effects-Analysis.html)
