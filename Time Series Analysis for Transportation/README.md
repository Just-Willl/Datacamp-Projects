# Time Series Analysis for Transportation

Estimate simultaneous team flights and forecast fuel expenditure for a fictional sporting league's 2102 season.

## Approach

Departure/arrival event counting, time series decomposition, ACF/PACF and stationarity checks, SARIMAX forecasting and joining flight costs.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [CONFIG.JSON](CONFIG.JSON)
- [baseball_flights.png](baseball_flights.png)
- [fuel_prices_2101.csv](fuel_prices_2101.csv)
- [team_flights.csv](team_flights.csv)

## Outputs

`max_teams_in_flight` and `total_fuel_spend_2102_dollars`.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas numpy statsmodels matplotlib pmdarima
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

Dates and costs belong to the fictional project scenario. The original notebook imports pmdarima even though its final forecast uses statsmodels.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
