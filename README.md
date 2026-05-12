# Numerical Experiments for Adaptive Golden-Ratio Primal--Dual Algorithms

This repository contains the Python notebooks used for the numerical experiments in the paper

**“The Golden Ratio Primal--Dual Algorithm with Two New Stepsize Rules for Convex--Concave Saddle-Point Problems”**  
by **Santanu Soe, Matthew K. Tam, and V. Vetrivel**.

The paper is available on arXiv:  
[https://arxiv.org/abs/2502.17918](https://arxiv.org/abs/2502.17918)

## Overview

The notebooks in this repository reproduce the numerical experiments reported in the paper. The experiments evaluate adaptive and partially adaptive stepsize rules for golden-ratio primal--dual algorithms for convex--concave saddle-point problems.

The proposed methods build on the golden-ratio primal--dual algorithmic framework and are designed to reduce direct dependence on precomputed problem parameters. The experiments compare the proposed methods with several related primal--dual and adaptive algorithms, including variants of GRPDA, Condat--Vu, and aGRAAL. For the precise algorithm names and theoretical details, please refer to the paper.

## Applications

The numerical experiments cover the following problems:

- **LASSO**
- **Fused Lasso** with one-dimensional total variation regularization
- **GraphNet** on two-dimensional grid graphs
- **Sparse logistic regression** using LIBSVM datasets:
  - `a9a`
  - `ijcnn1`
  - `mushrooms`
- **Image inpainting** with TV--\(L_2\) regularization

Each application has a self-contained Jupyter notebook that can be used to reproduce the corresponding figures and numerical results.

## Requirements

The experiments are implemented in Python using standard scientific-computing libraries such as:

- `numpy`
- `scipy`
- `matplotlib`
- `scikit-learn`

Some notebooks may require additional packages depending on the specific experiment.

## Citation

If you use this code, please cite the paper:

```bibtex
@article{soe2025golden,
  title={The Golden Ratio Primal--Dual Algorithm with Two New Stepsize Rules for Convex--Concave Saddle-Point Problems},
  author={Soe, Santanu and Tam, Matthew K. and Vetrivel, V.},
  journal={arXiv preprint arXiv:2502.17918},
  year={2025}
}
