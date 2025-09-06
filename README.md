README (WARNING: THIS WORK IS UNDER DEVELOPMENT AND IS FILLED WITH BUGS. THIS IS SIMPLY A PROTOTYPE AND IS NOT MEANT FOR PRODUCTION)

This Flight Radar Mockup is a web-based project that visually tracks flights on an interactive world map. It uses the Aviationstack API (with support for mock/demo data) and the Leaflet.js mapping library. The site allows users to view, filter, and search for active flights, with additional features such as weather overlays, flight details, and search suggestions.

Features
Live flight positions: Fetches data from the Aviationstack API (API key required), with fallback to mock flight data.

Interactive world map: View all flights as animated markers using Leaflet.js.

Flight search: Find specific flights by callsign, airline, or route; quickly cycle through matches.

Filtering: Filter by flight type—commercial, cargo, military, or private.

Declutter mode: Show only commercial flights for a simplified view.

Weather overlay: Toggle display of simulated weather regions (rain, storm, snow, fog) on the map. 

Flight details panel: Click a marker to display altitude, speed, aircraft, status, and more.

Splash screen: Friendly landing UI with quick-start actions and search.

How It Works
Map Display: The application uses Leaflet.js to render an interactive map and live-updated markers for every flight.

Live Data: If enabled, real flight data is fetched from Aviationstack via their REST API (API key required); otherwise, mock demo flights are used.

Marker Positioning: If live GPS data is missing, flight markers are intelligently placed along their expected routes between departure and arrival airports.

Filters and Search: UI elements let users filter planes by type and search using keywords.

Setup & Usage
Clone or download the repository.

Get an API key from Aviationstack.

Edit the code: Replace YOUR_API_KEY_HERE in the script section with your API key.

Open the index.html file in your browser. No server required; the app is pure front-end.

Start exploring! Use the splash screen, try the search bar, or turn on real-time data.

Requirements
Aviationstack API key (free or paid, for real flight data)

Modern web browser

Stable internet connection (to fetch map tiles and API data)

Technologies Used
Leaflet.js – Mapping library

Aviationstack API – Flight data provider

Tailwind CSS – UI and layout styling

Vanilla JavaScript (no frameworks required)

Notes
The free Aviationstack API tier provides limited real-time data. Some flights may have inaccurate or missing GPS, in which case marker positions are estimated.

No flight tracking data is stored. All rendering is client-side.

This project is intended for educational and demonstration purposes.

License
Copyright 2025
[Aeshan Tripathi]
This project is released under the Apache License.

Feel free to modify this as needed for your own use or for public sharing!

Related
Provide the project's name, short description, and main features
List installation steps for npm, yarn, and Docker
Describe configuration variables and example .env file
Add usage examples and common commands to run
Write contribution guidelines, license, and contact info





