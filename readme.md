# WeatherPy

Creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator, utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

* Randomly selected 500 unique (non-repeat) cities based on latitude and longitude.
* Performed a weather check on each of the cities using a series of successive API calls.
* Included a print log of each city as it's being processed with the city number and city name.
* Saved a CSV of all retrieved data and a PNG image for each scatter plot.

### Scatter Plots

* Temperature (F) vs. Latitude

    ![Temerature (F) vs Latitude](output_data/cityvstemp.png)
* Humidity (%) vs. Latitude

    ![Humidity (%) vs. Latitude](output_data/cityvshumidity.png)
* Cloudiness (%) vs. Latitude

    ![Cloudiness (%) vs. Latitude](output_data/cityvscloudiness.png)
* Wind Speed (mph) vs. Latitude

    ![Wind Speed (mph) vs. Latitude](output_data/cityvswindspeed.png)

### Linear Regression Plots

* Northern Hemisphere - Temperature (F) vs. Latitude

    ![Northern Hemisphere - Temperature (F) vs. Latitude](output_data/nh_maxvslat_lr.png)

* Southern Hemisphere - Temperature (F) vs. Latitude

    ![Southern Hemisphere - Temperature (F) vs. Latitude](output_data/sh_maxvslat_lr.png)
* Northern Hemisphere - Humidity (%) vs. Latitude

    ![Northern Hemisphere - Humidity (%) vs. Latitude](output_data/nh_humidityvslat_lr.png)
* Southern Hemisphere - Humidity (%) vs. Latitude

    ![Southern Hemisphere - Humidity (%) vs. Latitude](output_data/sh_humidityvslat_lr.png)
* Northern Hemisphere - Cloudiness (%) vs. Latitude

    ![Northern Hemisphere - Cloudiness (%) vs. Latitude](output_data/nh_latvsclouds_lr.png)
* Southern Hemisphere - Cloudiness (%) vs. Latitude

    ![Southern Hemisphere - Cloudiness (%) vs. Latitude](output_data/sh_latvsclouds_lr.png)
* Northern Hemisphere - Wind Speed (mph) vs. Latitude

    ![Northern Hemisphere - Wind Speed (mph) vs. Latitude](output_data/nh_latvswindspeed_lr.png)
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

    ![Southern Hemisphere - Wind Speed (mph) vs. Latitude](output_data/sh_latvswindspeed_lr.png)
