# Predicting Credit Card Approvals

Build and tune a logistic regression classifier for credit-card applications.

## Approach

Missing-value replacement and imputation, dummy encoding, scaling, a train/test split and five-fold grid search.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [cc_approvals.data](cc_approvals.data)
- [credit_card.jpg](credit_card.jpg)

## Outputs

A confusion matrix, classification report, best parameters and test accuracy.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas numpy scikit-learn
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The notebook performs preprocessing before splitting the data; its scores should be interpreted with that limitation.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
