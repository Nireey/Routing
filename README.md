Route Optimization in Kathmandu City
This project demonstrates how to compute and visualize the shortest routes for driving in Kathmandu, Nepal, using OpenStreetMap (OSM) data, NetworkX, and Folium in Python. The project visualizes different types of routes (shortest time, shortest distance, and a route via a waypoint), and also includes a custom legend for easy route identification on the map.

Features
Shortest Time Route: Finds the fastest route between two locations.
Shortest Distance Route: Finds the route with the least distance.
Route via Waypoint: Finds a route that passes through a specified waypoint.
Interactive Map: Displays the computed routes on an interactive map using Folium.
Custom Legend: Adds a custom legend on the map to explain the routes and markers.
Requirements
To run this project, you need to install the following Python libraries:

networkx
osmnx
folium
You can install them using pip:

bash
Copy
Edit
pip install networkx osmnx folium
How It Works
Download Street Network: The street network for Kathmandu is downloaded from OpenStreetMap using the osmnx library.
Add Speeds and Travel Times: The travel speeds and times for each road segment are added to the graph for route calculation.
Find Nearest Nodes: Given the coordinates of a start location, an end location, and an optional waypoint, the nearest network nodes are found.
Compute Routes: Three types of routes are calculated:
Shortest route by time
Shortest route by distance
Route via waypoint (passing through a specified location)
Create an Interactive Map: The routes are plotted on an interactive map, and markers for the start, end, and waypoint are added.
Legend: A custom legend is added to the map for easy visualization of the routes and locations.
Usage
Clone or download the project repository.
Open the Jupyter Notebook (.ipynb file).
Run each code cell to:
Download the street network of Kathmandu.
Compute the shortest routes.
Visualize the routes on an interactive map.
View the travel metrics (distance and time) for each route.
Example Output
You will see an interactive map showing:

A blue route for the shortest time.
A green route for the shortest distance.
An orange route for the route that passes through a waypoint.
Markers indicating the start, end, and waypoint locations.
Conclusion
This project provides a simple and effective way to visualize routing data for urban transportation systems. It demonstrates the power of combining Python libraries for spatial data analysis and interactive visualization.
