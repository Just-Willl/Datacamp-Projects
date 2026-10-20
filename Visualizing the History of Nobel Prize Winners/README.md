# Visualizing the History of Nobel Prize Winners

Explore Nobel Prize laureates from 1901 to 2023.

## Approach

Frequency counts, decade features, grouped proportions, first-recipient lookup and repeat-winner identification.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [Nobel_Prize.png](Nobel_Prize.png)
- [data/nobel.csv](data/nobel.csv)

## Outputs

Top gender/country, the leading US-born decade, the highest female-share decade/category, the first female laureate and repeat winners.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas seaborn numpy
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The notebook primarily uses tabular summaries; the title reflects the original DataCamp project.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
