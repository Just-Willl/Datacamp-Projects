# Cleaning Bank Marketing Campaign Data

Clean bank marketing records and separate them into client, campaign and economics tables.

## Approach

String normalisation, missing-value handling, boolean conversions, date construction and CSV export.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [bank_marketing.csv](bank_marketing.csv)
- [campaign.csv](campaign.csv)
- [client.csv](client.csv)
- [economics.csv](economics.csv)
- [piggy_bank.jpg](piggy_bank.jpg)

## Outputs

`client.csv`, `campaign.csv` and `economics.csv`, linked through `client_id`.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas numpy
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

Running the export cells overwrites the three included output CSVs.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
