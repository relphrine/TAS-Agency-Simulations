# The Geometry of Agency: Numerical Simulations

This repository contains the Python source code and Jupyter Notebooks required to reproduce the numerical simulations, topological data models, and figures presented in the manuscript *[Insert Your Paper Title Here]*.

## Overview

The computational framework models intentional agency as a non-Abelian holonomy within a principal bundle geometry. The simulations explicitly demonstrate the thermodynamic and topological constraints of agency across three distinct failure modes (Hypotheses 1-3) using stochastic differential equations (Euler-Maruyama integration) and vector field analysis.

## Repository Structure

The notebooks are numbered sequentially and map directly to the figures in the manuscript:

* **`01_H1_Metric_Collapse.ipynb`** Simulates structural breakdown (Hypothesis 1). Contains the Euler-Maruyama integration of the intentional lifting mechanism versus zero-mean ergodic noise. *(Reproduces Figure 4)*
* **`02_H2_Metabolic_Exhaustion.ipynb`** Simulates temporal/metabolic exhaustion (Hypothesis 2). Models the dynamic depletion of the $\alpha$ coupling parameter and the resulting "wilting" of the motor trajectory. *(Reproduces Figure 5)*
* **`03_H3_Contextual_Failure.ipynb`** Simulates state-dependent contextual failure (Hypothesis 3). Models the boundary-crossing event where the trajectory exits the stable manifold, resulting in a sudden drop of intentional holonomy. *(Reproduces Figure 6)*
* **`04_Figure_1_Redraw.ipynb`** Generates the baseline theoretical geometry. Computes the 3D helical bundle structure and the quadratic metabolic premium curves ($\Delta\mathcal{E} \propto \alpha^2$). *(Reproduces Figure 1)*
* **`05_Figure_2_Stirring.ipynb`** Visualizes the Fokker-Planck state space. Computes the radial stochastic diffusion ($\mathbf{D}$) and the tangential probability flux ($\mathbf{J}_{ss}$) driven by the metabolic pump. *(Reproduces Figure 2)*

## Requirements

The simulations are built using standard scientific Python libraries. To run the notebooks locally, ensure you have the following installed:

```bash
pip install numpy matplotlib scipy
```

Alternatively, these notebooks can be uploaded and executed directly in Google Colab with zero configuration required.

## Usage

1. Clone this repository:
	```bash
	git clone [https://github.com/YourUsername/TAS-Agency-Simulations.git](https://github.com/YourUsername/TAS-Agency-Simulations.git)
	```
2. Launch Jupyter Notebook or JupyterLab:
	```bash
	jupyter notebook
	```
3. Open the desired .ipynb file and execute the cells sequentially to generate the high-resolution figures.

## License

MIT License