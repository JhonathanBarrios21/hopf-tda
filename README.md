# Hopf bifurcation detection using Topological Data Analysis

## Paper

This repository contains the code and data supporting the paper:

**"Topological Detection of Hopf Bifurcations via Persistent Homology: A Functional Criterion from Time Series"**

Jhonathan Barrios, Yásser Echávez, Carlos F. Álvarez (2026, submitted)

Preprint available at:  *[http://arxiv.org/abs/2603.27395]*

---

## Overview

This repository provides the computational framework used to study the detection of Hopf bifurcations from time series using Topological Data Analysis (TDA).

The proposed methodology follows the pipeline:

**Time series → Takens embedding → Persistent homology → Topological summaries → Detection**

---

## Main contribution

We introduce a topological criterion based on maximum persistence:

H(μ) = max(d - b)

which captures the emergence of a dominant one-dimensional homological class associated with oscillatory dynamics.

---

## Repository contents

### Dynamical systems

- Normal form of Hopf bifurcation  
- Lorenz system  
- Belousov–Zhabotinsky reaction model  

### Topological analysis

- Persistence diagrams  
- Maximum persistence  
- Betti curves (L1 norm)  

### Additional analysis

- Correlation with Lyapunov exponents  
- Robustness under noise  

---

## Reproducibility

All numerical experiments and figures from the paper can be reproduced using the provided notebooks.

The recommended execution order is:

1. `01_normal_hopf.ipynb`
2. `02_lorenz.ipynb`
3. `03_bz_reaction.ipynb`
4. `04_lyapunov_correlations.ipynb`

---

## Requirements

To run the notebooks, install the required Python packages:

```bash
pip install -r requirements.txt

---

## Citation
If you use this repository, please cite:

@article{barrios2026hopf_tda,
  title={A Topological Criterion for Detecting Hopf Bifurcations from Time Series},
  author={Barrios, Jhonathan and Echávez, Yásser and Álvarez, Carlos F.},
  year={2026}
  note ={arXiv preprint arXiv:},
  eprint= {},
  archiveprefix= {arXiv},
  primaryclass = {math.DS},
  URL = {https://arxiv.org/abs/},
}

## Status
This repository is under active development and may be updated as the paper evolves.
