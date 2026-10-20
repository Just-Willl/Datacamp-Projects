# Exploring Airbnb Market Trends

Combine 2019 New York Airbnb listings from CSV, TSV and Excel files to summarise the rental market.

## Approach

Merging on listing IDs, parsing review dates, fuzzy matching room categories and cleaning price strings.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [data/airbnb_last_review.tsv](data/airbnb_last_review.tsv)
- [data/airbnb_price.csv](data/airbnb_price.csv)
- [data/airbnb_room_type.xlsx](data/airbnb_room_type.xlsx)
- [nyc.jpg](nyc.jpg)

## Outputs

A one-row `review_dates` DataFrame containing first/last review dates, private-room count and average listing price.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas numpy openpyxl thefuzz
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The summary describes the supplied historical listings.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
