# Exploring NYC Public School Test Result Scores

Explore New York City public-school SAT performance.

## Approach

Filtering strong maths scores, calculating combined SAT totals, ranking schools and aggregating borough statistics.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [schoolbus.jpg](schoolbus.jpg)
- [schools.csv](schools.csv)

## Outputs

`best_math_schools`, `top_10_schools` and `largest_std_dev`.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The analysis uses the supplied school-level averages.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
