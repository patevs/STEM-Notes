---
date: 2018-12-30
lastmod: 2018-12-30
title: Project Jupyter
description: Introduction to Project Jupyter, Jupyter Notebook, and JupyterLab
slug: jupyter
authors: ["patevs"]
categories:
  - Tutorial
  - Jupyter
  - Python
  - Anaconda
tags:
  - engineering
  - introduction
  - installation
  - jupyter
  - jupyterlab
  - python2
  - python3
  - pip
  - pipenv
  - anaconda
  - conda
toc: true
---
## Installing Jupyter

[`Jupyter`](https://jupyter.org/) requires a prequisite of either [`Python`](https://www.python.org/) [version 2.7](https://www.python.org/downloads/release/python-2715/) or [version 3.3](https://www.python.org/downloads/) and greater. 

The recommended installation method is to use the [`Anaconda`](https://www.anaconda.com/download/) distribution which will install Python and Jupyter.

## Running Jupyter Notebook

Run the following command to run [`Jupyter Notebook`](https://jupyter-notebook.readthedocs.io/en/stable/)

```cmd
jupyter notebook
```

## Installing JupyterLab

[`JupyterLab`](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html) is the next-generation web-based user interface for Project Jupyter.

JupyterLab can be installed using either `conda`, `pip` or, `pipenv`.

#### conda

```cmd
conda install -c conda-forge jupyterlab
```

#### pip
```cmd
pip install jupyterlab
```

#### pipenv

```cmd
pipenv install jupyterlab
pipenv shell
```

## Running JupyterLab

JupyterLab can be run with the following command:

```cmd
jupyter lab
```

----
