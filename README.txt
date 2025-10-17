Overview
This repository contains the data, scripts, and figures for the analysis presented in the paper "Advancing Towards Grey Zone: Evaluation of Tropical Cyclones in Key Basins with the 12.5 km High Resolution IAP-CAS (FGOALS-f3) Model".

Project Structure
- Data/: Input data required for the analysis
- Figures/: All generated output figures
- Scripts/: Jupyter notebooks for processing, analysis, and visualization
- python_environment.yml: Conda environment specification (Python 3.10.9)

Note: Supplementary materials are prefixed with S_ (e.g., S3_Inter-annual_variability.ipynb).

Environment Setup
1. Create environment:
   conda env create -f python_environment.yml

2. Activate environment:
   conda activate project_env

3. Launch Jupyter:
   jupyter notebook

Usage
- Execute notebooks in Scripts/ directory in numerical order
- Main results are saved to Figures/
- Supplementary results use S_ prefix in both Scripts/ and Figures/