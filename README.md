# netcdf-prep-for-nsidc

# 🛰️ NSIDC DAAC Data Preparation & NetCDF Conversion

This repository provides a complete, reproducible Python-based workflow for preparing and formatting Earth science data files according to the standards set by the **NASA National Snow and Ice Data Center Distributed Active Archive Center (NSIDC DAAC)**. The process includes metadata structuring, data cleaning, NetCDF conversion, and visualization.

## 📂 Repository Contents

- `Demo.ipynb` — Main Jupyter Notebook outlining the end-to-end process:
  - Loading sample data
  - Converting variables to proper formats
  - Generating compliant NetCDF files
  - Reading and visualizing output

## 📊 Dataset Description

The notebook uses a sample dataset:
> **SMAP-Derived 9-km EASE-Grid Surface Soil Permittivity and Vegetation Optical Depth over Snow-Covered Regions, Version 1**  
> [GitHub Repo](https://github.com/aebtehaj/SM-Snow-L-band)

This product provides daily 9-km resolution estimates of:
- Surface Soil Permittivity
- Vegetation Optical Depth (VOD)

Retrieved using the **Tau-Omega-Snow (TO-Snow)** emission model and validated with external ecological and climate variables.

## 🛠️ Standards and Guidelines

The data formatting and metadata follow the official standards outlined by:
- [NASA Earth Science Data Standards](https://www.earthdata.nasa.gov/about/standards)
- [NSIDC NetCDF Attribute Guidelines (PDF)](https://nsidc.org/sites/default/files/documents/other/nsidc-guidelines-netcdf-attributes.pdf)

## 🧰 Dependencies

Make sure the following Python packages are installed:
```
numpy
scipy
xarray
netCDF4
matplotlib
h5py
```

## 📈 Visualization Tools

The output NetCDF files can be opened and visualized in:
- [Panoply](https://www.giss.nasa.gov/tools/panoply/)
- [QGIS](https://qgis.org/)
- Python tools like `xarray` and `matplotlib`

## 📜 References

1. [Passive microwave retrieval of soil moisture below snowpack at L-band using smap observations, 2022](https://ieeexplore.ieee.org/abstract/document/9927161)  
2. [Global estimates of L-band vegetation optical depth and soil permittivity of snow-covered boreal forests and permafrost landscape using SMAP satellite data, 2024](https://www.sciencedirect.com/science/article/pii/S0034425724001561)
