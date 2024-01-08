# python-api-challenge
## Summary
This challenge is aimed as utilising API platforms, such as OpenWeatherMap and Geoapify, to create a code to generate a list of cities, their corresponding weather conditions and hotels in the area.
## Installation and Running
For this code to run successfully, python is required to be installed along with the pandas tool library and either Jupyter lab or Jupyter notebook, and citipy. One method to install these programs is to download Anaconda - link below. In addition, an API Key is required for OpenWeatherMap and Geoapify. To obtain API keys, regristration is required with the links to these platforms below.
Once all this has been completed, open the file within Jupyter, ensure that the input files are directed correctly and API keys have been referenced, and run!
Anaconda install: https://docs.anaconda.com/free/anaconda/install/
citipy install: https://pypi.org/project/citipy/
OpenWeatherMap: https://openweathermap.org/
Geoapify: https://openweathermap.org/
## Description
The data used for this notebook is obtained through citipy library, OpenWeatherMap API, and Geoapify API.
To begin, from citipy library a list of up to 1500 cities will be created. OpenWeatherMap will then be ustilised to obtain the correspoinding weather data for each city and the code shall create a DataFrame to store this information.
Data that the OpenWeatherMap provides for the currrent day includes:
* maximum temperature
* humidity
* cloudiness
* wind speed
The notebook will then display the cities latititude against the above OpenWeatherMap outputs listed as a scvatter plot, including regression modelling.
This notebook also outputs the city DataFrame as a csv file, as well as the scatter plots as individual jpeg files.

In a seperate notebook, the city csv file is imported and a map plot is created showing each city. The users ideal vacation weather can then be amended to suit, with another map plot displayed including the closest hotel in each city.

## External Assistance
This code had assistance from both the Instructor, Sean Whitehead, and AskBCS Learning Assistant to help create the function required for scatter plot creation. Note, the scatter plots were created successfully but assistance was needed for the function specifically. 
