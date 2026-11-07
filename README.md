# DSCI 552 - Homework 6

APS Failure at Scania Trucks data set: median imputation, coefficients of variation,
correlations, and tree ensembles on a heavily imbalanced problem. A random forest with
no compensation, a class-weighted and a balanced random forest, an L1-penalized XGBoost
model with alpha chosen by cross-validation, and XGBoost with SMOTE applied inside each
training fold. Written answers to ISLR 6.6.3, 6.6.5, 8.4.5 and 9.7.3.

Name: Mohammad Hasnain Raza
GitHub Username: hasnainrazaa03
USC ID: 1259246355

## Structure

```
data/aps_failure/   aps_failure_training_set.csv, aps_failure_test_set.csv, aps_failure_description.txt
notebook/           Raza_MohammadHasnain_HW6.ipynb
requirements.txt    package versions used
```

## Running the notebook

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cd notebook
jupyter notebook Raza_MohammadHasnain_HW6.ipynb
```

The notebook reads the data with relative paths such as `../data/aps_failure/aps_failure_training_set.csv`,
so it runs from the `notebook` folder without any change. A full run takes a few minutes.
