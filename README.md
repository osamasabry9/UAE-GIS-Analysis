# 🇦🇪 UAE Administrative Boundaries and Population Visualization

This project provides an interactive and static visualization of the **United Arab Emirates administrative boundaries**, including analysis of **population, area, and density**. It supports both **folium-based maps** and **matplotlib visualizations**, with shapefiles sourced from [Humanitarian Data Exchange (HDX)](https://data.humdata.org/dataset/cod-ab-are).

---

## 📂 Dataset Source

**Name:** [United Arab Emirates administrative level 0-1 shapefiles (are_adm_fcsc_20230515_SHP_AB.zip)](https://data.humdata.org/dataset/cod-ab-are)  
**License:** Open Data (HDX - UNOCHA)  
**Content:**
- Level 0: Country boundary  
- Level 1: Emirate boundaries

---

## ✅ Features

| Feature | Description |
|--------|-------------|
| 🗺️ Interactive Map | Uses Folium to visualize Emirates with tooltips and heatmap |
| 🌡️ Population Heatmap | Shows density using `folium.plugins.HeatMap` |
| 📊 Static Choropleth | Matplotlib-based map with density coloring |
| 📍 Famous Landmarks | Burj Khalifa, Sheikh Zayed Mosque, Jebel Jais added to map |
| 📈 Density Chart | Bar chart of population density by Emirate |
| 📁 GeoJSON Export | Shapefile converted to GeoJSON for web mapping |

---

## 🛠️ Installation

If you're running on **Google Colab**, just copy-paste the notebook cells.  
Otherwise, for local setup:

```bash
pip install geopandas folium matplotlib seaborn
````

Make sure you have:

* Python 3.8+
* Jupyter Notebook or Google Colab

---

## 📦 How to Use

1. **Upload the ZIP shapefile** (`are_adm_fcsc_20230515_SHP_AB.zip`)
2. **Run the notebook cells**:

   * Extract and read shapefiles using GeoPandas
   * Add population/area data if missing
   * Plot maps and charts
3. **Output Files:**

   * `uae_density_map.png` – Static map
   * `uae_density_bar_chart.png` – Density bar chart
   * `uae_interactive_map.html` – Interactive map
   * `uae_adm1.geojson` – Exported Emirate GeoJSON

---

## 🌍 Visual Preview

### 🗺️ Interactive Map Sample

![Map Sample](screenshots/uae_map_preview.png)

### 📈 Density by Emirate

![Bar Chart](screenshots/density_bar_chart.png)

---

## 🧠 Technologies Used

* [`GeoPandas`](https://geopandas.org/)
* [`Folium`](https://python-visualization.github.io/folium/)
* [`Matplotlib`](https://matplotlib.org/)
* [`Seaborn`](https://seaborn.pydata.org/)
* [`HDX`](https://data.humdata.org/)


## 📜 License

This project is open source under the MIT License. The dataset is provided by UNOCHA under its open data policy.

---

## 🤝 Acknowledgements

* Data provided by [Humanitarian Data Exchange (HDX)](https://data.humdata.org/)
* Emirate names and stats approximated based on available public info

---

## 📬 Contact

If you'd like to collaborate or suggest features, feel free to open an issue or contact me via GitHub!

```


