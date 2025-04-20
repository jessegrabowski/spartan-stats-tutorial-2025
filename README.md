# Spartan Statistical Association PyMC Tutorial

This repository holds all the code and instructions used in the PyMC tutorial presented to the Spartan Statistical Association in April 2025

This tutorial covers the modern Bayesian modeling workflow. Specifically, it answers the question, "what is a Probabilistic Programming Language (PPL), and why should I care?". We will do a modeling project from start to finish, focusing on how to incrementally add complexity and check that the model is doing what we want expect.

The tutorial is written for complete beginners to Python and Bayesian statics, so "incidental" topics, such as different probability distributions, probability theory, algorithms, and numerical computation, will come up. But the focus will be 100% on how to interact with these as a practitioner. Indeed, the point of a PPL is to hide these details!

# Installation

There are several ways to get the included tutorial materials up and running. 

## Local Installation
To get everything installed locally, clone this repository with:

```bash
git clone https://github.com/jessegrabowski/spartan-stats-tutorial-2025.git
```

Included in the repository is an `environment.yaml` file, which can be used to set up an anaconda environment. To do this, change to the directory created by `git` and create the environment as follows:

```bash
cd spartan-stats-tutorial-2025
conda env create -f environment.yaml
conda activate spartan-pymc
```

## Run Notebooks on Colab

If you don't want a local installation (or if your laptop is a potato), you can easily run any of the notebooks in this repository in Google Colab. Each notebook contains A link to launch it in Colab. Alternatively, you can launch any notebook you find on github by changing the URL from `github.com/...` to `githubtocolab.com/...` 
