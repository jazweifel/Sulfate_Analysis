# Sulfate Aerosol Analysis

This repository contains analysis notebooks used to generate figures for:

**Zweifel et al. (2026)**  
*Seasonality of Sulfate Aerosols and Radiative Forcing from East Asian SO₂ Emissions over the North Pacific.*

The analysis processes output from the **Community Earth System Model (CESM2.1.5)** and produces the figures used in the manuscript.

---

## Repository Structure

```
notebooks/
└── figures/
    ├── Figure_01
    ├── Figure_02
    ├── Figure_03
    ├── ...
    └── Figure_10
```

Each directory contains the Jupyter notebook used to generate the corresponding manuscript figure.

---

## Data

Large climate model datasets are **not included in this repository**.

The analysis uses CESM model output derived from simulations described in the manuscript. These datasets are hundreds of gigabytes in size and therefore cannot be distributed through GitHub.

The emissions forcing used in the simulations is based on the **Community Emissions Data System (CEDS)**:

Hoesly, R. et al. (2018). *Historical (1750–2014) anthropogenic emissions of reactive gases and aerosols from the Community Emissions Data System (CEDS).* Geoscientific Model Development.

---

## Software Archive

A permanent snapshot of this repository is archived on Zenodo:

DOI: https://doi.org/10.5281/zenodo.18893812

---

## Requirements

Typical environment used for analysis:

- Python 3
- xarray
- numpy
- matplotlib
- pandas
- cartopy
- netCDF4

---

## Author

Jack Zweifel  
Department of Atmospheric and Oceanic Sciences  
University of Wisconsin–Madison
