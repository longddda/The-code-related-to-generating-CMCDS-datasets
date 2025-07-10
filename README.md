# CMCDS dataset: Comprises computed ECD spectral data for over 10,000 chiral organic small molecules

## Overview

This repository contains a complete pipeline for generating and analyzing ECD (Electronic Circular Dichroism) spectra of molecules using Gaussian input and output files.

The workflow includes:
- Converting SMILES strings to `.mol` structure files
- Generating `.gjf` input files for Gaussian
- Optimizing molecular structures and extracting key data from `.log` files
- Plotting ECD spectra from Gaussian calculation outputs

---

## Required Software

To run the notebooks and scripts in this repository, the following software and libraries are required:

- Python 3.8+
- Jupyter Notebook
- RDKit
- NumPy
- pandas
- matplotlib

## How to Reproduce the Results

1. **Clone the repository**:

```
git clone https://github.com/yourusername/The-code-related-to-generating-CMCDS-datasets.git
cd The-code-related-to-generating-CMCDS-datasets/code
```

2. **Place your input files:** 

- SMILES strings in `.csv`
- `.mol` files in `mol_file/`
- Gaussian input files in `gjf_opt/`
- Gaussian output files in `opt_log/` or `ecd_log/`

3. **Run the Jupyter notebooks in order:**

- `1.convert the molecule's SMILES to a MOL file.ipynb`
- `2.convert from .mol file to .gjf file.ipynb`
- `3.convert a .log file to an ECD .gjf file.ipynb`
- `4.convert an ECD .log file into an ECD spectrum.ipynb`

4. The generated `.gjf` files and ECD plots will be stored in the corresponding folders.

## File Structure

```
The-code-related-to-generating-CMCDS-datasets/
├── code/
│   ├── ecd_gjf/
│   ├── ecd_log/
│   ├── gjf_opt/
│   ├── mol_file/
│   ├── opt_log/
│   ├── 1.convert the molecule's SMILES to a MOL file.ipynb
│   ├── 2.convert from .mol file to .gjf file.ipynb
│   ├── 3.convert a .log file to an ECD .gjf file.ipynb
│   ├── 4.convert an ECD .log file into an ECD spectrum.ipynb
│   └── test_natural_product_molecules.csv
├── README.md   
```

## File Format Descriptions

- `.smiles` – SMILES strings input
- `.mol` – Molecular structure files
- `.gjf` – Gaussian input files
- `.log` – Gaussian output files
- `.ipynb` – Jupyter notebook
- `.csv` – Tabular data input
- `.png` / `.pdf` – Spectrum output plots

## License




