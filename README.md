# Visualizing Earthquake Data with D3.js and Leaflet

This project is part of the Big Data 2 course in the Big Data & Artificial Intelligence program. It aims to visualize earthquake data using D3.js and Leaflet, allowing users to interactively explore seismic activity around the world.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Features](#features)

## Project Overview
The application fetches real-time earthquake data from the USGS (United States Geological Survey) API and visualizes it on an interactive map. Users can see the magnitude, depth, and location of earthquakes represented by colored circles on the map.

## Technologies Used (default : part1)
- **HTML**: For structuring the web application (see `index.html`).
- **CSS**: For styling the application (see `style.css`).
- **JavaScript**: For implementing functionality (see `lab1.js`).
- **Leaflet.js**: For creating interactive maps.
- **D3.js**: Although not utilized in this implementation, it is typically used for complex data visualizations. ( see part 2 for an exemple of box plot )

## Setup Instructions
1. Clone this repository or download the files.
2. Open `index.html` in a web browser.
3. Ensure you have an internet connection to fetch data from the USGS API.

## Usage
Once the application is loaded, it will automatically fetch earthquake data from the past month. The map will display circles representing each earthquake, where:
- The size of the circle corresponds to the magnitude of the earthquake.
- The color of the circle indicates the depth (with a legend provided).

Click on any circle to view detailed information about that specific earthquake.

## Features
- Interactive map with real-time earthquake data visualization.
- Color-coded circles based on earthquake depth.
- Popup information displaying magnitude, depth, location, and time of each earthquake.
- A legend to help interpret depth colors.
