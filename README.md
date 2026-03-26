# Hopf bifurcation detection using Topological Data Analysis
## Paper
This repo contains a codebase for the paper

"A Topological Criterion for Detecting Hopf Bifurcations from Time Series"

by Jhonathan Barrios, Yásser Echávez and Carlos F. Álvarez. submitted (2026) 

Preprint can be find in arXiv:

## Overview

This repository contains the code, data, and notebooks supporting the study of Hopf bifurcation detection from time series using Topological Data Analysis (TDA).

The methodology is based on the following pipeline:

Time series → Takens embedding → Persistent homology → Topological summaries → Detection

## Main contribution

We propose a topological criterion based on maximum persistence:

H(μ) = max(d - b)

which captures the emergence of a dominant 1-dimensional homological class associated with oscillatory behavior.

## Contents

- Dynamical systems:
  - Normal form of Hopf bifurcation
  - Lorenz system
  - Belousov–Zhabotinsky reaction model

- Topological analysis:
  - Persistence diagrams
  - Maximum persistence
  - Betti curves (L1 norm)

- Additional analysis:
  - Correlation with Lyapunov exponents
  - Noise robustness

## Reproducibility

The repository is organized to reproduce all numerical experiments and figures from the paper.

## Status

🚧 Work in progress — repository under construction
