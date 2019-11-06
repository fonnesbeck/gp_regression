# A Primer on Gaussian Processes for Regression Analysis 

**PyData NYC 2019**

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fonnesbeck/gp_regression/master)

## Description

Gaussian processes are flexible probabilistic models that can be used to perform Bayesian regression analysis without having to provide pre-specified functional relationships between the variables. This tutorial will introduce new users to specifying, fitting and validating Gaussian process models in Python.

## Abstract

Nowadays, there are many ways of building data science models using Python, including statistical and machine learning methods. I will introduce probabilistic models, which use Bayesian statistical methods to quantify all aspects of uncertainty relevant to your problem, and provide inferences in simple, interpretable terms using probabilities. A particularly flexible class of probabilistic models uses Bayesian non-parametric methods, which allow models to vary in complexity depending on how much data are available. In doing so, they avoid the over-fitting that is common in machine learning and statistical modeling. I will demonstrate the basics of Bayesian non-parametric modeling in Python. Specifically, I will introduce Gaussian processes (GP), and show how they can be applied to regression analysis using a few examples.

## Outline

1. Regression models: the basics 
    - What’s the usual approach to regression, and what are its limitations?
2. Introduction to probabilistic modeling
    - How can you model complex things using a Gaussian (normal) distributions?
3. What is a Gaussian process? 
    - An overview of the features and properties of Gaussian processes.
4. Building Gaussian process models
    - Selecting your covariance function to suit your problem.
5. Fitting Gaussian process models
    - How you fit your GP depends on what you need it to do, and how much data you have.
6. Model checking and prediction
    - Does my GP work as advertised? What can I do with it?

## Setup

This tutorial assumes that you have [Anaconda](https://www.anaconda.com/distribution/#download-section) (Python 3.6 or greater) setup and installed on your system. If you do not, please download and install Anaconda on your system before proceding with the setup.

The next step is to clone or download the tutorial materials in this repository. If you are familiar with Git, run the clone command:

    git clone https://github.com/fonnesbeck/gp_regression.git
    
otherwise you can [download a zip file](https://github.com/fonnesbeck/gp_regression/archive/master.zip) of its contents, and unzip it on your computer.
***
The repository for this tutorial contains a file called `environment.yml` that includes a list of all the packages used for the tutorial. If you run:

    conda env create
    
from the main tutorial directory, it will create the environment for you and install all of the packages listed. This environment can be enabled using:

    conda activate gp_tutorial
    
Then, you can start **JupyterLab** to access the materials:

    jupyter lab