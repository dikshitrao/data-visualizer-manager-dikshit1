🌤️ Weather Data Visualizer – Dikshit
📘 Assignment Overview

This project is a mini assignment for the course Programming for Problem Solving using Python.
The goal is to analyze and visualize daily weather data of Delhi to understand climate patterns and long-term trends.

📂 Dataset

Dataset Used: Daily Delhi Climate dataset (CSV format)

Main Columns:

date – Date of observation

meantemp – Mean daily temperature (°C)

humidity – Mean daily humidity (%)

wind_speed – Average wind speed (km/h)

meanpressure – Mean daily air pressure (hPa)

Cleaned File: data/Cleaned_DailyDelhiClimate.csv

🛠️ Tools & Technologies

Python 3

Jupyter Notebook

Libraries Used:
Pandas, NumPy, Matplotlib, Seaborn

📁 Project Structure
weather-data-visualizer-dikshit/
│
├─ data/
│   ├─ DailyDelhiClimateTrain.csv
│   └─ Cleaned_DailyDelhiClimate.csv
│
├─ images/
│   ├─ Daily_Temperature.png
│   ├─ Humidity_vs_Temperature.png
│   ├─ Monthly_Temperature.png
│   └─ Temp_Humidity_Combined.png
│
├─ notebook/
│   └─ Weather_Analysis.ipynb
│
└─ report/
    └─ Summary.md

📊 Analysis & Visualizations

Daily Mean Temperature
Line chart showing daily temperature trends across multiple years.

Humidity vs Temperature
Scatter plot showing how humidity correlates with temperature.

Average Monthly Temperature
Bar chart showing temperature patterns and seasonal variation.

Combined Trend Plot
Line chart comparing temperature and humidity on the same timeline.

🧠 Key Insights

Clear seasonal patterns: hot summers, cool winters, and mild monsoons.

Humidity shows moderate correlation with temperature.

Monthly temperature analysis reveals strong periodic changes.

Wind speed and pressure show small fluctuations with no strong seasonal trend.

🧮 NumPy Statistical Analysis

NumPy was used to compute essential weather statistics after grouping by month:

✔ Mean Temperature

Shows the average monthly temperature and helps identify climatic trends.

✔ Minimum & Maximum Temperature

Highlights the temperature range and seasonal extremes.

✔ Standard Deviation

Measures how much temperature varies within a month.
Higher value = larger day-to-day variation.

▶️ How to Run the Project

Open:
notebook/Weather_Analysis.ipynb

Run all cells in order:

Loads the dataset

Cleans and processes the data

Creates visualizations

Saves cleaned files and plots automatically

Check generated files in data/ and images/ folders.

✍️ Author

Dikshit
