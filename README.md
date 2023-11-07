# Bike-Sharing-Analysis-using-Machine-Learning

### Context:


Bike-sharing systems represent a modern iteration of conventional bike rental services, characterized by a fully automated process encompassing membership, rental, and return procedures. These systems enable users to effortlessly rent bicycles from one location and conveniently return them to another. Presently, more than 500 bike-sharing programs are operational worldwide, boasting a cumulative fleet of over 500,000 bicycles. The prominence of these systems has surged, garnering significant attention due to their pivotal contributions to traffic management, environmental sustainability, and public health concerns. The multifaceted benefits offered by bike-sharing systems have fostered widespread interest and recognition in various domains.


### Objective:

Which factors have an impact on the target variable, and what actionable insights can be derived from the analysis to inform business recommendations?

In what ways can ensemble techniques such as Bagging, Boosting, and Stacking be leveraged to construct a predictive model for estimating the rental count of bikes?

### Data Description:

The bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions, precipitation, the day of week, season, the hour of the day, etc. can affect the rental behaviors.

- instant: record index
- dteday : date
- season : season (1:spring, 2:summer, 3:fall, 4:winter)
- yr : year (0: 2011, 1:2012)
- mnth : month ( 1 to 12)
- hr : hour (0 to 23)
- holiday : whether the day is holiday or not
- weekday : day of the week
- workingday : if day is neither weekend nor holiday then 1, otherwise is 0.
- weathersit : 
	- 1: Clear, Few clouds, Partly cloudy
	- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
	- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
	- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are divided by 41 (max)
- atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max). The “feel like” temperature relies on environmental data including the ambient air temperature, relative humidity, and wind speed to determine how weather conditions feel to bare skin.
- hum: Normalized humidity. The values are divided by 100 (max)
- windspeed: Normalized wind speed. The values are divided by 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered
