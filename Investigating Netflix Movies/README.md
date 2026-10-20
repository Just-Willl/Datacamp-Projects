# Investigating Netflix Movies

Explore films released in the 1990s in a supplied Netflix catalogue dataset.

## Approach

Filtering by release year and title type, duration summaries, a histogram and counting short action films.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [netflix_data.csv](netflix_data.csv)
- [redpopcorn.jpg](redpopcorn.jpg)

## Outputs

The `duration` answer and `short_movie_count`.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas matplotlib
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

This is an analysis of the supplied catalogue snapshot.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
