# CAS_FGOALS-f3_TC
CAS FGOALS-f3 TC simulations

Overview This repository contains the data, scripts, and figures for the analysis presented in the paper "Advancing Towards Grey Zone: Evaluation of Tropical Cyclones in Key Basins with the 12.5 km High Resolution CAS FGOALS-f3 Model".

Project Structure

Data/: Input data required for the analysis
Figure/: All generated output figures
Table/: All generated output tables
Script/: Jupyter notebooks for processing, analysis, and visualization
python_environment.yml: Conda environment specification (Python 3.10.9)

Note: Supplementary materials are prefixed with "S" 
(e.g., S5_Inter-annual variability of the number of TCs.ipynb, Tab_S1_Peak Category [Exclusive].ipynb, S6_Composite of Precipitation and Wind-ERA5.pdf).

Environment Setup

Create environment: conda env create -f python_environment.yml

Activate environment: conda activate project_env

Launch Jupyter: jupyter notebook

Usage

Execute notebooks in Scripts/ directory in numerical order
Main results are saved to Figures/
Supplementary results use S_ prefix in both Scripts/ and Figures/
