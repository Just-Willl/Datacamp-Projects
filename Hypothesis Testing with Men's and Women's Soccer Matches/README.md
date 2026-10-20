# Hypothesis Testing with Men's and Women's Soccer Matches

Compare total goals in men's and women's FIFA World Cup matches from 2002 onwards.

## Approach

Filtering match records, constructing total goals, plotting distributions and a one-sided Mann–Whitney U test.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [men_results.csv](men_results.csv)
- [soccer-pitch.jpg](soccer-pitch.jpg)
- [women_results.csv](women_results.csv)

## Outputs

A `result_dict` containing the p-value and hypothesis-test decision.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas seaborn matplotlib scipy pingouin
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The original notebook calls `shapiro` without importing it. Its brief specifies 10% significance, while the decision cell uses 1%; these existing issues are preserved.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
