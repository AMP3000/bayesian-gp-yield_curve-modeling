# Bond Yield Curve Modeling with Bayesian Gaussian Processes

[![Python](https://img.shields.io/badge/python-3.13-blue)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

This repository uses Bayesian Gaussian Processes to model municipal bond yield curves. Municipal bonds are often overlooked compared to other types of bonds and are usually modeled with deterministic models that perform even worse given the sparse data. This project demonstrates how Bayesian Gaussian Process Regression can be applied to uncover yield curve dynamics and inherent uncertainty even with limited data.

The approach generalizes to other fixed-income instruments and bond datasets beyond municipal bonds.

## 🔍 Notebook Overview

Data from [EMMA Website](https://emma.msrb.org/)

- **Bayesian Gaussian Process Regression (GP):** Flexible nonparametric modeling of bond yield curves  
- **Uncertainty Quantification:** Posterior distributions to capture predictive uncertainty  
- **Model Evaluation:** Includes train/test splits and Negative Log Predictive Density (NLPD)  
- **Comparative Analysis:** Functions to compare bond yield curves across issuers/sectors  
- **Visualization:** Matplotlib plots with confidence intervals, posterior samples, and test point markers


### Example of Models and Posterior Distributions:

![Alt Text](images/bayesian_model.png)
![Alt Text](images/posterior_distributions.png)

## ⚡ Getting Started

Install the required libraries using pip:

```bash
pip install numpy pandas matplotlib mplcyberpunk datetime scipy sklearn
```

Clone this repository 
Run through notebook cells to reproduce the analysis and plots


## Research Connection

This project was completed as a part of a Research for Undergraduates Program (REU). A research paper was written alongside the code to formalize the methodology and findings. 

🔗 [Research Paper](https://drive.google.com/file/d/1cYeYV2rkz7CBj5UKULra5SL2RA-PPwyO/view)
