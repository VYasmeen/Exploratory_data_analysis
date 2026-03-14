# Roller Coaster Exploratory Data Analysis (EDA)

A comprehensive Exploratory Data Analysis (EDA) project using Python and Pandas to uncover trends in the world of roller coasters. This project focuses on data cleaning, handling complex data types (like GPS coordinates), and visualizing correlations between physical attributes and coaster performance.

## Project Overview
This project was built to practice "manual" Data Analysis—moving away from AI-assisted autocomplete and focusing on core Python and SQL logic. It takes a raw, messy dataset of roller coaster statistics and transforms it into actionable insights.

## Tech Stack
- **Python:** Primary language for data manipulation.
- **Pandas:** Used for data cleaning, filtering, and aggregation.
- **Matplotlib & Seaborn:** Used for statistical visualization and trend analysis.
- **PyCharm:** Professional IDE used for script development and debugging.

## Key Analysis Phases

### 1. Data Understanding & Cleaning
- **Shape & Type Inspection:** Identifying missing values and incorrect data types.
- **Deduplication:** Removing duplicate entries based on `Coaster_Name` and `Opening_Date_Clean`.
- **Casing & Formatting:** Standardizing column names to lowercase to prevent indexing errors.

### 2. Feature Engineering
- **Binned Analysis:** Grouping granular Latitude and Longitude data to identify regional speed trends.
- **Aggregation:** Calculating mean speeds and coaster counts per location to filter for statistically significant data.

### 3. Data Visualization
- **Correlation Heatmaps:** Exploring the relationship between height, speed, and inversions.
- **Top 10 Rankings:** Visualizing the fastest and oldest coasters using bar charts.
- **Regional Comparisons:** Analyzing how coaster specs vary across different geographic latitudes.

## 📈 Key Insights
- **The "Happiness" of Coasters:** Investigated whether certain regions invest more in high-speed attractions.
- **Data Quality:** Found that filtering for a minimum threshold (e.g., `count >= 5`) is essential to avoid outliers when analyzing regional averages.

## How to Run
Clone the repository:

Bash
git clone [https://github.com/VYasmeen/Exploratory_data_analysis.git](https://github.com/VYasmeen/Exploratory_data_analysis.git)
Install dependencies:

Bash
pip install pandas matplotlib seaborn
Run the notebook or scripts in your preferred IDE (PyCharm recommended).
