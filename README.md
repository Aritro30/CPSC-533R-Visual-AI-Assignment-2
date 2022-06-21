# Development Environment Setup

We encourage all students to use the Conda package management for a better environment manegement. The Conda installation can be found here https://www.anaconda.com/products/individual.

## Create environment

The default environment usually have too many pre-installed packages, which may conflict the packages we want to install. Therefore, we create a brand new environment by the following command:

```
conda create -n cs533r python=3.8
```

This command creates a Python3.8 environment named `cs533r`.

Then we can use the command 

```
conda activate cs533r
```

to activate `cs533r` environment.

## Install Packages

We have included all packages needed in `requirements.txt`. You can use

```
conda install --file requirements.txt
```

to automatically install all required packages.

## Open JupyterLab

As our assignments are written in Jupyter, we use

```
jupyter lab
```

to open the jupyter lab in our browser.
