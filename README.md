# Identifying Species Distribution Along the West Coast of the US


## Overview
Marine aquaculture has the potential to play an important role in the global food supply as a more sustainable protein option than land-based meat production. Gentry et al. mapped the potential for marine aquaculture globally based on multiple constraints, including ship traffic, dissolved oxygen, bottom depth.


## Goal
To determine which Exclusive Economic Zones (EEZ) on the West Coast of the US are best suited to developing marine aquaculture for several species of oysters.


## Highlights
- Combining raster and vector data
- Masking and resampling raster data
- Map algebra
- Map visualization


## Data
#### Sea Surface Temperature

We will use average annual sea surface temperature (SST) from the years 2008 to 2012 to characterize the average sea surface temperature within the region. The data we are working with was originally generated from NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1.

#### Bathymetry

To characterize the depth of the ocean we will use the General Bathymetric Chart of the Oceans (GEBCO).

#### Exclusive Economic Zones

We will be designating maritime boundaries using Exclusive Economic Zones off of the west coast of US from Marineregions.org.


## Repo Structure
```
Identifying_Species_Distribution
 │   .gitignore
 └───data
      └─── |  average annual sst's 
           |  depth.tif
           |  wc region files
 │   Identifying_Species_Distribution.html
 │   Identifying_Species_Distribution.Rmd
 │   Identifying_Species_Distribution.Rproj
 │   README.md
         
           
```
