# GEOG 458 Lab 04 – Map Tile Generation with Mapbox GL JS

This project demonstrates the creation of four raster tile sets using **QGIS**, **QMetaTiles/QTiles**, and **Mapbox Studio**, and their visualization in a single interactive web map using **Mapbox GL JS**.

---

## 🌐 Web Map URL

👉 **Access the interactive web map here:**  
https://jishnuk123.github.io/Tile-Generation-Lab

---

## 🗺️ Examined Geographic Area

The study area for this project is the **Seattle, Washington metropolitan area**, including the City of Seattle and surrounding neighborhoods. This area was chosen due to its availability of open geospatial datasets and its relevance to urban and environmental analysis.

---

## 🔍 Tile Sets Overview

### **Tile Set 1: Modified Basemap**

**Description:**  
A custom basemap created in **Mapbox Studio**, derived from a dark-style basemap and modified to include adjusted label fonts, emphasized landmarks, and dark blue water features. This basemap provides geographic context for the thematic layers.

**Zoom Levels:**  
`[e.g., 11–15]`

**Screenshot:**  
![Tile Set 1 – Modified Basemap](assets/tileset1/metatiles/13_&&_1310_2857_&&_1313_2860.png)

---

### **Tile Set 2: Seattle Parks**

**Description:**  
A thematic map showing public park polygons in Seattle, created from a geospatial dataset loaded into QGIS. Parks are symbolized in green to represent recreational and environmental spaces and exported as transparent raster tiles.

**Data Source:**  
Seattle Open Data Portal – Parks and Open Space

**Zoom Levels:**  
`[e.g., 11–15]`

**Screenshot:**  
![Tile Set 2 – Seattle Parks](assets/tileset2/metatiles/11_&&_325_713_&&_328_716.png)

---

### **Tile Set 3: Basemap + Parks Data**

**Description:**  
A combined tile set integrating the custom basemap from Tile Set 1 with the Seattle parks dataset from Tile Set 2. This layer demonstrates how thematic data can be overlaid on a tailored basemap for improved spatial interpretation.

**Zoom Levels:**  
`[e.g., 11–15]`

**Screenshot:**  
![Tile Set 3 – Basemap and Data](assets/tileset3/metatiles/11_&&_327_713_&&_330_716.png)

---

### **Tile Set 4: UW Themed Map**

**Description:**  
A thematic map designed in **Mapbox Studio** using University of Washington colors, icons, and labels to highlight campus landmarks and surrounding features.

**Zoom Levels:**  
`[e.g., 11–15]`

**Screenshot:**  
![Tile Set 4 – UW Themed Map](assets/tileset4/metatiles/8_&&_39_87_&&_42_90.png)

---

## 🧩 Web Map Features

- Full-screen interactive map  
- Layer switcher to toggle between all four tile sets  
- Map title and descriptive text  
- Zoom controls and scale bar  
- Proper attribution for map tiles and data sources  

---

