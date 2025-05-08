# Final Project: Single Cell RNA-seq Analysis

# Paper 2 "Single cell transcriptomic analyses implicate an immunosuppressive tumor microenvironment in pancreatic cancer liver metastasis"

## 📁 Project Structure

- `data/`: Raw or unpacked case-specific expression data.
- `cache/`: Preprocessed `.h5ad` AnnData files.
- `figures/`: Output plots and visualizations.
- `results/`: Analytical results.
- `scanpy.ipynb`: Main analysis notebook.
- `notebook_env.yml`: Conda environment specification.
- `GSE197177_RAW.tar`: Raw data archive from GEO (if used).

## 🔧 Setup Instructions

```bash
conda env create -f notebook_env.yml
conda activate your_env_name
