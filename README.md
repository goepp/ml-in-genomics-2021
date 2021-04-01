# 2021-ml-in-genomics

Course material for the course *Machine Learning in Genomics*.

Includes slides of the lecture and the jupyter notebooks of the practical sessions.

## Installation

- Clone the repository `git clone https://github.com/goepp/ml-in-genomics-2021/`

- You need to download the heavy files `athaliana_small.X.txt` and `athaliana_small.W.txt` [here](https://plmbox.math.cnrs.fr/d/fcf6f52656a9451ead65/) and place them in `practical/data/`.

## Quick setup from scratch

You need python3 and jupyter notebook. An easy way to set it up from scratch is:

- Download [https://conda.io/en/master/miniconda.html](miniconda).

- Install Jupyter Notebook using conda: `conda install -c conda-forge notebook`.

- Create a conda environment: `conda create -n mlgen`

- Install modules: `conda install ipykernel seaborn pandas numpy sklearn matplotlib`

## Getting started

Run the jupyter notebook from within the conda env:
```
conda activate mlgen
jupyter notebook
```
And your notebook should open in a web browser.
