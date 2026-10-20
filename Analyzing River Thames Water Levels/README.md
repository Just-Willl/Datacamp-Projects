# Analyzing River Thames Water Levels

Summarise London Bridge tidal measurements and examine how extreme high and low water levels vary over time.

## Approach

Time series cleaning; grouped mean, median and interquartile range; quantile thresholds and annual ratios.

## Notebook and files

- [notebook.ipynb](notebook.ipynb) — Python analysis, explanations and saved outputs.
- [data/10-11_London_Bridge.txt](data/10-11_London_Bridge.txt)
- [data/12_All_Hallows_Pier.txt](data/12_All_Hallows_Pier.txt)
- [data/13_Temple_Pier.txt](data/13_Temple_Pier.txt)
- [data/14_Strand_on_Green.txt](data/14_Strand_on_Green.txt)
- [data/15_Richmond.txt](data/15_Richmond.txt)
- [data/1_Walton_on_Naze.txt](data/1_Walton_on_Naze.txt)
- [data/2_Margate.txt](data/2_Margate.txt)
- [data/3_Shivering_Sand.txt](data/3_Shivering_Sand.txt)
- [data/4_Southend.txt](data/4_Southend.txt)
- [data/5_Coryton.txt](data/5_Coryton.txt)
- [data/6_Tilbury.txt](data/6_Tilbury.txt)
- [data/7-8_Silvertown.txt](data/7-8_Silvertown.txt)
- [data/9_Cherry_Garden_Pier.txt](data/9_Cherry_Garden_Pier.txt)
- [locations.png](locations.png)

## Outputs

High- and low-tide summary Series and a `solution` dictionary containing annual extreme-tide ratios.

## Run locally

From this project folder, install JupyterLab and the packages used by the notebook:

```bash
python -m pip install jupyterlab pandas numpy matplotlib
python -m jupyterlab notebook.ipynb
```

Keep the notebook's working directory set to this folder so relative data and image paths resolve. Review the cells before running them in order. Package versions are not pinned; the original notebooks may need adjustments for newer library versions.

## Notes

The notebook includes exploratory attempts before a final solution. An earlier cell refers to undefined `high_ratio` and `low_ratio`; a fresh Run All may stop there.

This project was completed as part of DataCamp learning. The original notebook and supplied assets are preserved.

[Back to project index](../README.md)
