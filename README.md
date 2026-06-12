# CIR Yield-Curve Prediction

This repository contains a Google Colab/Jupyter notebook for predicting a zero-coupon yield curve from the observed 3M yield using a CIR baseline and CIR++ extension.

## Files

- `src.ipynb`: final notebook for submission
- `cir_predictions.csv`: generated yield-curve predictions

## Reported R2 Values

- Baseline CIR: `0.859965`
- CIR++ extension: `0.890852`
- CIR++ extension with known 3M anchor: `0.922311`

Run `src.ipynb` from top to bottom. The notebook uses relative paths, so it works when the repository structure is kept unchanged.
