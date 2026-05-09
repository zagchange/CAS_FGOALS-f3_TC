# CAS_FGOALS-f3_TC

CAS FGOALS-f3 tropical cyclone simulations and analysis workflows.

---

## Overview

This repository contains the data, scripts, figures, and supplementary materials associated with the study:

> "Advancing Towards Grey Zone: Evaluation of Tropical Cyclones in Key Basins with the 12.5 km High Resolution CAS FGOALS-f3 Model"

The repository includes processing workflows, tropical cyclone tracking analyses, visualization scripts, and processed outputs used in the study.

---

## Project Structure

- `Data/` : Input data required for the analysis  
- `Figure/` : Generated output figures  
- `Script/` : Jupyter notebooks and analysis scripts  
- `Table/` : Generated output tables  
- `python_environment.yml` : Conda environment specification  
- `requirements.txt` : Python package requirements  

---

## Supplementary Materials

Supplementary materials are identified using the prefix `S`.

Examples include:

- `S5_Inter-annual variability of the number of TCs.ipynb`
- `Tab_S1_Peak Category [Exclusive].ipynb`
- `S6_Composite of Precipitation and Wind-ERA5.pdf`

---

## Environment Setup

Create the conda environment:

```bash
conda env create -f python_environment.yml
```

Activate the environment:

```bash
conda activate project_env
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Usage

Execute notebooks in the `Script/` directory in numerical order.

- Main analysis outputs are saved in `Figure/`
- Supplementary outputs use the prefix `S_`

Update directory paths in notebooks if necessary to match local data locations.

---

## Data Availability

The original observational and reanalysis datasets used in this study are publicly available from their respective providers.

Processed outputs, analysis scripts, and supplementary materials associated with this repository are archived through Zenodo.

---

## License

This repository is distributed under the MIT License.
