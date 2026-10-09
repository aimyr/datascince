# Tabular classification — data science coursework

An exploratory machine-learning notebook comparing classifiers on a dataset with a binary `diabetes` label. The work includes data cleaning, categorical encoding, model comparison, XGBoost hyperparameter tuning, and prediction export.

## Repository contents

| File | Purpose |
| --- | --- |
| [Aimer_PO2.ipynb](Aimer_PO2.ipynb) | Analysis, preprocessing, training, and evaluation notebook |
| `training_data.csv` | Training data used by the notebook |
| `test_data.csv` | Data used for prediction export |
| `answer.csv` | Saved prediction output |
| `model_v1.pkl` | Saved model artifact |

## Reading and reproducing the work

Open the notebook in Jupyter and keep the CSV files in the same working directory. The notebook imports pandas, NumPy, scikit-learn, Matplotlib, seaborn, XGBoost, LightGBM, and Optuna, among other libraries. It does not include a pinned environment specification.

The notebook explores several train/test splits and both binary and weighted metrics. Saved outputs should be treated as exploratory results until the notebook has been rerun from a clean environment and a single evaluation protocol has been established. No new performance result is claimed by this README.

## Dataset and project status

This is an educational classification exercise, not a clinically validated diagnostic tool. The original dataset source and redistribution terms are not documented in this repository; those details need to be established before treating the files as a reusable dataset release.
