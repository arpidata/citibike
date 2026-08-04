# 🚲 Citi Bike Data Analysis & Geospatial Insights

An end-to-end data analytics project exploring **Citi Bike trips in Jersey City (2025)**  using Python, geospatial analysis, interactive visualizations, and weather data integration.

---

## 📖 Project Overview

The objective of this project is to analyze Citi Bike usage patterns in Jersey City and identify temporal, spatial, and environmental factors that influence bike-sharing activity.

The project combines data cleaning, feature engineering, exploratory data analysis, weather data integration, and geospatial analytics to generate actionable insights.

---

## 🎯 Project Objectives

* Analyze Citi Bike trip patterns throughout the year.
* Identify the busiest months and seasons.
* Explore the most popular stations and travel routes.
* Investigate how weather conditions influence bike usage.
* Perform geospatial analysis of station activity across Jersey City neighborhoods.
* Create interactive maps for better spatial understanding.

---

## 🛠 Technologies Used

* Python
* Pandas
* GeoPandas
* Plotly
* Folium
* Matplotlib
* Requests
* Jupyter Notebook

---

## 📁 Project Structure

```
citibike/
├── data/
│   └── citibike/
├── notebooks/
│   ├── 1_Download_Citibike_Data.ipynb
│   ├── 2_Data_Enrichment.ipynb
│   ├── 3_Weather_Data.ipynb
│   ├── 4_Data_Visualization.ipynb
│   └── 5_Neighborhood_Analysis.ipynb
├── README.md
├── .gitignore
└── requirements.txt
```

---

## 📊 Data Processing

The project includes:

* Downloading Citi Bike trip data
* Data cleaning
* Missing value handling
* Ride duration calculation
* Date and time feature engineering
* Season classification
* Processed dataset generation

---

## 🌦 Weather Data Integration

Weather information was retrieved from the Open-Meteo Archive API and merged with daily Citi Bike activity.

Weather variables include:

* Average temperature
* Maximum temperature
* Minimum temperature
* Precipitation
* Rainfall
* Snowfall
* Maximum wind speed

---

## 📈 Exploratory Data Analysis

The project explores:

* Monthly ride volume
* Seasonal ride distribution
* Top departure stations
* Top arrival stations
* Daily ride trends
* Weather impact on bike usage

Interactive Plotly visualizations were created to better understand the data.

---

## 🗺 Geospatial Analysis

GeoPandas and Folium were used to perform spatial analysis, including:

* Station point generation
* Coordinate Reference System (CRS) handling
* Spatial joins between stations and neighborhoods
* Route analysis
* Interactive route maps
* Neighborhood-level activity analysis
* Choropleth maps
* Interactive station maps

---

## 📌 Key Analyses

✔ Monthly Citi Bike demand

✔ Seasonal trends

✔ Most popular stations

✔ Most popular routes

✔ Weather vs bike usage

✔ Neighborhood activity

✔ Station density

✔ Average activity per station

✔ Departure and arrival distribution

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* API Integration
* Geospatial Analytics
* Interactive Mapping
* Python Programming
* Business Data Analysis

---

## 📚 Dataset

Citi Bike Trip Data (Jersey City, 2025)

Neighborhood boundaries were provided as GeoJSON files.

Weather data was obtained using the Open-Meteo Archive API.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/arpidata/citibike.git
cd citibike
```

### 2. Create a Conda environment

```bash
conda create -n citibike python=3.12
```

### 3. Activate the environment

```bash
conda activate citibike
```

### 4. Install the required packages

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 6. Run the notebooks in order

1. `1_Download_Citibike_Data.ipynb`
2. `2_Data_Enrichment.ipynb`
3. `3_Weather_Data.ipynb`
4. `4_Data_Visualization.ipynb`
5. `5_Neighborhood_Analysis.ipynb`

---

## 👩‍💻 Author

**Arpenik Mesropyan**

Radiologist transitioning into Data Analytics with a strong interest in data visualization, geospatial analytics, and business intelligence.
