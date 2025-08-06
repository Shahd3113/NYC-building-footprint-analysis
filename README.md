# 🗽 NYC Building Footprint Analysis

A data analysis and spatial visualization project focusing on the building footprints in New York City using official open-source geospatial data.

## 📌 Objectives

- Analyze building construction years, heights, and spatial distribution across NYC
- Detect trends and patterns per borough
- Visualize key metrics using maps and charts

## 📂 Dataset

- **Source:** [NYC Open Data - BUILDING_P](https://data.cityofnewyork.us/City-Government/BUILDING_P/u9wf-3gbt/about_data)
- Includes:
  - Geographic footprints of buildings
  - Construction year
  - Height above ground
  - Borough name
  - Unique identifiers (BIN, BBL, etc.)

## 🛠️ Steps

1. Imported necessary libraries (pandas, geopandas, matplotlib, folium, etc.)
2. Loaded the official NYC building dataset
3. Performed EDA to explore construction year, building height, and data quality
4. Cleaned data by handling nulls and dropping unnecessary fields
5. Created visualizations using:
   - Charts (bar, pie, histogram)
   - Interactive maps using Folium
6. Highlighted spatial patterns by borough and identified age clusters


---

### 🧹 Data Cleaning & Preparation

- **Data Type Conversion**  
  ![Data Type Conversion](images/data_type_conversion.png)

- **Handling Missing Values**  
  ![Missing Values](images/handling_missing_values.png)

- **Land Use Distribution**  
  ![Land Use](images/land_use_distribution.png)
## 📊 Visualizations

### 🗺️ Spatial Maps

- **Interactive Building Map**  
  ![Interactive Map](images/interactive_building_map.png)

- **Buildings Colored by Borough**  
  ![Buildings by Borough](images/buildings_colored_by_borough.png)

- **Spatial Layout of City Structures**  
  ![Spatial Layout](images/spatial_layout_of_city_structures.png)

- **Building Age Clusters**  
  ![Age Clusters](images/building_age_clusters.png)

---

### 📈 Distributions & Analytics

- **Distribution of Construction Years**  
  ![Construction Years](images/distribution_of_construction_years.png)

- **Distribution of Building Heights**  
  ![Building Heights](images/distribution_of_building_heights.png)

- **Tall Buildings in NYC (Height > 43ft)**  
  ![Tall Buildings](images/tall_buildings_nyc.png)

- **Top 10 Building Classes**  
  ![Top 10 Classes](images/top_10_building_classes.png)

- **Number of Buildings per Borough**  
  ![Buildings per Borough](images/number_of_buildings_per_borough.png)


## ✅ Key Insights

- Certain boroughs (like Manhattan) contain a high concentration of older buildings
- Recent constructions are clustered in specific zones
- Building heights vary greatly depending on borough and location
- Spatial analysis supports city planning and real estate decision-making

## 🧠 Tools Used

- Python
- Pandas & GeoPandas
- Matplotlib & Seaborn
- Plotly
- Folium
- Jupyter Notebook

## 📎 Files

- `analysis.ipynb`: Main analysis notebook
- `images/`: Contains charts and maps

## 📬 Contact

Feel free to reach out for questions or collaboration.
