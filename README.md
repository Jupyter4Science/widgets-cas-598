# How the Little Jupyter Notebook Became a Web App: A Tutorial for
Making Your Code and Data More Accessible and Reusable

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

## Prerequisites

Prior exposure to ipywidgets and/or familiarity with object-oriented
programming is recommended. We review the basics of ipywidgets within
the first hour and quickly move on to more advanced design principles.

## Binder

There are two ways to access this tutorial. You can launch these
notebooks in a Binder environment by clicking the badge below. This
requires not extra installation on your part. Just click the link and
follow along.

<div>

[![](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nicole-brewer/jupyter-web-app-template/HEAD)

Binder

</div>

### How long will my Binder session last?

Binder will automatically shut down user sessions that have more than 10
minutes of inactivity (if you leave a jupyterlab window open in the
foreground, this will generally be counted as “activity”). Binder tries
to guarentee that active sessions will last up to 6 hours.

### What if my session shuts down during a break?

We will start from a fresh checkpoint after every break, so if your
Binder session ends, you can just restart a new session and the
beginning of the next section.

If you would like to run this tutorial locally on your own computer,
please follow the instructions below.

## Installation Instructions

1.  Clone this repository with `git clone jupyter-web-app-template`
2.  If you don’t have it already, you will need to [download and install
    Miniconda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)
3.  Run `conda env create -f environment.yml` to create a conda
    environment called `jupyter-web-application`
4.  Run `conda activate jupyter-web-application` to activate the conda
    environment
5.  Run `jupyter lab` to launch JupyterLab

## How to use

We will follow the notebooks in the tutorial sequentially, starting with
`00_getting_started.ipynb`. We will then transition to editing notebooks
in the `nbs` directory that contains a full web application. You will be
instructed when to do so from the numbered notebooks.
