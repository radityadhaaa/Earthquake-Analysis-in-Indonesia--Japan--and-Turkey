
# Earthquake Analysis (2008 - 2017): Indonesia, Japan, and Turkey

## Overview
This project analyzes earthquake data from Indonesia, Japan, and Turkey for the period between 2008 and 2017. The notebook performs data cleaning, preprocessing, exploration, and visualization to uncover trends and characteristics of seismic activity across these regions. Key aspects explored include earthquake frequency, magnitude trends, and geographical distributions.

## Contents
The notebook covers the following major steps:

1. **Data Import and Initial Setup**
   - Import necessary libraries for data manipulation, analysis, and visualization (`numpy`, `pandas`, `matplotlib`, `seaborn`, `datetime`, and `calendar`).
   - Load earthquake datasets from Indonesia, Japan, and Turkey into separate DataFrames for analysis.

2. **Data Preprocessing**
   - Rename columns for consistency and better readability.
   - Drop unnecessary columns to reduce data complexity.
   - Extract date-related information such as year, month, and day.
   - Parse location data to extract `city` and `country` information.
   - Clean and standardize country names for consistent analysis across datasets.

3. **Data Filtering**
   - Filter earthquake records based on specific criteria (e.g., country and date range).
   - Focus on earthquake data for the years 2008 to 2017.

4. **Data Visualization**
   - **Earthquake Counts**: Create bar charts to visualize the number of earthquakes in each country.
   - **Yearly Earthquake Trends**: Plot the frequency of earthquakes per year for each country.
   - **Average Magnitude Trends**: Compare the average magnitude of earthquakes per year across the three countries using bar plots.
   - **City-Based Earthquake Counts**: Display the number of earthquakes recorded in each city within each country, with emphasis on the most affected areas.
   - **Depth vs. Magnitude Scatter Plot**: Create a scatter plot comparing depth and magnitude for each country's earthquakes.

5. **Conclusions**
   - Summarize insights and observations derived from the data analysis and visualizations.

## Key Files
- `katalog_gempa.csv`: Earthquake data for Indonesia.
- `earthquake_japan.csv`: Earthquake data for Japan.
- `earthquake_turkey.csv`: Earthquake data for Turkey.
- Jupyter Notebook containing the analysis and visualizations.

## How to Use
1. **Prerequisites**:
   - Python 3.x installed on your system.
   - Necessary libraries installed: `numpy`, `pandas`, `matplotlib`, `seaborn`.

2. **Run the Notebook**:
   - Open the Jupyter Notebook and execute cells sequentially to reproduce the analysis.
   - Ensure that the data files (`katalog_gempa.csv`, `earthquake_japan.csv`, `earthquake_turkey.csv`) are located in the correct path as specified in the code.

3. **Customization**:
   - You can modify filtering criteria (e.g., date range) to focus on different periods.
   - Additional visualizations or analysis steps can be added to gain further insights.

## Results
- **Earthquake Frequency**: The data shows varying frequencies of earthquakes across Indonesia, Japan, and Turkey, with each country experiencing different trends over the years 2008 to 2017.
- **Magnitude Trends**: The average magnitude trends revealed yearly fluctuations, highlighting differences in seismic activity severity.
- **Geographical Distributions**: Certain cities in each country experienced higher earthquake frequencies, indicating regional seismic hotspots.

## Conclusion
This analysis provides insights into the seismic activity trends in Indonesia, Japan, and Turkey. The visualizations and trends help inform risk assessment and preparedness strategies. Further exploration can involve predictive modeling, correlation analysis, or in-depth regional studies.
