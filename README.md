# Side-by-Side Comparison of Variant Function Measurements Using Deep Mutational Scanning and Base Editing

This repository provides the code and data necessary to reproduce the analysis and figures presented in the publication on [BioArxiv](https://www.biorxiv.org/content/10.1101/2024.06.30.601444v2) comparing variant function measurements obtained through deep mutational scanning and base editing. We are committed to transparency and reproducibility, and this repository facilitates independent validation of our findings.

## Project Overview

The repository is organized by figure, with each folder corresponding to a specific figure from the publication. Inside each folder, you will find the data and Jupyter Notebook(s) required to recreate the analysis and generate the corresponding figure. **Before running a notebook, please ensure that you set the working directory within the notebook to the location of the data files within that figure's folder.**

## Data Availability

* **Sequencing Data:** Raw sequencing data is available for download from the Sequence Read Archive (SRA) under BioProject accession number **PRJNA1218278**.

* **Read Counts:** For convenience, we have also included pre-calculated read counts for each sample within their respective figure folders. This allows users to reproduce the analysis without processing the raw sequencing data if desired.


## Dependencies


This project uses different Python versions and packages depending on the figure being generated. Please ensure you have the correct versions and dependencies installed before running the scripts.  It is highly recommended to use a virtual environment to manage these dependencies and avoid conflicts.


**Python Versions:**

* **Figures 1, 2, 3, and 4:** Python 3.10.12
* **Figure 3F (BE-HIVE):** Python 3.7.  You also need to download and install the BE-HIVE model separately from
  [https://github.com/maxwshen/be_predict_efficiency](https://github.com/maxwshen/be_predict_efficiency)

**Required Packages:**

The `requirements.txt` file, located above, lists the necessary Python packages for most figures in this project. You can install these packages using pip:

```bash
pip install -r requirements.txt
