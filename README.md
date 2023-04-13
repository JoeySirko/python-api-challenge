# python-api-challenge

In the part 2 for VacationPY i understand it says 

Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

A max temperature lower than 27 degrees but higher than 21

Wind speed less than 4.5 m/s

Zero cloudiness

But my api wasn't giving me any results for this 
this was my code i used 
ideal_weather_df = city_data_df[(city_data_df["Max Temp"] > 21) & (city_data_df["Max Temp"] < 27) & (city_data_df["Wind Speed"] < 4.5) & (city_data_df["Cloudiness"] == 0)].dropna()
city_data_df = city_data_df.dropna()
ideal_weather_df.head()

i changed the temperature values so I could have results generated on the map for step 5
