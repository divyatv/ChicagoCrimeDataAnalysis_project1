# Project01_Panda_UNCBootCamp

Instructions to run the code
--------------------------------------
There are ---- files in the project.
1) start.ipynb - file will load a widget to select timeline, crimetype, wards and other user specific attributes.
This code calls the following functions in crimes_weather.ipynb 
   read_crime_data
   get_crimes_count
   read_weather_data
   get_crime_weather_merged

Sample put of the execution:   
start reading .....  Tue Jul  9 19:12:58 2019
elapsed time= 1686.679203748703
columns= ['Date', 'Year', 'Month', 'Humidity daily mean', 'Mean Sea Level Pressure daily mean', 'Precipitation daily sum', 'Total Cloud Cover daily mean', 'Sunshine Duration daily sum', 'Wind Speed daily mean', 'Temperature daily max (F)']
done reading .....  Tue Jul  9 19:43:18 2019


NOte: the code takes 30 mins to run on a 16GB ra machine.
   
2) crimes_weather.ipynb -- file has code to build plot relationships between crime types and weather and wards.


Step1:
-----
1) Run the file start.ipynb -> all cells
2) 