# MODIS-Land-Cover-Classification-Annual-Data-500m-From-GEE
This repository contains a Google Earth Engine (GEE) script for retrieving and analyzing MODIS land cover data. The script focuses on a specific region of interest (ROI) and exports land cover classification results for a chosen year.

## Overview

The provided script utilizes Google Earth Engine to:

- Define a region of interest (ROI) as a polygon.
- Retrieve MODIS land cover dataset for a specified date range and filter it by the ROI.
- Extract month and year information from the image timestamps.
- Choose a specific year of interest and filter the dataset accordingly.
- Select the image for the specified year and clip it to the ROI.
- Visualize the land cover classification on the map using a predefined color palette.
- Export the land cover image for the chosen year to Google Drive.

## Instructions

1. **Setting up Google Earth Engine Account:**
   - Ensure you have access to Google Earth Engine (GEE) and have the necessary permissions to run scripts.

2. **Configuring the Script:**
   - Modify the region of interest (ROI) coordinates in the script based on your study area.
   - Customize the year variable to the desired year of interest.

3. **Running the Script:**
   - Execute the script in the Google Earth Engine Code Editor or locally, depending on your preference.

4. **Viewing Results:**
   - Check the results on the Google Earth Engine Map and ensure the land cover classification is visualized correctly.

5. **Exporting Data:**
   - Review the exported data in the specified Google Drive folder.

## Dependencies

- Google Earth Engine Account
- Google Earth Engine API
- Google Earth Engine Python API (if running locally)
