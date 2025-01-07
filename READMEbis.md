# README.md

## Description

Meteo Data Aggregation Hub is an open source tool for collecting and gathering meteorological data.

Data is received from various API and providers (NOAA, ECMWF, Météo France, DWD,...) 

All data blocks are merged into only one standard data file (NetCDF) with all meteorological data.

Tool architecture is made of micro-services channels handling data processing.

It has been deviced to be scalable and prone to extensions in input sources and computional tasks,


## Main features

- **Data mergeing** : Gather and merge data from various providers.
- **Normalizing** : All data is store in one NetCDF file
- **Geographical area filtering** : Filter data according to user criterias.
- **Advanced** :
  - Space and/or time interpolation.
  - Configurable requests using JSON files.

