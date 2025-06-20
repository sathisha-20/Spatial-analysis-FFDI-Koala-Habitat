# Spatial-analysis-FFDI-Koala-Habitat

## 📘 Project Description

This project performs a **spatiotemporal analysis of the Forest Fire Danger Index (FFDI)** across **New South Wales, Australia**, from **2013 to 2023**. It identifies regions under high fire risk over time and validates the **spatial overlap between past fires and high risk areas**. Additionally, the project assesses the impact of fire risk on **koala habitats**, using **Python** and **QGIS**.

---

## 📁 Folder Structure

📦 Spatiotemporal Analysis and Koala Habitat Files/dropbox link below
├── Study Area # Area of this study shapefile
├──2013-2023_pastfires.zip # Shapefile of preprocessed past fire polygons from 2013 to 2023
├── Monthly_FFDI files/ # Monthly FFDI raster files (GeoTIFF format)
├── FFDI_highrisk_12plus/ # Binary rasters with high-risk FFDI pixels (FFDI > 12)
├── Koala_Data/Preprocessed Koala shapefile/ Thresholded shapefile # Spatial data of koala habitat areas
├── Output_Spatiotemporal analysis/ # Results from spatial and temporal analysis
└── README.md # This documentation file

📁 Notebooks/
├── Calculation of FFDI.ipynb # Calculates FFDI using input climate data
├── Calculation of KBDI & DF.ipynb # Calculates KBDI and Drought Factor
├── FFDI_Spatiotemporal Analysis.ipynb # Calculates high-risk area trends and plots
├── Overlap_Analysis_FFDI_Koalahabitat.ipynb # Identifies overlaps with koala habitats
└── Validation_of_FFDI_with_past_fires.ipynb # Compares FFDI maps with historical fire data

yaml
Copy
Edit

---

## 🔗 Access the Datasets

📥 **Download all files from Dropbox**:  
👉 [**Click here to access the shared folder**](https://www.dropbox.com/scl/fo/y69xi2vhj2ucse75myh50/ABG0er6CdJDU60dFqmu2d5s?rlkey=9tuamuw7yurnz231006yfxrh3&st=qdeexgfx&dl=0)  

---

## 🧰 How to Run the Analysis

### 1. Install Required Python Packages

Open your terminal and run:

```bash
pip install numpy pandas rasterio geopandas shapely matplotlib seaborn xarray rioxarray
2. Open and Run the Jupyter Notebooks
Execute the notebooks in the following recommended order:

Calculation of FFDI.ipynb

Calculation of KBDI & DF.ipynb

FFDI_Spatiotemporal Analysis.ipynb

Validation_of_FFDI_with_past_fires.ipynb

Overlap_Analysis_FFDI_Koalahabitat.ipynb

Make sure all required datasets are downloaded and extracted in the appropriate folders.

📊 Key Outputs

FFDI Monthly Files

High- Risk Files

Time series plots of FFDI clusters and trend analysis, Seasonality analysis

Time series of Annual high risk areas

Validation of modelled fire risk with actual past fires

Overlap analysis of fire risk zones with koala habitat

