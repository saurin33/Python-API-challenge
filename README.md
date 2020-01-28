#Weather Analysis:

In this project we have randomly selected more than 500 cities between latitude(-90, 90) and longitude (-180, 180) and created a representation model of weather across world cities.

We made series of scatter plots to showcase the following relationships:

•	Temperature (F) vs. Latitude
•	Humidity (%) vs. Latitude
•	Cloudiness (%) vs. Latitude
•	Wind Speed (mph) vs. Latitude

After that we ran linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

•	Northern Hemisphere - Temperature (F) vs. Latitude
•	Southern Hemisphere - Temperature (F) vs. Latitude
•	Northern Hemisphere - Humidity (%) vs. Latitude
•	Southern Hemisphere - Humidity (%) vs. Latitude
•	Northern Hemisphere - Cloudiness (%) vs. Latitude
•	Southern Hemisphere - Cloudiness (%) vs. Latitude
•	Northern Hemisphere - Wind Speed (mph) vs. Latitude
•	Southern Hemisphere - Wind Speed (mph) vs. Latitude

We have also added our analysis about the relationships after each plot.

After that we have narrowed down the DataFrame to find ideal weather condition, like:
•	A max temperature lower than 80 degrees but higher than 70.
•	Wind speed less than 10 mph.
•	Zero cloudiness.

Using Google Places API we have found the first hotel for each city located within 5000 meters of your coordinates for a perfect vacation.

