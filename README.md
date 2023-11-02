# Simple-web-scraping-of-Tehran
This simple Jupyter Notebook project analyzes historical yearly weather averages for Tehran, Iran. The data represents the average maximum and minimum temperatures as well as the annual average rainfall, taken from over 12 months of historical data. The data is obtained from the Weather WX Online website.

Data Source
The data used in this analysis is derived from the following URL:

Tehran Weather 
https://www.weatherwx.com/yearly-climate/ir/tehran.html

Project Overview
The project involves web scraping, data cleaning, analysis, and visualization using Python libraries such as BeautifulSoup, pandas, seaborn, and matplotlib.

Data Content
The dataset includes the following information:
Month','avg_Temperatures', 'avg_Windspeed', 'avg_Precipitation', 'avg_Humidity','avg_Cloud_Cover','avg_Pressure','avg_Dry_Days','avg_Precip_Days', 'avg_Snow_Days','avg_Fog_Days','avg_UVIndex','avg_Hours_of_Sun']


Month: The month of the year.
Average temperature: Average daytime temperature in degrees Farenhait.
Average Wind Speed: Average Wind Speed in Km.
Average Precipitation: 
Average Humidity:
Average Cloud Cover:
Average Pressure:
Average Dry Days:
Average Precip Days:
Average Snow Days:
Average Fog Days:
Average UV Index:
Avrage Hours of Sun:
Files
Tehran_Weather_Analysis.ipynb: Jupyter Notebook containing the Python code.
Tehran_weather_averages.csv: CSV file with cleaned weather data exported from the Tehran_Weather_Analysis.ipynb.
Analysis Steps
Web Scraping:

Data is scraped from the website using BeautifulSoup.
Information is extracted from HTML tables on the web page.
Data Cleaning:

Data is organized into a pandas DataFrame.
Column names are cleaned, and data types are converted for analysis.
Data Analysis:

Descriptive statistics and a correlation matrix are calculated.
Visualizations are used to provide insights into the data.
Data Visualization:

Heatmap to visualize correlations between temperature and rainy days.
Boxplot to show temperature distribution (Day vs. Night).
Line chart to display yearly temperature patterns.
Bar chart to show annual rainy days.
Data Export:

Cleaned data is saved to a CSV file for reference.
Conclusion
This analysis explores the historical weather data for Tehran, including average daytime and nighttime temperatures, as well as the number of rainy days for each month. The analysis includes data scraping, data cleaning, data visualization, and statistical summaries. Key findings and visualizations are presented to help understand Tehran's weather patterns throughout the year.

Additionally, based on the annual weather averages, it is evident that June and July are particularly appealing months for holidaymakers, as they boast the most favorable weather conditions. During these months, temperatures are pleasant, with an average around 18°C, making them ideal for outdoor activities and exploration.

Contributors

