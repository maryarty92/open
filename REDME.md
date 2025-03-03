# Overpass QL Script for Yarsale Area

This script is designed to extract specific geographical data from the Yarsale area using Overpass Turbo. The script utilizes the Overpass Query Language (Overpass QL) to query OpenStreetMap data.

## Overview

The script retrieves the following types of data within the specified area:
- Various amenities, including schools, libraries, healthcare facilities, and more
- Tourist attractions like hotels
- Various types of shops

## Query Breakdown

- **Amenities:** A wide range of amenities are filtered, such as schools, libraries, restaurants, and healthcare centers.
- **Tourism and Shops:** The script fetches data about hotels and various types of shops.

## Usage

1. **Open Overpass Turbo:** Go to [Overpass Turbo](https://overpass-turbo.eu/).
2. **Paste the Script:** Copy the code from the script file and paste it into the Overpass Turbo query field.
3. **Run the Query:** Click on the "Run" button to execute the query and visualize the data on the map.
4. **Export Results:** Once the data is loaded, you can export the results in various formats like GeoJSON, GPX, or KML using the export options provided by Overpass Turbo.

## Output

The results of the query include both geometrical data and metadata, which will be displayed on the map interface of Overpass Turbo.

## Note

- Ensure that your internet connection is stable when running the query, as fetching data might require considerable bandwidth for larger areas or detailed data requests.
- The timeout for the query is set to 25 seconds. If you experience timeout errors, consider narrowing down the search area or simplifying the query.