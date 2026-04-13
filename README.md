## ERA5 Wind Point Analysis & Windrose

This repository contains a simple and practical workflow to analyze wind data from ERA5 using Python and Jupyter Notebook.

The notebook demonstrates how to extract wind data at a specific location, compute wind speed and direction, and visualize wind patterns using a windrose.

---

## Requirements

Make sure you have the following Python libraries installed:

```bash
pip install xarray cfgrib numpy pandas matplotlib windrose
```
---

## Workflow Overview

This notebook covers:

1. Extract wind data (u10, v10) at a selected point  
2. Compute wind speed and meteorological wind direction  
3. Export time series to CSV  
4. Classify wind into 16 directional sectors  
5. Generate wind statistics (%)  
6. Plot windrose visualization  

---

## How to Use

---

### 1. Clone Repository

Open Anaconda Prompt / Terminal, then run:
```bash
git clone https://github.com/kikid-kbw/pywind_era5_02.git
cd pywind_era5_02
```
Open notebook
```bash
jupyter notebook
```

### 2. Open jupyter notebook file
open:
```bash
era5_extraction_count_windrose.ipynb
```

### 3. Prepare the data
You can generate these files using the notebook from pywind_era5_01

### 4. Run Notebook
Run all cells step by step

---

## Series

pywind_era5_01 → Download & basic visualization
pywind_era5_02 → Point analysis & windrose

---

## Notes

This project is intended for educational and practical use
Feel free to explore and modify the workflow
