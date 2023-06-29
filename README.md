Air Pollution Project
Project Summary
The main goal was to analyze the historical air pollution data in Europe's capital cities from 2021 January to 2023 June (when this project started)..

Skills Used

Bash for data cleaning
SQL to analyze the data
Power BI for visualization

Desired Insights

Which city was the most polluted to live in from 2021 to 2023?
Which city had the healthiest air to breath from 2021 to 2023?
Rank the capital cities by the PM 2.5. and PM 10.
Which season has the highest and lowest pollution levels across Europe?

Preparing the Project Data

The Dataset was scraped from https://www.openweathermap.org through an API key.
The cities' data was also scraped from https://www.learnit3d.fi using BeautifulSoup and Python's Requests library.

Importing the Dataset to PostgrSQL

First I created the following tables:
-air_pollution
-cities

For the SQL table creation I usually use pgAdmin4, and for loading the data into the tables I use Bash (Yes, I know I could have also done it in pgAdmin4, but that's how I got used to it).


Creating the Visualization
My goal was to create insights where one can compare any city he/she likes to and also change the dates for his/her liking.
I also didn't want to overcomplicate things, and tried to keep it simple so anyone can make conclusions from the dashboard easily.
I wanted to make the dashboard interactive in order to drill into specific areas, months, years, etc.


Key Takeaways from the Data


Of course, properties in LA are expensive, but if you are able to purchase one as an investment, the conclusions drawn here provide valuable insights!
