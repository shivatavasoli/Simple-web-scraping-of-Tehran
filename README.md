# Simple-web-scraping-of-Tehran
This Python project analyzes 10 days forecast for Tehran weather in Iran. The data represents the average max and min temperatures as well as the daily rain amount, taken for next 10 days. This data was taken from the Weather Forecast.

**Data Source**

The data used in this analysis is derived from the following URL:

**Tehran Weather** 

(https://www.foreca.com/100112931/Tehran-Iran/10-day-forecast)

**Project Overview**

The project involves web scraping, data cleaning, analysis, and visualization using Python libraries such as BeautifulSoup, pandas, seaborn, and matplotlib.

**Data Content**

The dataset includes the following information:

Day: The date of month for next 10 days.

Max temperature: Max temperature per day in degrees Celsious.

Min temperature: Min temperature per day in degrees Celsious.

Wind Speed: Average daily Wind Speed in Km/h.

Rain volume: Rain volume/inches per day


Tehran_Webscraping.ipynb: Jupyter Notebook containing the Python code.
Tehran_weather_10days_forecast.csv: CSV file with cleaned weather data exported from the Tehran_Webscraping.ipynb.

Web Scraping:

Data is scraped from the forecast website using BeautifulSoup.
Information is extracted from HTML and iterating Div Classes within that web page.

**Data Cleaning:**

Data is organized into a pandas DataFrame.
Data types are converted to int and float to have scatter plot.


**Data Visualization:**

Heatmap to visualize correlations between temperature and rainy days.
Boxplot to show 10 days temperature distribution (Day vs. Night).
Line chart to display 10 days temperature trend.
Bar chart to show daily rain volume.

**Data Export:**

Cleaned data is saved to a CSV file for reference.

**Conclusion**

This analysis explores the 10 days forecast weather for Tehran, considering the max and min temperatures, as well as the amount of rain for each day. The analysis includes data scraping, data cleaning, data visualization, and statistical summaries. Key findings and visualizations are presented to help forecast Tehran's weather.

Based on the weather forecast, the rainy days doesn't have correlation with the Temperature. In addition,the average rain inches are 0.03 inches in next 10 days which is very low. During the next 10 days, average max and min temperatures is around 20°C and 12°C accordingly.

