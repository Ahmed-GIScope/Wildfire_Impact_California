# Wildfire Impact in California (GIS Project)

## 📌 Overview
This project analyzes the impact of wildfires in California using **ArcGIS Pro**.  
It calculates burned areas by county and visualizes the results through thematic maps.  

## 🛠 Tools & Methods
- ArcGIS Pro 3.0
- Spatial Join for county-level statistics
- Raster overlay for burned area
- Export to Excel for summary tables

## 📊 Results
- Final wildfire maps:  
  - ![Wildfire Map](maps/Wildfire_Map.jpg)  
  - ![Wildfire Intersect](maps/Wildfire_Intersect.jpg)  
- County-level summary: [`wildfire_summary.xlsx`](results/wildfire_summary.xlsx)

## 📂 Repository Contents
- `/maps` → Exported wildfire maps (`Wildfire_Map.jpg`, `Wildfire_Intersect.jpg`)  
- `/results/wildfire_summary.xlsx` → Burned area statistics per county  
- `Wildfire_Impact_California.aprx` → ArcGIS Pro project file  
- `Wildfire_Impact_California.atbx` → ArcGIS Toolbox  
- `README.md` → Project documentation  

## ⚠️ Note on Data
Due to size limits, raw data (Geodatabase, Map Package) is not included.  
You can download wildfire perimeter data from [USGS Fire Data](https://data-nifc.opendata.arcgis.com/) and California county boundaries from [California Open Data](https://data.ca.gov/).  

## ✨ Author
**Ahmed Nouman**  
Agricultural Engineer & GIS Specialist  
🌍 Remote Sensing • Climate Change • Sustainable Agriculture  
