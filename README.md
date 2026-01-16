# Spain Weather Analysis - AEMET

## Technologies
- Power BI Desktop
- AEMET OpenData API
- DAX (calculated tables, measures)

## Features
1. Interactive map with 100+ weather stations
2. Wind rose by 22.5° direction sectors
3. Temperature, humidity, precipitation KPIs
4. Filters by station/date

## Installation
1. Download .pbix file
3. Refresh data

## Dashboard Overview
**Map Page**: Spain map showing all stations.  over any station shows coordinates, average temperature & wind speed.
**Station Detail**: Line charts (temp/humidity/precip), wind rose (16 sectors: avg speed), slicer by station.

## Data Processing
- Connected to AEMET observations & inventory stations (https://opendata.aemet.es/centrodedescargas/inicio)
- Filtering of data
- Aggregated max/min/avg temperature, wind speed, precipitation
- Calculated wind direction bins (16 sectors) for observations
- Created wind sectors table with sumarization of direction bins for each station obtaining the count and mean windspeed columns.