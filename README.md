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

Northern cities have lower air pollution.            
The PM2.5 and PM10 values are almost at an identical level.
Given the data the most polluted city from 2021 until now is Paris according to the AQI Index and PM levels.                    
The least polluted city in 2021 is Reykjavik, in 2022 it is Stockholm, and in 2023 so far still Stockholm.
For the seasonal pollution it is spring that has a worse pollution than other seasons, but if we only count months February and March had the most pollution.    
Ranking the the cities by PM 2.5:

2021:    
1. Paris    
2. Bucharest    
3. Valletta

2022:    
1. Paris    
2. Bucharest    
3. Rome

2023:    
1. Paris    
2. Bucharest    
3. Rome    

Ranking the the cities by PM 10:   

2021:    
1. Valletta    
2. Paris    
3. Bucharest
 
2022:    
1. Paris    
2. Valletta    
3. Bucharest
  
2023:    
1. Paris    
2. Bucharest    
3. Valletta    

The least polluted season by AQI is the summer, followed by the autumn with only a little difference. The least polluted month in 2021 was May and in 2022 it was September.

PM.: Please keep in mind that the data for 2023 is not complete, I will add the rest of it later this year.
