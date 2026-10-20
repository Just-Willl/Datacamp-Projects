# Customer Analytics Preparing Data for Modeling

Prepare anonymised training-provider customer records for efficient storage and later modelling.

## Approach

Boolean conversions, smaller numeric types, nominal and ordered categorical types, and filtering by experience and company size.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [customer_train.csv](customer_train.csv)
- [hr-image-small.png](hr-image-small.png)

## Outputs

The cleaned and filtered `ds_jobs_transformed` DataFrame and dtype/memory inspection.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

This notebook prepares data; it does not train a job-change prediction model.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
