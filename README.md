# README.md - `jupyter_demos`

This repository contains sample Jupyter notebooks for demonstrations.

## Installation

1 - Create a new `conda` environment

```bash
conda env create -f environment.yml
```

2 - Activate the environment

```bash
conda activate jupyter_demos
```

3 - Link the `R` kernel to Jupyter in this environment

```bash
Rscript install.R
```

4 - Start the notebook server

```bash
jupyter notebook
```

### Removing the environment

Deactivate the environment, and use the `conda remove` command:

```bash
conda deactivate
conda remove --name jupyter_demos --all
```

## Binder

Run this repository on Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/widdowquinn/jupyter_demos/master)