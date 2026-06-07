# Seasonal Snowfall Prediction in the European Alps

## A Machine Learning Investigation Using ERA5-Land Reanalysis and Topographic Data


---

## Project Overview

Seasonal snowfall is a critical component of mountain climates and directly impacts water resources, hydropower generation, ecosystems, and winter tourism.

This project investigates whether winter snowfall in the European Alps can be predicted using pre-season climate conditions and geographic characteristics. Using ERA5-Land climate reanalysis data and elevation information, we develop and evaluate machine learning models capable of forecasting seasonal snowfall accumulation across the Alpine region.

The project combines:

- Climate science
- Data engineering
- Statistical analysis
- Machine learning
- Model explainability

---

## Research Question

> To what extent can winter snowfall in the European Alps be predicted using autumn climate conditions and topographic characteristics?

Specifically, the project investigates:

- How strongly elevation influences snowfall accumulation.
- Whether autumn temperature contains predictive information about winter snowfall.
- Whether autumn precipitation can improve seasonal forecasts.
- Which variables contribute most to snowfall variability.
- Whether machine learning models outperform traditional statistical approaches.

---

## Study Area

European Alps

Approximate spatial extent:

- Latitude: 43°N – 48°N
- Longitude: 5°E – 16°E

The Alps provide an ideal case study due to their strong elevation gradients and highly variable snowfall patterns.

---

## Datasets

### ERA5-Land Reanalysis

Provider:
European Centre for Medium-Range Weather Forecasts (ECMWF)

Variables used:

- 2-meter air temperature (`t2m`)
- Total precipitation (`tp`)
- Snowfall (`sf`)

Period:

- 2000–2025

Spatial resolution:

- 0.1° × 0.1°

Source:

https://cds.climate.copernicus.eu/

---

### Elevation Dataset

Digital Elevation Model (DEM) used to determine elevation for each ERA5 grid cell.

Variable:

- Elevation (meters above sea level)
