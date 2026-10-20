# Modeling Car Insurance Claim Outcomes

Identify the strongest single-feature logistic model for car insurance claims.

## Approach

Mean imputation, fitting one statsmodels logistic model per feature and comparing confusion-table accuracy.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [car.jpg](car.jpg)
- [car_insurance.csv](car_insurance.csv)

## Outputs

A `best_feature_df` containing the selected feature and its accuracy.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas numpy statsmodels
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The reported accuracy is calculated on the fitting data; it is not a held-out estimate.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
