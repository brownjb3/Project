Non-Chain BBQ Across the U.S.
This interactive Leaflet web map visualizes non-chain barbecue restaurants across the United States, along with state population data for 2023. The goal is to showcase where unique, independent BBQ joints are located.

Features
Custom Map Markers based on average user ratings (0–5).

State Population Layer with a color scale representing population estimates.

Interactive Popups & Tooltips for BBQ location names and addresses.

Legend for both rating categories and population ranges.

Responsive Full-Screen Design using Leaflet and FontAwesome.

Files and Dependencies
Main Files:
index.html – The core map application.

assets/bbq_locations.geojson – GeoJSON file with non-chain BBQ location data and average ratings.

assets/2024_USpop.geojson – GeoJSON file with U.S. state population estimates.

External Libraries:
Leaflet.js – for interactive mapping.

leaflet-ajax – for loading GeoJSON asynchronously.

FontAwesome – for custom fire icons representing BBQ ratings.

Chroma.js – for generating a color scale.

jQuery – for dynamically injecting marker colors into CSS.

 Map Styling
BBQ locations are symbolized with fire icons colored by rating:

 Red = 0 stars

 Orange = 1–2 stars

 Yellow = 3 stars

 Green = 4–5 stars

State polygons are shaded in blue gradients based on population density.

Notes
Ratings and addresses were attained via google maps api using a scraper

This project is ideal for exploring independently owned BBQ restaurants.

Population data sourced from U.S. Census 2024 estimates.

Author
Map Author: [Jacob Brown]
Credits:

State polygons: US Census Open Data

Basemap: CartoDB

Icons: FontAwesome
