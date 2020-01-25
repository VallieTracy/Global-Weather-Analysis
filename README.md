*python-api-challenge*

Background
----------

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"
Now, we know what you may be thinking: "Duh. It gets hotter..."
But, if pressed, how would you prove it?

*WeatherPy Objectives*
-------------------
In WeatherPy, I'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I will utilize a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.
My first objective is to build a series of scatter plots to showcase the following relationships:

*Temperature (F) vs. Latitude*          
*Humidity (%) vs. Latitude*         
*Cloudiness (%) vs. Latitude*        
*Wind Speed (mph) vs. Latitude*         

My next objective is to run linear regression on each relationship, separating them by Northern and Southern Hemisphere:

*Northern Hemisphere - Temperature (F) vs. Latitude*     
*Southern Hemisphere - Temperature (F) vs. Latitude*     
*Northern Hemisphere - Humidity (%) vs. Latitude*     
*Southern Hemisphere - Humidity (%) vs. Latitude*     
*Northern Hemisphere - Cloudiness (%) vs. Latitude*     
*Southern Hemisphere - Cloudiness (%) vs. Latitude*     
*Northern Hemisphere - Wind Speed (mph) vs. Latitude*     
*Southern Hemisphere - Wind Speed (mph) vs. Latitude*     


