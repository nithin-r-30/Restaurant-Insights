# 🍽️ Restaurant Insights – Geo-Spatial Data Analysis

## 📌 Project Overview

Restaurant Insights is a data analytics and geo-spatial visualization project designed to explore and analyze restaurant data. The project focuses on understanding restaurant distribution, customer ratings, cuisines, pricing patterns, and geographical locations.

Using Python, data analysis techniques, interactive maps, and Power BI dashboards, the project transforms raw restaurant data into meaningful insights that support better understanding of restaurant trends and performance.

## 🎯 Project Objectives

- Analyze restaurant distribution across different cities.
- Identify popular cuisines and restaurant categories.
- Understand restaurant rating patterns.
- Analyze the relationship between restaurant ratings and average cost.
- Explore customer votes and restaurant popularity.
- Visualize restaurant locations using geographical coordinates.
- Create interactive maps and Power BI dashboards.

## 🛠️ Technologies Used

- **Python** – Data analysis and preprocessing.
- **Pandas & NumPy** – Data manipulation and cleaning.
- **Matplotlib & Seaborn** – Data visualization.
- **Folium** – Interactive geographical maps.
- **Power BI** – Interactive dashboard development.
- **Jupyter Notebook** – Data analysis and implementation.

## 📂 Project Structure

```text
Restaurant-Insights/
│
├── Dataset/
│   ├── Dataset.csv
│   └── cleaned_restaurant_data.csv
│
├── Maps/
│   ├── restaurant_map.html
│   └── restaurant_heatmap.html
│
├── Notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   └── 03_visualization_geo_analysis.ipynb
│
├── restaurant.pbix
├── requirements.txt
└── README.md
```

## 📊 Dataset Description

The dataset contains restaurant-related information, including:

- Restaurant ID and Name
- Country and City
- Address and Locality
- Latitude and Longitude
- Cuisines
- Average Cost for Two
- Table Booking Availability
- Online Delivery Availability
- Price Range
- Aggregate Rating
- Rating Text
- Customer Votes

The original dataset contains 9,551 records. After preprocessing and cleaning, the resulting dataset contains 9,542 records.

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Load the original restaurant dataset.
- Remove duplicate records.
- Handle missing values.
- Convert numerical columns into appropriate data types.
- Clean column names and cuisine information.
- Export the cleaned dataset.

### 2. Exploratory Data Analysis (EDA)
- Analyze restaurant distribution across cities.
- Identify the most popular cuisines.
- Explore restaurant rating distributions.
- Analyze average cost versus ratings.
- Study customer votes and ratings.
- Compare average ratings and costs across cities.

### 3. Geo-Spatial Analysis
- Use latitude and longitude coordinates to identify restaurant locations.
- Generate an interactive restaurant location map using Folium.
- Create a geographical heatmap to visualize restaurant concentration.
- Display restaurant ratings through map markers.

### 4. Power BI Dashboard
The Power BI report provides visual insights into restaurant data through:

- Location-based filtering.
- Restaurant geographical distribution.
- Rating-related KPI cards.
- Restaurant and city information.
- Restaurant rating distribution.

## 🗺️ Geo-Spatial Visualizations

The project includes two interactive geographical visualizations:

**Restaurant Map:** Displays restaurant locations using geographical coordinates and rating-based marker colors.

**Restaurant Heatmap:** Highlights geographical areas with higher concentrations of restaurants.

The HTML map files are available in the `Maps` folder.

## 🚀 Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Restaurant-Insights.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Restaurant-Insights
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn folium jupyter
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks in the `Notebooks` folder and execute them in the following order:

1. `01_data_preprocessing.ipynb`
2. `02_exploratory_data_analysis.ipynb`
3. `03_visualization_geo_analysis.ipynb`

### Step 5: Open the Power BI Report

Open `restaurant.pbix` using Microsoft Power BI Desktop to explore the interactive dashboard.

### Step 6: View Geographical Maps

Open the following HTML files in a web browser:

- `Maps/restaurant_map.html`
- `Maps/restaurant_heatmap.html`

## ✨ Key Features

- Restaurant data cleaning and preprocessing.
- Exploratory data analysis.
- Cuisine and city-wise analysis.
- Rating and pricing analysis.
- Interactive restaurant location mapping.
- Geographical heatmap visualization.
- Power BI dashboard for interactive analysis.

## 🔮 Future Enhancements

- Add real-time restaurant data integration.
- Include advanced geographical clustering.
- Develop a web-based interactive dashboard.
- Add restaurant recommendation functionality.
- Perform predictive analysis on restaurant ratings.
- Expand location-based insights.

## 🎓 Project Information

**Project Title:** Restaurant Insights – Geo-Spatial Data Analysis  
**Domain:** Data Analytics and Geo-Spatial Visualization  
**Tools:** Python, Jupyter Notebook, Folium, Power BI  
**Project Type:** Data Analytics Project

## 📌 Conclusion

Restaurant Insights demonstrates how data analytics and geo-spatial visualization can be used to understand restaurant trends, customer ratings, cuisine preferences, pricing patterns, and geographical distribution. By combining Python-based analysis, interactive maps, and Power BI dashboards, the project converts restaurant data into meaningful and understandable insights.

---

**Restaurant Insights – Turning Restaurant Data into Meaningful Insights.**
