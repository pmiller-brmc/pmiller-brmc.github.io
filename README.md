# BRMC Resource Map - Interactive Services Map

This repository hosts the source code for the **BRMC Resource Map**, an interactive web application designed by the Blue Ridge Medical Center to help users locate and visualize essential community resources, including **Health Centers**, **Libraries**, and **Hospitals**, within the service area.

Built on the **Leaflet.js** mapping library, this tool provides a robust interface for data exploration and navigation.

The boilerplate for this code was created through a QGIS2Web export.
-----

## Key Features

  * **Interactive Mapping:** A responsive and modern interface built on the Leaflet framework.
  * **Marker Clustering:** Uses **Leaflet.markercluster** for efficient management and display of dense data points.
  * **Geocoding Search:** Integrated search functionality powered by **Leaflet-Photon** for finding addresses and specific locations.
  * **Nearest Service Navigation:** Upon clicking any point on the map, the navigation panel populates with the closest services, allowing users to cycle through them.

-----

## Accessing the Map

### Public Access

The official, published version of the map is hosted on GitHub Pages and can be accessed directly at the following URL:

 **[pmiller-brmc.github.io](https://pmiller-brmc.github.io)**

### Local Setup (For Developers)

To run or develop the map locally, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [repository-url]
    cd [repository-name]
    ```
2.  **Run Locally (Recommended):**
    Use a simple HTTP server to avoid local security restrictions and load the map correctly. For example, using Python:
    ```bash
    python -m http.server 8000
    ```
3.  **Access the Map:**
    Open your browser and navigate to `http://localhost:8000/index.html` (or the name of your main HTML file).
    
* Alternatively, you can run the html by opening the html file.
-----

## Usage Guide

To begin, navigate to the **[pmiller-brmc.github.io](https://www.google.com/search?q=https://pmiller-brmc.github.io)** website.

### Map Interaction

  * **Search Bar:** Use the search input (top-left) to find locations by address or name.
  * **Nearest Services:** Described below. Click on the map to find nearest locations to that point.

### Nearest Services Navigation

  * Click anywhere on the map to set a target point.
  * The bottom navigation bar will display information about the closest Health Center, Library, and Hospital to that clicked point.
  * Use the **Back** and **Forward** buttons to move between close hospital locations

-----

## Data Sources

The data displayed on this map is compiled from trusted public and government-maintained datasets:

  * **General Virginia Data:** `data.virginia.gov`
  * **Health Centers:** `findahealthcenter.hrsa.gov`
  * **Boundary Data (e.g., Census):** `U.S. Census Bureau`

**2025 Blue Ridge Medical Center**

-----