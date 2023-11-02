# Simple-web-scraping-of-Tehran
This Python Notebook project analyzes historical yearly weather averages for Tehran, Iran. The data represents the average maximum and minimum temperatures as well as the annual average rainfall, taken from 12 months of a year as a historical data. The data is obtained from the Weather WX Online website.

##**Data Source**

The data used in this analysis is derived from the following URL:

##**Tehran Weather** 

https://www.weatherwx.com/yearly-climate/ir/tehran.html

##**Project Overview**

The project involves web scraping, data cleaning, analysis, and visualization using Python libraries such as BeautifulSoup, pandas, seaborn, and matplotlib.

##**Data Content**

The dataset includes the following information:

Month: The month of the year.
Average temperature: Average daytime temperature in degrees Farenhait.
Average Wind Speed: Average Wind Speed in Km.
Average Precipitation 
Average Humidity in %
Average Cloud Cover in %
A3verage Pressure in mph
Average Dry Days
Average Precip Days
Average Snow Days
Average Fog Days
Average UV Index
Avrage Hours of Sun: sunny hours per day


Tehran_Webscraping.ipynb: Jupyter Notebook containing the Python code.
Tehran_weather_averages.csv: CSV file with cleaned weather data exported from the Tehran_Webscraping.ipynb.

Web Scraping:

Data is scraped from the website using BeautifulSoup.
Information is extracted from HTML tables on the web page.
##**Data Cleaning:**

Data is organized into a pandas DataFrame.
Column names are cleaned, and data types are converted for analysis.
##**Data Analysis:**

Descriptive statistics and a correlation matrix are calculated.
Visualizations are used to provide insights into the data.
##**Data Visualization:**

Heatmap to visualize correlations between temperature and rainy days.
Boxplot to show temperature distribution (Day vs. Night).
Line chart to display yearly temperature patterns.
Bar chart to show annual rainy days.
##**Data Export:**

Cleaned data is saved to a CSV file for reference.
##**Conclusion**
This analysis explores the historical weather data for Tehran, including average daytime and nighttime temperatures, as well as the number of rainy days for each month. The analysis includes data scraping, data cleaning, data visualization, and statistical summaries. Key findings and visualizations are presented to help understand Tehran's weather patterns throughout the year.

Additionally, based on the annual weather average, it is evident that the rainy days doesn't have correlation with the Temperature. The months July, August and September are the hottest months without rains. In addition,the average rainy days are 3 days per month which is very low. During the mentioned months, temperatures are so high, with an average around 35°C.


