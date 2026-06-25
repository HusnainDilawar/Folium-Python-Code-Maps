# Archaeological Spatial Intelligence & Settlement Pattern Analysis

## Overview

As part of a professional geospatial analytics solution developed at **Stellar Solutions**, I designed and implemented an end-to-end spatial analysis pipeline to process archaeological datasets from the **Neolithic** and **Roman** periods across the United Kingdom. The solution transforms raw archaeological records into actionable spatial insights using geospatial preprocessing, machine learning clustering techniques, statistical evaluation, and interactive GIS visualization.

## Workflow

```
Raw Archaeological Dataset
        │
        ▼
Data Cleaning & Validation
        │
        ▼
Extract British National Grid References (Regex)
        │
        ▼
Convert Grid References to Easting/Northing
        │
        ▼
Transform Coordinates to Latitude & Longitude (WGS84)
        │
        ▼
Filter Historical Periods (Roman / Neolithic)
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Scaling
        │
        ▼
K-Means Clustering
        │
        ▼
DBSCAN Clustering
        │
        ▼
Cluster Performance Evaluation
(Silhouette Score & Davies-Bouldin Index)
        │
        ▼
Meta-Ensemble Clustering
        │
        ▼
Interactive GIS Visualization (Folium)
        │
        ▼
Settlement Pattern Analysis & Spatial Insights
```

## What I Implemented

* Designed a complete archaeological data preprocessing pipeline.
* Extracted British National Grid (BNG) references using Regular Expressions (Regex).
* Converted BNG references into Easting/Northing coordinates.
* Transformed coordinates to WGS84 Latitude and Longitude using **pyproj**.
* Performed exploratory spatial data analysis to validate geographic distributions.
* Implemented **K-Means** clustering with the Elbow Method for optimal cluster selection.
* Applied **DBSCAN** to detect dense settlement regions and identify spatial outliers.
* Evaluated clustering quality using **Silhouette Score** and **Davies-Bouldin Index**.
* Developed a **Meta-Ensemble Clustering** approach by combining K-Means and DBSCAN results.
* Created interactive GIS maps using **Folium** with marker clustering, layer controls, and informative popups.
* Produced reproducible spatial analytics to support archaeological settlement pattern analysis.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* pyproj
* Folium
* Matplotlib
* Seaborn
* Jupyter Notebook

## Key Features

* Automated archaeological data preprocessing
* British National Grid coordinate extraction
* Coordinate transformation (BNG → WGS84)
* K-Means clustering
* DBSCAN clustering
* Meta-Ensemble clustering
* Cluster evaluation metrics
* Interactive GIS visualization
* Settlement pattern analysis
* Spatial outlier detection
* Reproducible analytical workflow

## Results

* Successfully processed archaeological datasets from multiple historical periods.
* Generated high-quality geographic coordinates from raw location records.
* Identified settlement clusters using both centroid-based and density-based clustering methods.
* Produced interactive web-based maps for spatial exploration.
* Delivered a scalable and reproducible workflow for archaeological spatial intelligence and settlement analysis.
