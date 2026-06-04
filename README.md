# XGBoost_pCO2_IO

This repository contains scripts to build XGBoost models, perform statistical analysis, and create figures. 

## Repository Structure

The repository includes the following scripts:

1. **`Figures_and_Statistics.ipynb`**
   - A Jupyter Notebook for generating visualizations and performing statistical analyses.
   - Designed to produce high-quality plots and calculate key statistics for validation.

2. **`XGBoost_model.ipynb`**
   - A Jupyter Notebook for building and evaluating XGBoost models. A similar code is applied to the four subregions individually.

## Requirements

The scripts require Python 3.7 or later. Install the necessary dependencies using:

```bash
pip install -r requirements.txt
```

### Key Libraries
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `xgboost`
- `sklearn`
- `xarray`
- `xskillscore`

## Usage

### Figures and Statistics
To generate figures and perform statistical analyses, use the `Figures_and_Statistics.ipynb` notebook. Open the notebook in Jupyter and update the input file paths and datasets as needed and load the necessary libraries.

Run the notebook:

```bash
jupyter notebook figures_statistics.ipynb
```

### XGBoost Models
To build and evaluate XGBoost models, use the `XGBoost_model.ipynb` notebook. Ensure that the input data file paths and model parameters are set appropriately in the notebook.

Run the notebook:

```bash
jupyter notebook xgb_models.ipynb
```
### Contributors
Prasanna Kanti Ghoshal and Apurva P Joshi
