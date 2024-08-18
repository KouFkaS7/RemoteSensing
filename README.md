# RemoteSensing

Landsat 7 Image Analysis with Google Earth Engine
This project leverages Google Earth Engine (GEE) and Python to analyze Landsat 7 satellite imagery for a specified geographic area over a one-year period. The main objectives include retrieving, visualizing, and analyzing satellite images, particularly focusing on the calculation of the Normalized Difference Vegetation Index (NDVI) for environmental monitoring.

Features
Image Collection: Filters and retrieves Landsat 7 images for a specific location and time range.
Image Metadata: Extracts metadata like acquisition dates and cloud cover for each image.
Visualization: Displays true-color images and NDVI thumbnails using predefined visualization parameters.
Clipping: Clips images to a specified polygon region for focused analysis.
NDVI Calculation: Computes the mean NDVI for the region of interest and visualizes the vegetation index.
Installation
Ensure you have Python installed.
Install the required packages:
bash

pip install earthengine-api pandas
Authenticate and initialize Google Earth Engine within your environment.
Usage
Run the script to retrieve and analyze Landsat 7 images. The script outputs image thumbnails and generates a pandas DataFrame summarizing image metadata. Additionally, it calculates NDVI for selected images within a defined region.
