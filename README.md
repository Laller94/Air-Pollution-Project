Project Title: Air Pollution Analysis in European Capital Cities (2021-2023)

Project Summary:

The primary objective of this project was to conduct an extensive analysis of historical air pollution data spanning from January 2021 to June 2023 across major capital cities in Europe.

Skills Applied:

-Bash for comprehensive data cleaning.

-SQL for data analysis and querying.

-Power BI for data visualization and presentation.

Desired Insights

Identification of the most polluted city in Europe from 2021 to 2023.
Determination of the city with the highest air quality during this period.
Ranking of capital cities based on PM 2.5 and PM 10 levels.
Assessment of seasonal variations in pollution levels across Europe.

Data Preparation:

The dataset was meticulously sourced through the OpenWeatherMap API. 
Additionally, city data was extracted from Learnit3D.fi using a combination of BeautifulSoup and Python's Requests library.

Database Management:

The data was effectively imported into PostgreSQL, where two crucial tables were created:

'air_pollution'
'cities'
The data import and table creation processes were streamlined using a combination of pgAdmin4 and Bash scripting.

Data Visualization:

My goal was to create an interactive dashboard that allows users to compare cities and customize date ranges.
The focus was on simplicity to ensure that users could easily draw conclusions from the displayed insights.
Interactivity was incorporated to enable users to explore specific areas, months, and years.

Key Takeaways from the Data:

Northern European cities consistently exhibited lower levels of air pollution.
PM2.5 and PM10 levels closely correlated throughout the study.
Based on the AQI Index and PM levels, Paris consistently ranked as the most polluted city from 2021 to the present.
The cleanest city in 2021 was Reykjavik, followed by Stockholm in 2022 and 2023 (to date).
Spring exhibited the highest pollution levels among the seasons, with February and March being the most polluted months.

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

Seasonal Insights:

The summer season consistently registered the lowest AQI levels, closely followed by autumn. May in 2021 and September in 2022 emerged as the months with the least pollution.

Note: Please bear in mind that the data for 2023 is not yet complete, and additional updates will be incorporated later this year to ensure the project's completeness and accuracy.
The least polluted season by AQI is the summer, followed by the autumn with only a little difference. The least polluted month in 2021 was May and in 2022 it was September.
