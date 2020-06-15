# python-api-challenge
## WeatherPy

### Summary
The objective of this work is to visualize the weather of 500+ cities across the world of varying distance from the equator.
The following are the conclusions of the analysis:

### Data Analysis
#### Getting the Data
Data was randomly selected from OpenWeatherMap API where information about cities and their respective latitude, longitude, maximum temperature, humidity, cloudiness, wind speed, country and date was retreived. Table below shows a sample of the data.

![Table1](WeatherPy/Images/Table1.jpg)

#### Inspecting the Data
Cities with humidity higher than 100% were removed from the dataset. The basic statistics of data is shown in the table below.

![Table2](WeatherPy/Images/Table2.jpg)

Ten outliers for Humidity were removed, and the final cleaned dataframe was created. Table below shows a sample of the results.
![Table3](WeatherPy/Images/Table3.jpg)

#### Plotting the Data

The latitude vs temperature plot below shows how the temperature increases as latitude is closer to the Equator.

![Figure1](WeatherPy/Images/Fig1.png)

The latitude vs humidity plot below shows humidities above 50% around the Equator ~10 to 10degrees, but for the rest od the latitudes humidty can vay from 5 to 100%. There is no apparent correlation.

![Figure2](WeatherPy/Images/Fig2.png)

The latitude vs cloudiness plot below shows no correlation, data is very sparced.

![Figure3](WeatherPy/Images/Fig3.png)

The latitude vs wind speed plot below shows no correlation, data is very sparced.

![Figure4](WeatherPy/Images/Fig4.png)

### Comparing Northern and Southern Hemispheres

The Northern Hemisphere Maximum Temperature vs Latitude plot shows a negative correlation, temperature decreases as latitude increases. The r^2 is low, but still the tendency can be seen and it correponds to what is expected.

![Figure5](WeatherPy/Images/Fig5.png)

The Southern Hemisphere Maximum Temperature vs Latitude plot shows a positive correlation, temperature increases as negative latitude increases. The r^2 is low, but still the tendency can be seen and it correponds to what is expected.

![Figure6](WeatherPy/Images/Fig6.png)

The Northern Hemisphere Humidity vs Latitude plot shows a tendency of a negative correlation, however the r^2 is very low so there is no correlation.

![Figure7](WeatherPy/Images/Fig7.png)

The Southern Hemisphere Humidity vs Latitude plot shows a tendency of a postive correlation, however the r^2 is very low so there is no correlation.

![Figure8](WeatherPy/Images/Fig8.png)

The Northern Hemisphere Cloudiness vs Latitude plot shows no correlation.

![Figure9](WeatherPy/Images/Fig9.png)

The Southern Hemisphere Cloudiness vs Latitude plot shows no correlation.

![Figure10](WeatherPy/Images/Fig10.png)

The Northern Wind Speed Cloudiness vs Latitude plot shows no correlation.

![Figure11](WeatherPy/Images/Fig11.png)

The Southern Hemisphere Wind Speed vs Latitude plot shows no correlation.

![Figure12](WeatherPy/Images/Fig12.png)

## VacationPy
