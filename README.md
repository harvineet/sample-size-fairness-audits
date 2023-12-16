# Sample size calculations for fairness audits

Code for experiments in the paper
[A Brief Tutorial on Sample Size Calculations for Fairness Audits](https://arxiv.org/abs/2312.04745).

## Installation

Code is tested on Python 3.8.

Install Anaconda environment with pandas, numpy, matplotlib, joblib, scikit-learn, scipy

Install packages
> pip install folktables torch seaborn

## Datasets
Scripts automatically download and saves data for the ACS data in
a folder named `data`.

## Run instructions
Code to reproduce experiments is in `sample_sizes_calc.ipynb`.

## Acknowledgements
We use the excellent `folktables` package to query ACS data.
It is available at [folktables](https://github.com/socialfoundations/folktables).