# ECMWF S2S Reforecast: Predictability & Uncertainty Analysis
This project explores the predictability of the Northern Hemisphere 300 hPa Geopotential Height ($Z300$) using **ECMWF S2S (Subseasonal-to-Seasonal) reforecast data**.
The analysis focuses on quantifying forecast uncertainty growth and identifying the most predictable atmospheric modes through Principal Component Analysis (PCA) and Average Predictable Time (APT) analysis.

## Project Overview
In numerical weather prediction, uncertainty increases with lead time due to the chaotic nature of the atmosphere. 
This project implements a full pipeline to:
1. **Process** high-dimensional S2S reforecast datasets
2. **Visualize** the evolution of ensemble spreads using 3D probability density functions
3. **Extract** dominant spatial patterns via Area-Weighted PCA
4. **Identify** optimal predictable modes (APTM) that maximize the signal-to-noise ratio over time

## Tech Stack
- Data Processing: {Numpy}, {SciPy}, {netCDF4}
- Machine Learning: {Scikit-learn} (PCA)
- Visualization: {Matplotlib}, {Cartopy} (Geospatial projections)

## Analytical Pipeline
