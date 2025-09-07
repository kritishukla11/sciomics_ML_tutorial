# Machine Learning with DepMap & CCLE Tutorial

This repository contains a tutorial developed for the **UNC Sciomics Initiative** on applying
machine learning to DepMap and CCLE data. The notebooks guide participants through
installation, data exploration, and applying ML models for biological insights.

---

## Repository Structure

    .
    ├── MachineLearningWithDepMapCCLE.ipynb   # Main tutorial notebook
    ├── RUNFIRST_packageinstall.ipynb         # Environment setup helper
    ├── data/                                 # Example datasets
    └── environment.yml                       # Conda environment specification

---

## Getting Started

### 1. Clone the repository
    git clone https://github.com/<your-username>/sciomics-ml-tutorial.git
    cd sciomics-ml-tutorial

### 2. Create the conda environment
    conda env create -f environment.yml
    conda activate sciomics-ml

### 3. Run the tutorial
Launch Jupyter and open the notebooks:

    jupyter notebook

- Start with `RUNFIRST_packageinstall.ipynb` to ensure dependencies are installed.
- Then proceed to `MachineLearningWithDepMapCCLE.ipynb`.

---

## Requirements
- Python 3.9+
- Conda or mamba for environment management
- Jupyter Notebook / JupyterLab


---

## Acknowledgments
Developed as part of the **UNC Sciomics Initiative** training series.
