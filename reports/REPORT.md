## Quickstart

### 1) Set up
- Install Anaconda or Miniconda
- Create env from file  
  `conda env create -f environment.yml`  
  `conda activate tfhealth`

### 2) Data
- Put CMAPSS files into `data/raw/`  
  Example: `train_FD001.txt`, `test_FD001.txt`, `RUL_FD001.txt`

### 3) Reproduce results
- Run notebooks in order:
  1. `01_ingest_and_standardize.ipynb`
  2. `02_eda.ipynb`
  3. `03_feature_engineering.ipynb`
  4. `04_labeling.ipynb`
  5. `05_train_test_split.ipynb`
  6. `06_prepare_baselines.ipynb`
  7. `07_evaluate_results.ipynb`

Outputs go to `reports/` and `reports/figs/`.