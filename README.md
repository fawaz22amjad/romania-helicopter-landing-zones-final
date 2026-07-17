# Tactical Helicopter Landing Zone (HLZ) Suitability Analysis
**Location:** Făgăraș Mountains, Romania  
**Mission Scope:** Joint Search and Rescue / Tactical Extraction Planning  

---

## 📌 Project Overview
This project identifies viable helicopter landing zones (HLZs) in the rugged terrain of the Făgăraș Mountains using high-resolution terrain modeling and manual geospatial intelligence (GEOINT) verification. 

### Final Map Deliverable
![Final Map](Romania_HLZ_Suitability_Map.png)

---

## 🛠️ Methodology & Technical Workflow
1. **Terrain Suitability Modeling:** Calculated terrain slopes using a Digital Elevation Model (DEM) to identify flat clearings (< 5-degree incline).
2. **Dimension Constraints:** Isolated and filtered safe contiguous polygons exceeding a threshold of 1,500 m² to support standard tactical rotor clearances.
3. **Vegetation & Obstacle Quality Control (QC):** Conducted visual verification against high-resolution satellite basemaps. Where automated geometric centroids intersected with dense tree clusters, points were manually adjusted to clear, open grass lawns.

---

## 📂 Project Structure & How to Open
* `hlz_data.gpkg`: Self-contained GeoPackage containing vetted vector polygons and manually verified point centroids.
* `Romania_HLZ_Mission_Map.qgz`: Complete QGIS project styled with standard tactical SVGs and map layouts.

### To view this project locally:
1. Download this repository as a `.zip` folder and extract it.
2. Open **QGIS** (v3.x or higher).
3. Open the `Romania_HLZ_Mission_Map.qgz` project file. The data will load automatically via relative file paths.
