# A Crab Story

Information and insights on the abundance of snow crab in the Alaskan Eastern Bering Sea, the geographical distribution
and changes over the years (1975 - 2028) may be useful to monitor for goverment and environmental organizations.

# Objective

First of all, the task of this project was to find an appropriate dataset to further apply linear regression, cluster analysis and time series analysis.
Therefore, I came up with an open dataset from ‘kaggle’: Snow Crab Geospatial Data (1975-2018).
Gained insights may be useful to monitor for goverment and environmental organizations.

# Data Set

The data was collected from NOAA (National Oceanic and Atmospheric Administration, U.S. Department of Commerce).
It contains catch per unit effort data of commercial snow crab landings in the Alaskan Eastern Bering Sea.
The catch per unit effort is an indirect measure of the abundance of a target species.

2 datasets were merged:

- NMFS_Reporting_Areas.geojson
- Original Snow Crab.csv

The two datasets were merged via a spatial join, assigning each coordinate point from the original dataset to the polygon in the GeoJSON file that contains it.

# Tools

For this project, the following python libraries were used:

- pandas as pd
- numpy as np
- os
- matplotlib
- matplotlib.pyplot as plt
- seaborn as sns
- scipy
- folium
- json
- sklearn
- from sklearn.model_selection import train_test_split 
- from sklearn.linear_model import LinearRegression
- from sklearn.metrics import mean_squared_error, r2_score
- sklearn.cluster import KMeans
- from sklearn.preprocessing import StandardScaler
- pylab as pl
- statsmodels.api as sm
- warnings

# Executing the Code

The code is available as jupyter notebooks, [Open Scripts Folder on OneDrive](https://onedrive.live.com/?id=%2Fpersonal%2F68518651159bb850%2FDocuments%2FDokumente%2Fdata%20analytics%2FImm%5FAch%206%20DA%20Project%206%2FSnow%20Crab%20Ach%206&view=0)
