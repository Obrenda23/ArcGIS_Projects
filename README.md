# Watershed Elevation and Sub-Catchment Analysis

## Project Overview

This project demonstrates a watershed delineation and terrain analysis workflow completed using ArcGIS Pro. The study area was divided into ten sub-catchments to support hydrological assessment, water resource management, and environmental analysis.

The project integrates elevation data, river networks, hydrological stations, and meteorological stations to visualize watershed characteristics and support spatial decision-making.

---

## Project Objectives

- Delineate watershed and sub-catchment boundaries.
- Analyze topographic variation using a Digital Elevation Model (DEM).
- Visualize river networks and drainage patterns.
- Map hydrological and meteorological monitoring stations.
- Support hydrological and environmental planning through geospatial analysis.

---

## Study Area

The watershed was subdivided into ten sub-catchments (WS1–WS10) for detailed analysis. Elevation across the study area ranges from approximately **1,504 m to 3,220 m**, highlighting significant terrain variation that influences hydrological processes.

---

## Data Used

### Spatial Data
- Digital Elevation Model (DEM)
- Watershed boundaries
- River network data
- Hydrological station locations
- Meteorological station locations
- Administrative boundaries

### Derived Data
- Flow Direction Raster
- Flow Accumulation Raster
- Stream Network
- Watershed Boundaries
- Sub-Catchment Boundaries
- Elevation Classes

---

## Software and Tools

- ArcGIS Pro
- ArcGIS Spatial Analyst
- ArcGIS Hydrology Toolset
- ArcGIS Cartography Tools

---

## Methodology

### 1. DEM Preparation
The Digital Elevation Model was processed and checked for sinks and irregularities.

### 2. Hydrological Processing
Hydrological tools were used to:
- Fill sinks
- Generate flow direction
- Calculate flow accumulation
- Extract stream networks

### 3. Watershed Delineation
Pour points were defined and used to delineate watershed and sub-catchment boundaries.

### 4. Terrain Analysis
Elevation values were classified into multiple categories to visualize topographic variation across the watershed.

### 5. Cartographic Design
The final map was designed using:
- Elevation color gradients
- River network overlays
- Watershed boundaries
- Monitoring station symbols
- Scale bar, north arrow, and legend

---

## Results

The final map illustrates:

- Ten delineated sub-catchments (WS1–WS10)
- Elevation distribution across the watershed
- River network connectivity
- Hydrological monitoring stations
- Meteorological monitoring stations
- Area statistics for each sub-catchment

### Sub-Catchment Areas

| Sub-Catchment | Area (Ha) |
|--------------|-----------:|
| WS1 | 17,565 |
| WS2 | 46,245 |
| WS3 | 20,384 |
| WS4 | 31,037 |
| WS5 | 19,739 |
| WS6 | 24,258 |
| WS7 | 56,714 |
| WS8 | 76,882 |
| WS9 | 2,804 |
| WS10 | 57,048 |

---

## Key GIS Skills Demonstrated

- Watershed Delineation
- Hydrological Modeling
- Terrain Analysis
- DEM Processing
- Spatial Analysis
- Geoprocessing
- Environmental Mapping
- Cartographic Design
- Data Visualization
- ArcGIS Pro Workflow Development

---

## Repository Structure

```text
Watershed_Elevation_Analysis/
│
├── Maps/
│   └── Watershed_Elevation_Map.pdf
│
├── Data/
│   ├── DEM/
│   ├── Rivers/
│   ├── Watersheds/
│   └── Stations/
│
├── ArcGIS_Project/
│   └── Watershed_Analysis.aprx
│
├── Outputs/
│   ├── Watershed_Map.jpg
│   └── SubCatchment_Statistics.csv
│
└── README.md
```

---

## Sample Output

### Elevation Map of Sub-Catchments

This map visualizes:
- Watershed topography
- Sub-catchment boundaries
- River networks
- Hydrological stations
- Meteorological stations

*(Insert map screenshot here)*

---

## Applications

This project can support:

- Watershed management
- Flood risk assessment
- Water resource planning
- Environmental monitoring
- Hydrological research
- Land-use planning

---

## Author

**Brenda Ongera**

M.S. Applied Geospatial Science  
Bowling Green State University

### Research Interests
- GIS
- Remote Sensing
- Environmental Monitoring
- Landscape Ecology
- Hydrological Analysis
- Land Use/Land Cover Change

---

## License

This project is licensed under the MIT License.
