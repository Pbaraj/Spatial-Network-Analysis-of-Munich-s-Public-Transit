# Spatial Network Analysis of Munich's Public Transit

## Overview
This project builds a Python workflow to extract, process, and analyze public transport network data for Munich using GTFS and OpenStreetMap.

The workflow:
- loads GTFS schedule data
- filters it to the Munich metropolitan area
- downloads the Munich road network from OpenStreetMap
- links GTFS stops to the underlying OSM network
- computes graph-based indicators using NetworkX
- exports processed datasets and visualizations

## Tools and Libraries
- Python
- pandas
- GeoPandas
- OSMnx
- NetworkX
- Partridge
- Matplotlib

## Data Sources
- GTFS public transport schedule data
- OpenStreetMap road network data

## Project Structure
```text
Spatial Network Analysis of Munich's Public Transit/
│
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── Spatial Network Analysis of Munich's Public Transit.ipynb
├── outputs/
│   ├── maps/
│   └── tables/
├── README.md
└── .gitignore
