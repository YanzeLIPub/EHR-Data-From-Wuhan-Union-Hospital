# EHR-Data-From-Wuhan-Union-Hospital
A longitudinal electronic health record dataset of cardiovascular patients from central China
# EHR Data Processing and Visualization

This repository contains data processing and visualization scripts used in our study of patient behavior and healthcare system dynamics using de-identified electronic health records (EHR) from Wuhan Union Hospital. The scripts support data cleaning, feature extraction, cohort construction, and publication-ready visualizations.

## 📁 Repository Structure

Data Access
The original EHR data are hosted on the OMIX platform under controlled access (accession number: OMIX010068). Please submit a formal request to access the dataset according to local data use regulations.
├── scripts/
│ ├── data_cleaning.R # EHR data cleaning and missing value handling
│ ├── feature_engineering.R# Variable extraction and transformation
│ └── analysis.R # Chord diagrams, bar plots, and missing data heatmaps
├── figures/
│ └── Figure 1.pdf # Sample output figures
├── README.md
