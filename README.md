# Earth-Observation-Project
# Flood Mapping & Impact Assessment (GEE)

This Earth Engine script detects flood extents using Sentinel-1 SAR data and assesses impacts on population, croplands, and urban areas. It includes rainfall trend analysis and visual outputs.

## Main Features
- **Flood Detection**: Uses Sentinel-1 SAR imagery to detect flood extents via pre/post backscatter analysis, slope masking, and connectivity filtering.
- **Impact Analysis**:
  - Population exposure (GHSL 2015)
  - Cropland inundation (UMD 2019)
  - Urban flooding (JRC built-up areas)
- **Rainfall Trends**: Analyzes CHIRPS pentad data for historical rainfall and anomalies.
- **Export Options**: Download results as GeoTIFF or Shapefile.
- **Interactive Map**: Includes legend, flood map layers, and summary panel.

> **Note**: Designed for rapid flood impact assessment. Accuracy may vary; not intended for operational emergency response.

