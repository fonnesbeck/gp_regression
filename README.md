# A Primer on Gaussian Processes for Regression Analysis 

**PyData NYC 2019**

## Description

Gaussian processes are flexible probabilistic models that can be used to perform Bayesian regression analysis without having to provide pre-specified functional relationships between the variables. This tutorial will introduce new users to specifying, fitting and validating Gaussian process models in Python.

## Abstract

Nowadays, there are many ways of building data science models using Python, including statistical and machine learning methods. I will introduce probabilistic models, which use Bayesian statistical methods to quantify all aspects of uncertainty relevant to your problem, and provide inferences in simple, interpretable terms using probabilities. A particularly flexible class of probabilistic models uses Bayesian non-parametric methods, which allow models to vary in complexity depending on how much data are available. In doing so, they avoid the over-fitting that is common in machine learning and statistical modeling. I will demonstrate the basics of Bayesian non-parametric modeling in Python. Specifically, I will introduce Gaussian processes (GP), and show how they can be applied to regression analysis using a few examples.

## Outline

1. Regression models: the basics (10 min)
    - What’s the usual approach to regression, and what are its limitations?
2. Introduction to probabilistic modeling (15 min)
    - How can you model complex things using a Gaussian (normal) distributions?
3. What is a Gaussian process? (20 min)
    - An overview of the features and properties of Gaussian processes.
4. Building Gaussian process models (20 min)
    - Selecting your covariance function to suit your problem.
5. Fitting Gaussian process models (15 min)
    - How you fit your GP depends on what you need it to do, and how much data you have.
6. Model checking and prediction (10 min)
    - Does my GP work as advertised? What can I do with it?
