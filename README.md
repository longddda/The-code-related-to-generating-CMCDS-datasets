# CMCDS dataset: Comprises computed ECD spectral data for over 10,000 chiral organic small molecules

## Overview

This repository contains code and data for ["CMCDS dataset: Comprises computed ECD spectral data for over 10,000 chiral organic small molecules"].

It includes scripts for:
- Converting SMILES to `.mol` files  
- Generating `.gjf` input files for Gaussian  
- Parsing `.log` output files  
- Extracting energy and rotatory strength data  
- Plotting ECD spectra  

---

## Required Software

To run the notebooks and scripts in this repository, the following software and libraries are required:

- Python 3.8+
- RDKit
- NumPy
- pandas
- matplotlib
- re (built-in)
- os (built-in)

You can install the required Python packages with:

```
pip install -r requirements.txt
```
## How to Reproduce the Results

1. **Clone the repository**:

```
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. **Place your input `.mol` or `.log` files** in the appropriate folders (see File Structure below).

3. **Run the main Jupyter notebooks or Python scripts** to:

Convert input files
Extract data
Generate ECD spectra

4. **Output plots and processed data** will be saved to the designated output folders.

## File Structure

```
your-repo-name/
├── data/                  # Contains input molecule files (.mol, .gjf, .log)
├── output/                # Output files such as spectra, parsed data
├── scripts/               # Python scripts for processing and analysis
├── notebooks/             # Jupyter Notebooks for interactive use
├── figures/               # Plotted results (e.g., ECD spectra)
├── requirements.txt       # Python dependencies
└── README.md              # This file
```

## File Format Descriptions

`.smiles` – Text files containing SMILES strings

`.mol` – Molecular structure files (2D/3D), used as Gaussian input

`.gjf` – Gaussian input files, generated from .mol

`.log` – Gaussian output files, containing calculated properties

`.csv` – Tabular data such as energy and rotatory strengths

`.png` / `.pdf` – Plots of generated spectra

## License




