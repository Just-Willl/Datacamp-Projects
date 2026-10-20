# Hypothesis Testing in Healthcare Drug Safety

Compare adverse effects and age distributions between drug and placebo groups in a modified trial dataset.

## Approach

A two-proportion z-test, chi-square independence test, distribution plots and a Mann–Whitney U test.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [drug_safety.csv](drug_safety.csv)

## Outputs

`two_sample_p_value`, `num_effects_p_value` and `age_group_effects_p_value`.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab numpy pandas statsmodels pingouin seaborn matplotlib
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The notebook is a statistical learning exercise using the supplied modified dataset.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
