# Vessel-Proximity-Detection-in-Marine-Regions
Using Python

### Objective
The goal of this assignment is to develop an algorithm that identifies instances where a vessel comes into close proximity with another vessel in a marine region. This phenomenon is referred to as 'vessel proximity.'

### Background
Marine vessels, including container ships, cargo ships, passenger ships, and others, are assigned a unique 9-digit number called the Maritime Mobile Service Identity (MMSI). This number is used to uniquely identify each vessel.

### Input Data
The provided CSV file contains rows with the positions (latitude and longitude), timestamps, and 'mmsi' numbers of all vessels in the designated marine region.

### Task
Develop an algorithm to determine all vessel proximity events, where two vessels with different MMSIs come within a threshold distance during a given time frame. The algorithm should be efficient and use the Haversine formula for distance calculation. To enhance efficiency, consider using one or more of the following methods:
- **Vectorization**
- **Quadtree-based approach**

### Tools and Technologies
- **Programming Language:** Python
- **GIS Tools/Libraries:** Geopandas, Shapely
- **Data Visualization:** Matplotlib, Plotly

### Output
The output is a DataFrame containing the following columns:
- **mmsi (int):** The unique identifier for the vessel.
- **vessel_proximity (list of int):** List of MMSI numbers with which the vessel interacted.
- **timestamp (datetime):** The timestamp of the proximity event.


