# Background
As affectionados of travel and pent-up covid demand, we decided to evaluate the Transit Lines database found as part of our case study completed on May 21st, 2021.

# Data
This historical and international dataset documents how transit lines have evolved all over the world. Besides time, number of lines, and line length, the dataset contains spatial locations that could be mapped using a geospatial library in Python like GeoPandas or Folium.

The dataset is more fully described on Kaggle, and can be found [here](https://www.kaggle.com/citylines/city-lines).

# Exploratory Data Analysis

After importing and cleaning our data using **pandas**, each team member 

# Station Lifetimes

One of the main questions that we had was to determine the typical lifespan of a station in each area. While the majority of the stations are still in use, a sizable number of stations have closed over the years due to a lack of funding, improvements or migration. To answer this, we initially plotted all the station closures throughout the world in relation to station age frequency and opening date. There appears to be a sharp drop off in station closure age after 65-75 range, which should be expected considering the age and usage. What was surprising was how many units were clustered between 40-60. 

Investigating further, the stations that were closed were mostly built around the turn of the ~1900-1930s. Historically, this makes sense with a lot of the rebuilding that occured as a result of the world wars and explosive booms. The stations were retired after an median 54 years, with 75% of the stations closing by 1972. There appears to be a slight inverse linear correlation with the age of the station with the year it opened.

![GitHub Logo](png/worldwide_station_age.png)

Diving a bit deeper into the station age, we decided to focus into the top cities that had the most open stations currently. What was surprising was how few stations were closed in the cities with the most stations and how many Tokyo and New York had shut down over the last 100 years.

![GitHub Logo](png/city_station_age.png)

