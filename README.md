<p align="center">
  <img src='images/logo-blue.png'>
</p>

## Finch Studio
Finch Studio is an integrated modeling environment for pharmacometricians, clinical pharmacologists, data scientists, and other team members to visualize understand, develop, and organize PK/PD models and data.

## User Manual
https://docs.finchstudio.io

## Features

### Workbench and Model Notebook

* An advanced NONMEM code editor with syntax highlighting, error checking, code completion, documentation on hover, and code folding.
* Add, delete, edit, and duplicate (with final estimates) models, including as batch actions.
* Model descriptions, notes, tags, and color for model tracking and filtering.
* Display of key modeling results for all models (e.g., final objective function, significant digits, minimization status, etc.).
* Side-by-side comparison of results across models. 
* View code differences between models to aid in quality assurance.
* Built-in system console.
* Automatic creation of xpose formatted $TABLE records based on dataset covariates and model parameters.

### Interactive Visualizations

* Plots of the observed data 
  * Population observed data plots
  * Individual observed data plots
  * Covariate distribution and correlation plots
* Diagnostic plots
  * Individual fits
  * Residual diagnostic plots (CWRES vs Time, CWRES vs PRED, DV vs PRED, DV vs IPRED)
  * Post-hoc parameter distribution and correlation plots
  * Post-hoc parameters vs covariates

### Model Library 

Finch Studio currently has a library of > 100 different combinations of possible initial modeling templates. To generate an initial model template, different model features can be selected including dosing route, number of compartments, absorption model, clearance mechanism(s), parameterization (e.g., rate constants vs. semi-physiological terms, built-in ADVANS vs. differential equations), and statistical models for parameters and residual unexplained variability.
