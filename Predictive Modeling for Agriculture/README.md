# Predictive Modeling for Agriculture

Compare individual soil measurements as predictors of crop type.

## Approach

Train/test splitting, single-feature multinomial logistic regression and weighted F1 scoring.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [farmer_in_a_field.jpg](farmer_in_a_field.jpg)
- [soil_measures.csv](soil_measures.csv)

## Outputs

A `best_predictive_feature` dictionary containing the strongest feature and its weighted F1 score.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab numpy pandas scikit-learn
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The split has no fixed random seed, so results may vary. The original `multi_class` argument may require a compatible scikit-learn release.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
