# QFlowEDA

## Overview

QFlowEDA is a data analysis and machine learning toolkit designed for efficient processing and modeling of crop-related datasets. The project provides modules for data cleaning, preparation, and machine learning workflows, supporting both full-featured and lightweight usage.

## Features

- **Data Processing:**  
  Tools for cleaning, transforming, and preparing crop data for analysis.

- **Machine Learning Preparation:**  
  Scripts and modules to facilitate training and evaluation of ML models on agricultural datasets.

- **Modular Design:**  
  Core functionality in the `QFlow` package, with a streamlined version in `QFlow-lite` for rapid prototyping and experimentation.

- **Jupyter Notebooks:**  
  Interactive notebooks for data processing and model training.

## Directory Structure

- `QFlow/`  
  Core Python modules for data processing and ML preparation:
  - `config.py` — Configuration settings
  - `Crop_Data.py` — Crop data handling
  - `Prepare_ML.py` — ML data preparation
  - `Process_Data.py` — Data processing utilities

- `QFlow-lite/`  
  Lightweight version with:
  - Notebooks for data processing and ML training
  - `QFlow_class.py` — Simplified class-based interface
  - `Data/` — Sample datasets

- `README.md`  
  Project documentation.

- `.gitignore`  
  Git tracking settings.


## Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/Astraflaneur/QFlowEDA/
   ```
2. **Install dependencies:**  
   Ensure you have Python 3.x and required packages (see notebook headers or requirements in scripts).

3. **Explore the notebooks:**  
   Open `QFlow-lite/Data processing.ipynb` and `QFlow-lite/QFlow training.ipynb` for interactive examples.

4. **Use the modules:**  
   Import and use classes/functions from `QFlow/` for custom data workflows.

## License

See `QFlow-lite/LICENSE.txt` for details.

#### References
1. S.S. Kalantre, J.P. Zwolak, S. Ragole, X. Wu, N.M. Zimmerman, M.D. Stewart, and J.M. Taylor. [Machine learning techniques for state recognition and auto-tuning in quantum dots.](https://doi.org/10.1038/s41534-018-0118-7) *npj Quantum Inf.* **5**, 6 (2019).
2. J.P. Zwolak, S.S. Kalantre,  X. Wu, S. Ragole, and J.M. Taylor. [QFlow lite dataset: A machinelearning approach to the charge states in quantum
dot experiments.](https://doi.org/10.1371/journal.pone.0205844) *PLoS ONE* **13**(10): e0205844 (2018).
3. J.P. Zwolak, T. McJunkin, S.S. Kalantre, J.P. Dodson, E.R. MacQuarrie, D.E. Savage, M.G. Lagally, S.N. Coppersmith, M.A. Eriksson, and J.M. Taylor. [Autotuning of Double-Dot Devices In Situ with Machine Learning.](https://link.aps.org/doi/10.1103/PhysRevApplied.13.034075)
*Phys. Rev. Applied* **13**(3), 034075 (2020).
4. J.P. Zwolak, S.S. Kalantre, T. McJunkin, B.J. Weber, and J.M. Taylor. Ray-based classification framework for high-dimensional data. [arXiv:2010.00500](https://arxiv.org/abs/2010.00500) (2020).
5. J.P. Zwolak, T. McJunkin, S.S. Kalantre, S.F. Neyens, E. R. MacQuarrie, M.A. Eriksson, and J.M. Taylor. [Ray-based framework for state identification in quantum dot devices.](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.020335) *PRX Quantum* **2**(2), 020335 (2021).
6. J. Ziegler, T. McJunkin, E.S. Joseph, S.S. Kalantre, B. Harpt, D.E. Savage, M.G. Lagally, M.A. Eriksson, J.M. Taylor, and J.P. Zwolak. Toward Robust Autotuning of Noisy Quantum Dot Devices. [arXiv:2108.00043](https://arxiv.org/abs/2108.00043) (2021).
