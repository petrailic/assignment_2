# Firm Fast Growth Predictoin

**Authors:** Elsa Andrea Rodriguez Canales, Petra Ilic  
**Date:** February 15, 2026

## The Task
The objective of this project is to build a model to predict fast growth of firms using the bisnode-firms data.

## Project Folder Structure
```
.
├── data
│   ├── clean
│   │   └── bisnode_firms_clean.csv
│   ├── raw
│   │   ├── cs_bisnode_panel.csv
│   │   └── cs_bisnode_panel.zip
│   └── work5.csv
├── environment.yml
├── firm_growth_data_prep.ipynb
├── py_helper_functions.py
├── README.md
├── task_1_pred_and_class.ipynb
└── task_2_pred_and_class.ipynb
```

## How to Run

### Requirements
How to get the development/analysis environment running with conda:

```
conda env create -f environment.yml
conda activate pred_env
```

### Main Dependencies
* **Python** 3.13
* **pandas** - data manipulation and analysis
* **scikit-learn** - machine learning tools
* **matplotlib** - plotting and visualization
* **seaborn** - plotting and visualization

### Execution
 **Data Preparation:** Run the `firm_growth_data_prep.ipynb` jupyter notebook in full.
  **Predictions and Analysis:** Run the `task_1_pred_and_class.ipynb` and `task_1_pred_and_class.ipynb` jupyter notebooks in full. 