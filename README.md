# HW8

This repository contains three Python scripts/notebooks for **Homework 8**, each illustrating a different Bayesian modeling approach using [PyMC](https://www.pymc.io/) and the attached datasets.

1. **Q1 (Bayesian Logistic Regression)**  
   Demonstrates a Bernoulli model with a logit link function for a single binary outcome using `diabetes_dataset.csv`.

2. **Q2 (Bayesian Multivariate Regression)**  
   Explores modeling multiple continuous outcomes jointly using an LKJ prior for the covariance, applied to `Persistent_vs_NonPersistent.csv`.

3. **Q3 (Bayesian Multivariate Classification)**  
   Models multiple correlated binary outcomes via latent variables and an LKJ prior on their covariance, also using `Persistent_vs_NonPersistent.csv`.

Two datasets are included:
- `diabetes_dataset.csv`
- `Persistent_vs_NonPersistent.csv`

Please see the individual question scripts for full details on data preprocessing, model specification, and posterior inference.
