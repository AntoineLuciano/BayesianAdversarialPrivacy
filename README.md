# BayesianAdversarialPrivacy

# Bayesian Adversarial Privacy (BAP)

This repository contains the code (Python/JAX notebooks) and figures accompanying the paper **"Bayesian Adversarial Privacy"**.

## Contents

### Notebooks
- `notebooks/01_coin_toss_final.ipynb`  
  Reproduces **Example 1 (Coin toss)**: integrated risks and plots.

- `notebooks/02_gaussian_JAX_final.ipynb`  
  Reproduces **Example 2 (Gaussian model, JAX)**: Cases 1–6, mean/max adversaries, integrated risks and figures.

### Figures
- `figures/paper/`  
  Figures used in the main manuscript (typically reporting $R_A$).

- `figures/supplementary/`  
  Additional diagnostics reported in the Supplementary Material (e.g. panels for $R_B$, $R_E$, and $R_A$).

Recommended naming scheme:
- Paper: `fig_sigma_mean_RA.pdf`, `fig_sigma_max_RA.pdf`, `fig_tau_mean_RA.pdf`, `fig_tau_max_RA.pdf`
- Supplementary: `fig_sigma_mean_all.pdf`, `fig_sigma_max_all.pdf`, `fig_tau_mean_all.pdf`, `fig_tau_max_all.pdf`

## Installation

### Option A — Conda (recommended)

```bash
conda env create -f environment.yml
conda activate bap
