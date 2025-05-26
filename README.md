# WhaleDataset-VisualAnalysis 🐋🐬

This project presents a visual analysis of whale and dolphin sightings using a dataset provided by OBIS-SEAMAP.  
The analysis explores spatial and temporal patterns of marine mammals across different geographic regions and time periods, using a variety of visual techniques.

---

## 📊 Key Features

- 📍 **Geospatial Mapping**  
  Using `scatter_geo`, whale and dolphin sightings are plotted globally based on latitude and longitude.

- 🌡️ **Environmental Analysis**  
  The dataset includes **sea surface temperature**, **bathymetry (depth)**, and **latitude**, allowing comparisons across species and oceanic regions.

- 📦 **Species Grouping and Aggregation**  
  Observations are grouped by species, enabling average-depth, temperature, and spatial distribution analysis.

- 📈 **Temporal Trend Analysis**  
  Sightings over multiple decades are visualized to explore possible seasonal or long-term trends.

- 🎨 **Visual Methods Used**  
  - Heatmaps  
  - Boxplots  
  - Countplots  
  - Scatter plots  
  - Strip plots  
  - Interactive geographical maps (`plotly`)

---

## 📂 Project Structure

WhaleDataset-VisualAnalysis/
├── Marine Mammal - Visual Analysis.ipynb # Main notebook
├── assets/ # Saved plot images (optional)
│ └── scatter_geo_map.png
├── LICENSE # MIT License for code
├── README.md # This file
└── requirements.txt # Python dependencies

---

## 🐋 Data Source and License

This project uses marine mammal observation data from [OBIS-SEAMAP](http://seamap.env.duke.edu/).

> ⚠️ **Note**: The dataset itself is not included in this repository due to OBIS-SEAMAP’s data usage policy.  
> You can download the data directly from OBIS-SEAMAP and must comply with their [Terms of Use](http://seamap.env.duke.edu/data/terms).  
> Proper citation of both OBIS-SEAMAP and the original dataset providers is required.

### 🔖 OBIS-SEAMAP Citation

Halpin, P.N., A.J. Read, et al. 2009. OBIS-SEAMAP: The world data center for marine mammal, sea bird, and sea turtle distributions. *Oceanography* 22(2):104–115.

---

## 🪪 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.


---

## 🗺️ Visual Maps of Species Observations

### 1. Whale vs Dolphin Group Distribution
![Species Group Map](assets/species_map.png)

### 2. Global Tropical Sightings of Marine Mammal Species
![Tropical Species Map](assets/tropical_species_map.png)

### 3. Global Subtropical Sightings of Marine Mammal Species
![Subtropical Species Map](assets/subtropical_species_map.png)

### 4. Global Polar Sightings of Marine Mammal Species
![Polar Species Map](assets/polar_species_map.png)

### 5. Geographic Distribution of Dolphins, Killer Whales, and Minke Whales
![Common Name Map](assets/killerwhale_dolphin_minke_map.png)

