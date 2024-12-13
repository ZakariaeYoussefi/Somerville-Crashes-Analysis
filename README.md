# Traffic Crash Data Analysis in Somerville

This project explores the **Somerville Traffic Crash Dataset** to identify trends and patterns using data visualization techniques such as heatmaps and time-based analysis. By leveraging Python libraries, we aim to uncover insights into accident occurrences, contributing factors, and high-risk periods.

You can better Visualize the Notebook in [this Kaggle link](https://www.kaggle.com/code/zakariaeyoussefi/exploring-traffic-crash-patterns-insights-from-da)
## Dataset
The dataset consists of **2,428 rows and 32 columns**, containing detailed information about traffic accidents in Somerville. Key columns include:
- `Crash Number`: Unique identifier for each crash
- `Date and Time of Crash`: Timestamp of the accident
- `Latitude` and `Longitude`: Location of the crash
- `Count Fatal Injury`, `Count Serious Injury`, etc.: Injury statistics
- `Speed Limit`, `Weather Conditions`, `Light Conditions`, etc.: Environmental factors

## Objectives
1. **Visualize Accident Distribution**  
   - Use heatmaps to identify high-risk areas for traffic accidents.
2. **Time-Based Analysis**  
   - Uncover accident patterns by time of day to determine high-risk periods.
3. **Highlight Key Insights**  
   - Provide observations to assist with improving traffic safety measures.

## Libraries Used
- `pandas`: Data manipulation and preprocessing.
- `numpy`: Numerical operations.
- `matplotlib` and `seaborn`: Plotting graphs and charts.
- `folium`: Interactive map visualization with heatmaps.


## Notable Techniques
- **Heatmap Visualization**  
  Heatmaps are generated using `folium` and `HeatMap` to display accident hotspots based on geographic coordinates.
  
- **Time-of-Day Analysis**  
  Conversion of accident timestamps into hourly bins using `pandas` to visualize peak accident hours.

