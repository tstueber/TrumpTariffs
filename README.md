# Trump Tariff Map (Interactive)

This project visualizes the global tariffs imposed under the Trump administration using an interactive Leaflet.js map.

## 🔍 What It Does

- Displays country-by-country Trump-era tariffs using color-coded shading
- Shows reciprocal tariffs charged by each country on U.S. goods
- Identifies:
  - Tariff rate imposed on each country
  - Top impacted goods
  - Major affected companies
- Marks countries with **treaty exemptions** (USMCA or FTA) using a dashed border
- Allows user interaction:
  - Hover to highlight countries
  - Click for a popup with detailed information

## 🗺️ Features

- Built using [Leaflet.js](https://leafletjs.com/)
- Data sourced from a compiled JSON dataset of impacted countries
- Uses public `GeoJSON` country boundary files
- Styled with dynamic colors based on tariff severity
- Treaty-exempt countries are visually distinguished

## ⚙️ How to Use

To run it locally:
1. Download or clone the repository
2. Open `index.html` in your browser

To view online (via GitHub Pages):
- Go to: `https://tstueber.github.io/trump-tariff-map/`

## 📁 Files

- `index.html` — the main interactive map
- `tariffData` (inside script) — tariff dataset hardcoded in JavaScript
- `README.md` — you're reading it!

## 🌐 Technologies Used

- HTML5 / CSS3
- JavaScript
- [Leaflet.js](https://leafletjs.com/)
- [OpenStreetMap](https://www.openstreetmap.org/)
- [GeoJSON](https://geojson.org/)

## 📌 Notes

- Treaty exemptions apply only to qualifying goods under trade agreements.
- Data includes both tariff rates imposed by the U.S. and those charged in return.

---

🗣️ *This project is for visualization and educational purposes only.*

