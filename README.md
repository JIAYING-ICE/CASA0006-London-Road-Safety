# CASA0006-London-Road-Safety
This repository contains the coursework submission for **CASA0006 Data Science 
for Spatial Systems** (UCL CASA, 2025-2026).  

CASA0006 coursework: predicting road collision severity in London using STATS19 data  

## Research Question

Can road environment factors reliably predict the severity of road collisions 
in London, and which factors are the most influential drivers of serious or 
fatal outcomes?

## Data Sources

- **Primary**: UK Department for Transport STATS19 road safety data 
  (https://www.gov.uk/government/statistical-data-sets/road-safety-open-data)
- **Geographic scope**: Greater London (Metropolitan Police + City of London Police)
- **Temporal scope**: 2022 and 2023 calendar years
- **Auxiliary**: ONS Inner/Outer London Borough classification

## Repository Structure

- `notebook/coursework.ipynb` — main analysis notebook (submission)
- `data/processed/` — cleaned, London-filtered datasets read remotely by the notebook
- `docs/data_dictionary.md` — variable-level documentation

## How to Run

1. Open `notebook/coursework.ipynb` in Jupyter
2. Run "Restart & Run All"
3. Expected execution time: under 30 minutes on a standard laptop

## Environment

- Python 3.10+
- Libraries: pandas, numpy, geopandas, scikit-learn, matplotlib, seaborn, shap, imbalanced-learn

## Author

Jiaying Li, MRes Urban Spatial Science, CASA, UCL
