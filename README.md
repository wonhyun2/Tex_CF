![image](https://github.com/user-attachments/assets/564e09ca-89fa-4bf9-8a22-d27537096f9c)

Fig. Model extents and boundaries, including the observed stations: NOAA water level stations (♦), USGS hydrograph gages (▼) and streamflow gages (▲), the stations of USGS (+) and NOAA (+) High Water Marks, the best track of Hurricane Harvey (2017, ▬) and Hurricane Beryl (2024, ▬ ). The inset shows the study area within the Gulf of America, highlighting the hurricane tracks and their corresponding wind intensities.

# SFINCS Model Repository for Compound Flooding from Hurricanes Harvey and Beryl

This repository contains the input files, domain configurations, and model results for six hydrologically distinct coastal zones along the Texas Gulf Coast. The simulations were performed using the Super-Fast INundation of CoastS (SFINCS) model to assess the role of rapid intensification (RI) and relative sea-level rise (RSLR) on compound flooding, as presented in:

![image](https://github.com/user-attachments/assets/fdf991d6-8e53-4069-8815-f9abbe55c634)

Fig. Flood depth changes under Hurricane Harvey re-simulated with projected 2024 relative sea-level rise. a) average RSLR across six zones, derived from nine NOAA stations (detailed station information is provided in Table S4 of the Supplementary Information); flood amplification under b) max, c) mean, and d) min RSLR trends.

**Lee, W., Sun, A. Y., & Scanlon, B. R. (2025)**  
*Rapid Intensification and Relative Sea-Level Rise Amplifying Compound Flooding from Hurricanes Harvey to Beryl*  Submitted to _Earth’s Future_.

---

## 🔍 Overview

This study investigates compound flooding mechanisms by comparing two hurricane events:

- **Hurricane Harvey (2017)**: Slow-moving storm, extreme rainfall and river discharge.
- **Hurricane Beryl (2024)**: Rapidly intensifying storm, surge-dominated flooding.

We use SFINCS to simulate fluvial, pluvial, and surge-driven inundation for:
- All individual flood drivers
  a) tide-only
  b) tide+wind (Surge only)
  c) tide+wind+river
  d) tide+wind+rain  
- Compound scenarios (all-driver)
- Climate-adjusted RSLR scenario for Harvey

---

## 📂 Repository Contents

Each `DomainX_ZoneX/` folder includes:
- `sfincs_model.inp`: Model configuration file
- `input/`: Hydrodynamic boundary, rainfall, river discharge, and wind files
- `output/`: Simulation results for flood depth, extent, and time series

---
