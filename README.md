# README.md - `jupyter_demos`

This repository contains sample Jupyter notebooks for demonstrations.

## Installation

Create a new `conda` environment

```bash
conda env create -f environment.yml
```

Activate the environment

```bash
conda activate jupyter_demos
```

Start `R`

```bash
$ R

R version 3.5.1 (2018-07-02) -- "Feather Spray"
Copyright (C) 2018 The R Foundation for Statistical Computing
Platform: x86_64-apple-darwin13.4.0 (64-bit)

R is free software and comes with ABSOLUTELY NO WARRANTY.
You are welcome to redistribute it under certain conditions.
Type 'license()' or 'licence()' for distribution details.

  Natural language support but running in an English locale

R is a collaborative project with many contributors.
Type 'contributors()' for more information and
'citation()' on how to cite R or R packages in publications.

Type 'demo()' for some demos, 'help()' for on-line help, or
'help.start()' for an HTML browser interface to help.
Type 'q()' to quit R.
```

At the `R` prompt, install the `IRkernel` package

```R
install.packages("IRkernel")
IRkernel::installspec()
```

Exit `R`, then start the notebook server

```bash
jupyter notebook
```

## Binder

Run this repository on Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/widdowquinn/jupyter_demos/master)