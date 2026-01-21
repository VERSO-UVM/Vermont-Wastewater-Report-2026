# Data Directory

This folder contains datasets used in the Vermont Wastewater Report 2026 analysis.

## Data Files

The following data files should be placed in this directory:

- `facilities.csv` / `facilities.geojson` - Wastewater treatment facility locations and attributes
- `watersheds.geojson` - Vermont watershed boundaries
- `flood_zones.geojson` - FEMA flood zone data
- `lake_champlain_basin.geojson` - Lake Champlain Basin boundary
- `phosphorus_discharge.csv` - Historical phosphorus discharge data
- `permit_compliance.csv` - Permit compliance records
- `facilities_capacity.csv` - Facility capacity and flow data

## Data Sources

Data for this project comes from:
- Vermont Department of Environmental Conservation (DEC)
- U.S. Environmental Protection Agency (EPA)
- U.S. Geological Survey (USGS)
- Vermont Center for Geographic Information (VCGI)

## Notes

- All spatial data should use the Vermont State Plane coordinate system (EPSG:32145) or WGS84 (EPSG:4326)
- CSV files should use UTF-8 encoding
- Large data files (>100MB) should be documented here but not committed to the repository

## Data Privacy

Ensure that all data shared in this directory complies with privacy regulations and data use agreements.
