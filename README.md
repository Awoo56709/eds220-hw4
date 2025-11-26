# Visualizing the Aftermath of the Easton and Palisades Fires

![Palisades Weinraub Bus](vw.png)

# About

This repository contains a Jupyter notebook that creates a false color imagery to visualize the aftermath of the Eaton and Palisades fires that occured in LA County. Using Landsat data and infrared data, we are able to see the severity and vegetation impacts in the corresponding fire zones.

# Repository Structure

C:.
├───data
│   ├───eaton_fire
│   └───palisades_fire
└───eds220-hw4-task2-false-color-Ferrer-Lozano.ipynb
└───README.md
└───.gitignore


# Data Sources

- Eaton_Perimeter_20250121.shp: Dissolved fire perimeter/boundary of the Eaton Fire that took place during January 2025. It was collected by the NIFC FIRIS program.

- Palisades_Perimeter_20250121.shp: Dissolved fire perimeter/boundary of the Palisades Fire that took place during January 2025. It was collected by the NIFC FIRIS program.

- landsat8-2025-02-23-palisades-eaton.nc: This dataset contains a collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data, collected by the Landsat 8 satellite.

References:

Palisades and Eaton Dissolved Fire Perimeters. (2025). Fire perimeter shapefiles [Geospatial dataset]. ArcGIS Hub. https://hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c  [Accessed Nov. 24, 2025]

U.S. Geological Survey. (2025). Landsat 8 Collection 2 Level-2 surface reflectance data [Satellite imagery dataset]. Microsoft Planetary Computer. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2  [Accessed Nov. 24, 2025]

Bennett, M. M., Chen, J. K., Alvarez León, L. F., & Gleason, C. J. (2022). The politics of pixels: A review and agenda for critical remote sensing. Progress in Human Geography, 46(3), 729–752. https://doi.org/10.1177/03091325221074691 [Accessed Nov. 24, 2025]

Galaz García, C., Cawse-Nicholson, K., Frew, A., & Fontenot, R. (2024). EDS 220: Working with environmental datasets [Course materials]. Master of Environmental Data Science, Bren School of Environmental Science & Management, University of California, Santa Barbara. https://meds-eds-220.github.io/MEDS-eds-220-course/ [Accessed Nov. 24, 2025]