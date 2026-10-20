# Clustering Antarctic Penguin Species

Group Antarctic penguins using physical measurements and sex without species labels.

## Approach

Dummy encoding, standardisation, an inertia comparison and K-means clustering with six clusters.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [penguins.csv](penguins.csv)

## Outputs

Cluster assignments, diagnostic plots and a `stat_penguins` table of cluster means.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas matplotlib scikit-learn
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

Clusters describe groups in the measurements; they are not verified species labels. Random initialisation can change results.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
