# 📍 Clustering Project for the Municipality of Breda

This project was developed as part of a data-driven initiative to support the Municipality of Breda in addressing segregation and socio-economic disparities across neighborhoods.

By applying machine learning and geospatial analysis, the project identifies neighborhood clusters based on socio-economic indicators, uncovering patterns and highlighting areas that may require policy attention or social intervention.

## 🧠 Project Summary

Segregation and social inequality have increased in Breda over the past decade. This project uses modern data science techniques to cluster neighborhoods and deliver actionable insights that support inclusive policy-making.

The end-to-end pipeline includes:

- **Data Acquisition & Cleaning**: Collected raw socio-economic and geospatial data, handled missing values, removed duplicates, and processed outliers.
- **Exploratory Data Analysis (EDA)**: Visualized trends and correlations to understand the data distributions and regional patterns.
- **Preprocessing & Dimensionality Reduction**:
  - Scaled features using `StandardScaler`
  - Applied `PCA` to reduce dimensions while retaining essential variance
  - Used `Nearest Neighbors` to compute locality-based distances
- **Clustering**:
  - Applied **DBSCAN** to identify clusters and outliers
  - Mapped vulnerable neighborhoods using cluster labels and policy-defined socio-economic criteria
- **Visualization**:
    - Built PowerBI interactive dashboard to represent the finidings to stakeholders

## 🗂️ Project Structure

| Module                     | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `EDA`                     | Visualizations and statistical analysis to explore trends in the dataset   |
| `Preprocessing`           | Feature scaling, PCA transformation, and neighborhood distance calculations |
| `Clustering`              | Application of DBSCAN, cluster labeling, and neighborhood tagging            |
| `GeoDataFrame Integration`| Used to handle spatial data and integrate clustering with geospatial visuals|
| `Visualization`| Built PowerBI dashboard to represent the finidings to stakeholders|


## 🛠️ Tools & Libraries

- `pandas` – Data manipulation  
- `numpy` – Numerical computations  
- `matplotlib`, `seaborn` – Data visualization  
- `sklearn` – Machine learning pipeline  
  - `StandardScaler`
  - `PCA`
  - `NearestNeighbors`
  - `DBSCAN`
- `GeoPandas` – Spatial data handling and visualization
- `PowerBI` - Interactive dashboards

## 🔍 Key Techniques

- PCA for dimensionality reduction  
- Nearest Neighbor for distance mapping  
- DBSCAN for density-based clustering  
- Cross-referencing clusters with vulnerability indicators  
- Geospatial insights via GeoDataFrames
- PowerBI dashboard to represnt key findigs to stakeholders

## 🕒 Duration

**8 weeks** (including EDA, modeling, and documentation)

## 📌 Outcome

This project produced meaningful neighborhood clusters that reflect socio-economic similarities and differences, offering the municipality an analytical foundation to combat segregation using targeted, data-informed decisions.

