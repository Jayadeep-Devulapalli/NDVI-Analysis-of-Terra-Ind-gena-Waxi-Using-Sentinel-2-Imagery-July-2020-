# NDVI-Analysis-of-Terra-Ind-gena-Waxi-Using-Sentinel-2-Imagery-July-2020-
Terra Indígena Waxi Vegetation Health Assessment

This project analyzes vegetation health in Terra Indígena Waxi, a protected Indigenous territory in Mato Grosso, Brazil, using Sentinel-2 L2A satellite imagery from July 2020. It calculates the Normalized Difference Vegetation Index (NDVI) to detect ecological integrity, deforestation pressure, and land-use change within the southeastern Amazon biome.

Key Features

NDVI analysis using Sentinel-2 Bands B04 (Red) and B08 (NIR)
RGB composite imagery for visual validation
Fully open-access data from Sentinel-2 and OpenStreetMap
Transparent, reproducible Python-based workflow
Focus on Indigenous land stewardship and environmental monitoring
Project Structure

data/ – Sentinel-2 .SAFE files or processed imagery
notebooks/ – Jupyter Notebook for NDVI calculation and visualization
outputs/ – Generated maps and images
scripts/ – Python scripts (if separate from notebooks)
README.md – Project overview and setup guide
How to Run

Clone the repository
Install dependencies: pip install -r requirements.txt
Open the notebook: jupyter notebook notebooks/NDVI_Analysis_TerraWaxi.ipynb
Dependencies

Python 3.8+
rasterio
numpy
matplotlib
jupyterlab or notebook
Data Sources

Sentinel-2 L2A imagery from Copernicus Open Access Hub
OpenStreetMap for contextual overlays
License
MIT License

Acknowledgments
This project supports data-driven conservation and emphasizes the importance of Indigenous perspectives in environmental research.
